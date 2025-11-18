## ARIGALA LAVANYA
## 212222060019


## Exp 5 Experimental verification of frequency response of Digital fiber optic link
# Digital Fiber Optic Link Analysis (600nm)

## AIM
To analyze the relationship between input and received signal of a 600nm fiber optic cable using digital link.

---

## EQUIPMENTS REQUIRED
- Fiber optic trainer kit ST 2502  
- Power supply  
- Patch cords  
- CRO (Cathode Ray Oscilloscope)  
- 660 nm fiber cable  

---

## THEORY

Fiber optic links can be used for transmission of digital as well as analog signals. A fiber optic link typically consists of three main elements:
- **Transmitter**: Converts the electrical input signal into optical (light) energy.
- **Optical Fiber**: Serves as the transmission medium for the light signal.
- **Receiver**: Converts the received light back into an electrical signal, preserving the original signal pattern.

---

## PROCEDURE

1. Connect the power supply to the board.  
2. Ensure that all switched faults are set to ‘Off’.  
3. Make the following connections:  
   a. Connect the 1 KHz square wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to comparator 1’s input.  
   d. Connect comparator 1's output to AC amplifier 1's input.  
4. On the board, switch emitter 1's driver to digital mode.  
5. Switch on the power.  
6. Monitor both the inputs to comparator 1 (TP13 & TP14). Slowly adjust the comparator's bias preset until the DC level on TP13 lies midway between the high and low levels of the signal on TP14.  
7. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
8. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
9. Calculate the bandwidth by determining the gain in decibels (dB).  

---


## BLOCK DIAGRAM

<img width="850" height="468" alt="image" src="https://github.com/user-attachments/assets/444382d4-244e-4893-a5a4-c00ad6f2dc61" />


---

## CONNECTION DIAGRAM  
**Setting up a Digital Link**

<img width="582" height="195" alt="image" src="https://github.com/user-attachments/assets/4d7a06ab-61b6-49aa-bd08-e3e9d78a529a" />


---

## TABULATION  
**Transmission through Digital Link**

| Frequency (Hz) | Output Signal Amplitude (Vo) | Gain = Vo/Vi | Gain in dB |
|----------------|------------------------------|--------------|------------|
|                |                              |              |            |

---
[DIGITA;.pdf](https://github.com/user-attachments/files/23599254/DIGITA.pdf)

## MODEL GRAPH

<img width="295" height="171" alt="image" src="https://github.com/user-attachments/assets/11f9894b-f545-470c-a2ea-6663102f2b2f" />


---

## RESULT

The frequency response of a digital fiber optic link at approximately 600nm is primarily limited by dispersion, which causes signal distortion and reduces integrity at higher frequencies. The system acts as a low-pass filter with a finite bandwidth, and the 600nm wavelength, while suitable for lab demonstrations, exhibits higher attenuation and dispersion than near-infrared wavelengths used for long-distance communication
