---
title: "FMCW Radar Signal Processing"
excerpt: "Implemented a real-time FMCW radar system using NI USRP B210 and LabVIEW by generating and transmitting linear chirp signals. The receiver module captured echo signals to extract time-delay and estimate range. The system was first simulated in LabVIEW, then validated through physical measurements and spectrum analysis. This project provided hands-on experience in SDR-based radar systems, signal integrity verification, and time-frequency analysis.<br/><img src='/images/fmcw_radar_1.jpg'>"
collection: portfolio
---

Radar Signal Processing
(Semester 4, Bandung Institute of Technology (ITB))

**Tools & Equipment Used**
- NI USRP B210
- LabVIEW
- Spectrum Analyzer (for validation)

**Objective**
To implement and test an FMCW (Frequency Modulated Continuous Wave) radar signal generation and reception system using NI USRP and LabVIEW, and validate performance through real-time measurement.

**Description**
In this project, I designed an FMCW radar system by generating a linear frequency chirp signal in LabVIEW and transmitting it via USRP. The received signal was captured using another USRP module and analyzed to extract time-delay information. The signal was initially simulated in LabVIEW to verify the accuracy of the range extraction algorithm in response to the echo signal at the receiver. Once validated, the algorithm was implemented on the USRP hardware for real-time object detection. Measurements were verified using a spectrum analyzer and compared against theoretical chirp parameters to ensure proper signal generation. Finally, the receiver’s performance was confirmed by successfully extracting the object’s range from the captured echo signal.

**Outcome / Result**
- Successfully demonstrated end-to-end FMCW signal transmission and reception using USRP
- Gained hands-on experience in software-defined radio (SDR) implementation and real-time signal testing

Screenshots / Diagrams
