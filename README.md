#**EX.NO:** 1  # EXPERIMENTAL VERIFICATION OF AMPLIFIER INVERTING, NON INVERTING , DIFFERENTIAL AMPLIFIER AND INSTRUMENTATION AMPLIFIERS
**DATE:**  
---

## AIM
To design and construct an Inverting, Non-Inverting, Differential and Instrumentation amplifiers.

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 10k,100k | 2 |
| 7 | Connecting wires and probes | As required | — |

---

## THEORY

Op-amp in open-loop configuration has limited application due to its enormous open-loop gain. Controlled gain can be achieved by taking a part of the output signal to the input through feedback.  
This is called a **Closed-Loop Configuration**.

The four basic types of closed-loop amplifier configurations are:
- Inverting amplifier  
- Non-inverting amplifier  
- Differential amplifier
- Instrumentation amplifier 

The entire configuration can operate with either AC or DC input.
		
 

---

### **Inverting Amplifier**

This is the most widely used op-amp configuration.  
The output voltage Vo  is fed back to the inverting input terminal through the  Rf - R1 network.  
The negative sign in gain indicates a **phase shift of 180°**.


Acl = -RF/R1

PIN DIAGRAM

![WhatsApp Image 2025-12-05 at 15 21 50_352f849e](https://github.com/user-attachments/assets/71aad88a-a5db-4007-8c99-39ddbc6e4f56)


CIRCUIT DIAGRAM: INVERTING AMPLIFIER:

![WhatsApp Image 2025-12-05 at 15 25 15_c01c666a](https://github.com/user-attachments/assets/010092cb-a4a7-4356-b15e-0fc2b5fd34c2)


MODEL GRAPH 

<img width="344" height="212" alt="image" src="https://github.com/user-attachments/assets/64cb1a1b-8530-40dd-b0ca-7ac0ced90287" />



DESIGN:

Inverting amplifier:
<img width="1600" height="1024" alt="image" src="https://github.com/user-attachments/assets/ded38caa-5dea-451a-8e8f-f0b2f8782c17" />
<img width="1600" height="470" alt="image" src="https://github.com/user-attachments/assets/26c46213-c739-4b8e-98f2-e866a27b450d" />



PROCEDURE:
Inverting amplifier:

1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1 & compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.


## TABULATION

![WhatsApp Image 2025-12-05 at 15 38 14_c463bdc9](https://github.com/user-attachments/assets/3140870b-80f4-4a19-bc9d-df2b563933a1)




---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-12-05 at 15 30 03_a7059a85](https://github.com/user-attachments/assets/c10ac7ba-43db-4e31-a084-d66b0db35930)

![WhatsApp Image 2025-12-05 at 15 30 02_a0bb48b6](https://github.com/user-attachments/assets/e080361f-d4a9-4552-8fc7-03926b0d1e99)

---
### **Non-Inverting Amplifier**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1


---

## CIRCUIT DIAGRAM

![WhatsApp Image 2025-12-05 at 15 40 23_50d07828](https://github.com/user-attachments/assets/3022e972-fed4-4c8e-bae4-348f61f28a03)

## MODEL GRAPH
<img width="321" height="178" alt="image" src="https://github.com/user-attachments/assets/c4145a7e-f67a-4bcd-84d7-0226d9b00e54" />

#DESIGN




PROCEDURE:
### **For  Non-Inverting Amplifier**
1. Select R1  as a constant value and choose a value for Rf .  
2. Connect the circuit as per the diagram.  
3. Apply constant amplitude input voltage.  
4. Measure the output voltage amplitude for different V1 using DSO.  
5. Compare practical and theoretical values of Vo .  
6. Verify that practical gain ≈ theoretical gain.  
7. Plot the input vs. output waveform for one practical case.

## TABULATION

<img width="1198" height="1600" alt="image" src="https://github.com/user-attachments/assets/5482235a-2e0f-48b2-bc7e-deae5564f480" />


## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-12-05 at 15 44 37_112015d3](https://github.com/user-attachments/assets/0ee6e437-26fa-4c65-8fa2-f1cd05b3078b)


![WhatsApp Image 2025-12-05 at 15 44 42_d2da0514](https://github.com/user-attachments/assets/b319bf33-23ef-4a28-916e-24602c0fb78a)


---
## DIFFERENTIAL AMPLIFIER

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1
## CIRCUIT DIAGRAM
![WhatsApp Image 2025-12-05 at 15 31 31_184d58f8](https://github.com/user-attachments/assets/638105dc-c5c5-4e6b-9538-505590aa1a93)


MODEL GRAPH1:

![WhatsApp Image 2025-12-05 at 15 31 21_9787ae91](https://github.com/user-attachments/assets/0927e5c9-90b7-409f-842d-a57a3f940667)


## DESIGN
<img width="1376" height="1600" alt="image" src="https://github.com/user-attachments/assets/04a1f406-c5ad-414a-8a01-ede3dddd5c42" />


### **Differential Amplifier**

AV = Vo/{V1 - V2} = -Rf/R1


Take  A = 10 
⇒  Rf = 10R1   
Choose  R1 = 1kOhm, Rf = 10kOhm

---



## PROCEDURE (Differential Amplifier)
1. Select  R1, R2, R3, Rf  such that R1 = R2  and  R3 = Rf .  
2. Connect the circuit as per the circuit diagram.  
3. Apply constant inputs Vin1 and  Vin2 .  
4. Measure output voltage using DSO.  
5. Compare theoretical and practical  Vo .  
6. Verify practical ≈ theoretical output.  
7. Plot the input vs. output waveform.

---

## TABULATION (Differential Amplifier)

<img width="1600" height="1166" alt="image" src="https://github.com/user-attachments/assets/5558b2e3-b12b-42f3-8e65-4146d601b27a" />




---
## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-12-05 at 15 33 01_af92bd93](https://github.com/user-attachments/assets/cde4106a-c514-4e0d-8449-3eceefcbdbcc)



## INSTRUMENTATION AMPLIFIER

THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER
<img width="1600" height="1414" alt="image" src="https://github.com/user-attachments/assets/4787410a-93f4-44bf-a89d-94778ddee4ad" />



PROCEDURE:

1.	Select the entire resistor with the same value. Let R be the gain varying resistor with different values of resistance for simplicity let R be a constant value.
2.	Connect the circuit as shown in the circuit diagram.
3.  + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
4.	Give the input V1 and V2 to the non-inverting terminals of first & second op-amp respectively.
5.	By varying the value of RG, measure the output voltage for common mode and differential mode operation. Since RG is selected as constant value, provide different input value of V1 and V2.
6.	Check the theoretical value with the experimental value.
7.	The output voltage is obtained in the Multimeter and the input and output voltage waveforms are plotted in a graph sheet

---

## TABULATION (Instrumentation Amplifier)
<img width="1600" height="1414" alt="image" src="https://github.com/user-attachments/assets/689cb146-7216-434a-b57a-8175d4a4ad64" />



---
## OUT PUT WAVEFORM AND DISCUSSION 
<img width="1185" height="1599" alt="image" src="https://github.com/user-attachments/assets/b346a1f7-bd37-4434-8211-512ee9e338dd" />




---
## RESULT
Thus, the **Inverting**, **Non-Inverting**, **Differential**, and **Instrumentation Amplifiers** were designed and their performance successfully tested using Op-Amp IC 741.

---
