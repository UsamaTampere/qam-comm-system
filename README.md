# QAM Communication System Simulation

This MATLAB project simulates a 16-QAM communication system including transmitter, channel with noise, receiver with LMS equalization, and error control coding (Hamming (7,4)).

---

## Features

- Bit generation and 16-QAM Gray mapping
- Pulse shaping with Root Raised Cosine filter
- Transmission over a multipath channel with AWGN noise
- LMS equalizer to mitigate channel effects
- BER calculation without ECC
- Implementation of Hamming (7,4) error control coding (to be completed)

---

## MATLAB Code Files

- `qam_comm_system.m`: Main simulation script including transmitter, channel, receiver, and equalization.
- (Add other code files here if any)

---

## Output Plots

### Transmitted Constellation  
<p align="center">
  <img src="figures./transmitted_constellation.png" alt="Transmitted Constellation" width="400"/>
</p>

### Transmitted Eye Diagram  
<p align="center">
  <img src="figures./transmitted_eye_diagram.png" alt="Transmitted Eye Diagram" width="400"/>
</p>

### Channel Frequency Response  
<p align="center">
  <img src="figures/channel_frequency_response.png" alt="Channel Frequency Response" width="400"/>
</p>

### Received Eye Diagram  
<p align="center">
  <img src="figures/received_eye_diagram.png" alt="Received Eye Diagram" width="400"/>
</p>

### LMS Error Convergence  
<p align="center">
  <img src="figures/lms_error.png" alt="LMS Error" width="400"/>
</p>

### Equalizer Frequency Response  
<p align="center">
  <img src="figures/equalizer_frequency_response.png" alt="Equalizer Frequency Response" width="400"/>
</p>

### Equalized Constellation  
<p align="center">
  <img src="figures/equalized_constellation.png" alt="Equalized Constellation" width="400"/>
</p>

---

## How to Run

1. Open MATLAB.
2. Run the `qam_comm_system.m` script.
3. The script generates plots and calculates BER.
4. Saved figures are in the `figures` folder.

---

## Author

Usama Bin Sohaib  
Student ID: 153015748  
Email: usamabin.sohaib@tuni.fi  
Tampere University, Finland

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
