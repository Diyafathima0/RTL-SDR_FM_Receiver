# RTL-SDR FM Receiver using SDRSharp
A hands-on experiment to receive and listen to **FM radio broadcasts** using an **RTL-SDR dongle** and **SDR# (SDRSharp)** software.  
This project demonstrates how analog FM signals can be captured, tuned, and demodulated using a low-cost SDR setup.

## Objectives
- Understand how Software Defined Radio (SDR) works.
- Capture and demodulate FM radio signals in the 88–108 MHz band.
- Visualize frequency spectra and learn FM signal properties.
- Relate practical SDR results with theoretical Communication concepts.

## Tools & Components
| Component | Description |
|------------|-------------|
| **Hardware** | RTL-SDR USB Dongle + Antenna |
| **Software** | SDR# (SDRSharp), Zadig driver |
| **Frequency Range Tested** | 92.7 MHz, 94.3 MHz |
| **Operating System** | Windows 11 |

## Experimental Setup
Antenna → RTL-SDR → SDR# Software → FM Demodulation → Audio Output

**Procedure:**
1. Installed SDR# and configured the RTL-SDR driver using Zadig.
2. Tuned SDR# to 92.7 MHz (local FM station).
3. Set **WFM (Wideband FM)** mode.
4. Adjusted gain and bandwidth for clear signal reception.
5. Observed live **spectrum** and **waterfall display**.
6. Listened to real-time FM audio.

## Results
| Observation | Details |
|--------------|----------|
| Center Frequency | 93.5 MHz |
| Mode | WFM |
| Bandwidth | 200 kHz |
| Output | Clear audio playback |

**Demo Video:** [Watch the FM Receiver in action](https://github.com/Diyafathima0/RTL-SDR_FM_Receiver/blob/48753d361397bca00f4de76f679c6cccd6132803/Screen%20Recording%202025-10-05%20203715.mp4)

## Concepts Learned
- Fundamentals of FM modulation and demodulation.  
- How SDR digitizes analog signals using IQ sampling.  
- Relation between **gain**, **bandwidth**, and **signal quality**.  
- Basics of real-time signal visualization.  

## Author
**Diya Fathima**  
3rd Year, B.Tech ECE, SRMIST  
(www.linkedin.com/in/diya-fathima-a197bb293)

##  Tags
`#SDR` `#RTLSDR` `#FMReceiver` `#SDRSharp` `#ECE` `#SignalProcessing`
