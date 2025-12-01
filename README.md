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

Fiber optic links can be used for transmission of digital as well as analog signals. Basically a fiber optic link contains three main elements, a transmitter, an optical fiber and a receiver. The transmitter module takes the input signal in electrical form and then transforms it into optical (light) energy containing the same information. The optical fiber is the medium which takes the energy to the receiver. At the receiver light is converted back into electrical form with the same pattern as originally fed to the transmitter.

TRANSMITTER:

LED, digital DC coupled transmitters are one of the most popular varieties due to their ease of fabrication. We have used a standard TTL gate to drive a NPN transistor, which modulates the LED SFH450V or SFH 756V source. (Turns it on and off).

RECEIVER:

SFH-551V is a digital optodetector. It delivers a digital output, which can be processed directly with little additional external circuitry. The integrated circuit inside the SFH551V optodetector comprises the photodiode device, a transimpedance amplifier, a comparator and a level shifter.

The photodiode converts the detected light into a photocurrent. With the aid of an integrated lens the light emanating from the plastic Fiber is almost entirely focused on the surface of the diode. At the next stage the trans-impedance amplifier converts the photocurrent into a voltage. In the comparator, the voltage is compared to a reference voltage. In over to ensure good synchronism between the reference and the trans- impedance output voltage, the former is derived from a second circuit of a similar kind, which incorporates a “blind” photodiode. The comparator derives a level shifter with an open collector output stages. Here a catch diode (similar to Schottky-TTL) prevents the saturation of the output transistor, thus limiting the output voltage to the supply voltage. pattern.

---

## PROCEDURE

 Refer to the block diagram & carry out the following connections and settings.  Connect the power supply with proper polarity to the kit link-B and switch it on.  Keep all Switch Faults in OFF position.  Keep switch SW8 towards TX position.  Keep switch SW9 towards TX1 position.  Keep switch SW10 towards TTL position.  Keep Jumper JP5 towards +5V position.  Keep Jumpers JP6 shorted.  Keep Jumper JP8 towards Pulse position.  Feed TTL Square wave signal of 1KHz from the function generator to the IN post of Digital Buffer.

 Connect the output post OUT of Digital Buffer to the post TX IN of Transmitter.  Slightly unscrew the cap of SFH756V (660nm). Do not remove the cap from the connector. Once the cap is loosened, insert the one meter fiber into the cap. Now tighten the cap by screwing it back.  Connect the other end of the Fiber to detector SFH551V (Photo Transistor Detector) very carefully.  Observe the detected signal at post TTL OUT on oscilloscope.

Uploading image.png…

 To measure the digital bandwidth of the phototransistor vary the input signal frequency and observe the detected signal at various frequencies.  Determine the frequency at which the detector stops recovering the signal. This determines the max. bit rate on the digital link.  Keep switch SW9 towards TX2 position.  Keep Jumper JP7 towards +5V position.  Remove fiber cable from SFH756V (660nm) and slightly unscrew the cap of SFH450V (950nm). Do not remove the cap from the connector. Once the cap is loosened, insert the one meter fiber into the cap. Now tighten the cap by screwing it back.  Observe the detected signal at post TTL OUT on oscilloscope.

Uploading image.png…
---


## BLOCK DIAGRAM

<img width="850" height="468" alt="image" src="https://github.com/user-attachments/assets/444382d4-244e-4893-a5a4-c00ad6f2dc61" />


---

## CONNECTION DIAGRAM  
**Setting up a Digital Link**
<img width="1280" height="900" alt="514708522-1d82f476-c35a-4769-a2fa-75e8b5c71c1f" src="https://github.com/user-attachments/assets/7eecbbd1-0e4c-4c55-afce-21749cf67b65" />


<img width="582" height="195" alt="image" src="https://github.com/user-attachments/assets/4d7a06ab-61b6-49aa-bd08-e3e9d78a529a" />


---

## TABULATION  
**Transmission through Digital Link**
<img width="878" height="1280" alt="514708553-ba09ad4b-1eba-431a-8d68-69651bba0ae8" src="https://github.com/user-attachments/assets/97405846-335b-46eb-8416-daea41f57e24" />


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
