# 16-QAM Communication System MATLAB Project

This project implements a 16-QAM digital communication system in MATLAB. It covers the full transmission chain including:

- Bit generation and Gray encoding
- 16-QAM modulation and constellation mapping
- Pulse shaping using Root Raised Cosine (RRC) filter
- Transmission over a multipath channel with additive white Gaussian noise (AWGN)
- Receiver matched filtering and downsampling
- LMS adaptive equalization to combat channel distortion
- Symbol detection and calculation of Bit Error Rate (BER)
- Implementation of Hamming (7,4) Error Control Coding (ECC) for improved reliability

---



## How to Run

1. Open MATLAB and navigate to the project folder.
2. Run the main script file (e.g., `qam_communication_system.m`).
3. The script will display:
   - Transmitted and received constellation plots
   - Eye diagrams before and after channel effects
   - Frequency responses of filters and equalizers
   - Bit Error Rate (BER) calculation results
4. You can modify parameters like SNR, symbol rate, or equalizer settings directly in the script.

---

## Key MATLAB Functions Used

- `qammod`, `qamdemod` — For QAM modulation and demodulation
- `rcosdesign` — For designing Root Raised Cosine filters
- `awgn` — Adding Gaussian noise
- `conv` — For filtering and channel convolution
- Custom LMS equalizer implementation

---

## License

This project is for academic use. Feel free to contact me for questions or collaboration.

---

## Contact

Usama Bin Sohaib  
Email: usamabin.sohaib@tuni.fi  
Tampere University, Finland
