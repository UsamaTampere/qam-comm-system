# QAM Communication System Simulation

This MATLAB project simulates a 16-QAM communication system, including transmitter design, channel modeling with noise, receiver design, LMS equalization, and basic error control coding with Hamming (7,4) code.

---

## Features

- Bit generation and 16-QAM modulation with Gray coding  
- Root Raised Cosine (RRC) pulse shaping  
- Transmission over a multipath channel with AWGN noise  
- Matched filtering and LMS adaptive equalization at the receiver  
- Bit error rate (BER) calculation without ECC  
- Implementation of Hamming (7,4) error correction code  

---

## Output Plots

### Transmitted Constellation  
![Transmitted Constellation](figures./transmitted_constellation.png)  

### Transmitted Eye Diagram  
![Transmitted Eye Diagram](figures./transmitted_eye_diagram.png)  

### Channel Frequency Response  
![Channel Frequency Response](figures/channel_frequency_response.png)  

### Received Eye Diagram  
![Received Eye Diagram](figures/received_eye_diagram.png)  

### LMS Error Convergence  
![LMS Error](figures/lms_error.png)  

### Equalizer Frequency Response  
![Equalizer Frequency Response](figures/equalizer_frequency_response.png)  

### Equalized Constellation  
![Equalized Constellation](figures/equalized_constellation.png)  

---

## How to Run

1. Open MATLAB.  
2. Load the main script file (e.g., `qam_comm_system.m`).  
3. Run the script to simulate the communication system and generate plots.  

---

## Author

Usama Bin Sohaib  
Electrical Engineering Student  
Tampere University  
Email: usamabin.sohaib@tuni.fi  
