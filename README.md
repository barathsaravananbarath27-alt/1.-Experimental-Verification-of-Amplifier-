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

<img width="315" height="117" alt="image" src="https://github.com/user-attachments/assets/c83a933a-99bb-4696-8f66-2311bafa9d29" />

<img width="537" height="307" alt="image" src="https://github.com/user-attachments/assets/d0584550-a25e-4d4e-bb10-9f8c1e0fde9f" />
<img width="496" height="528" alt="image" src="https://github.com/user-attachments/assets/e0f5586f-96af-45ef-82e1-271790066032" />


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

<img width="416" height="251" alt="image" src="https://github.com/user-attachments/assets/c8af36e2-fcf9-4cd5-8067-1e073fc96a77" />

<img width="416" height="244" alt="image" src="https://github.com/user-attachments/assets/27aa0b76-5b81-47ea-a8bd-a995933a5398" />
<img width="471" height="484" alt="image" src="https://github.com/user-attachments/assets/838bd50e-86d8-4562-82fb-485805a990f4" />

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

<img width="491" height="161" alt="image" src="https://github.com/user-attachments/assets/ad413d9d-db43-4a9e-9ac6-7d168b921010" />
<img width="537" height="375" alt="image" src="https://github.com/user-attachments/assets/938d9a32-6726-4b5c-8ac2-77b827caf219" />
<img width="577" height="508" alt="image" src="https://github.com/user-attachments/assets/30ff3250-8db9-4f88-b425-3409b860f1f6" />

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

<img width="536" height="296" alt="image" src="https://github.com/user-attachments/assets/8b69599b-0d8f-403c-96be-355fd867f059" />



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
<img width="539" height="357" alt="image" src="https://github.com/user-attachments/assets/30f67931-5981-4b51-adbd-a659dfe2e05c" />


<img width="493" height="702" alt="image" src="https://github.com/user-attachments/assets/7a4b6587-1fd9-4155-93d9-257fb306bd1e" />


---
## OUT PUT WAVEFORM AND DISCUSSION 
<img width="592" height="545" alt="image" src="https://github.com/user-attachments/assets/f18bd2ac-d66f-4352-a13d-2db6ec4b4950" />



---
## RESULT
Thus, the **Inverting**, **Non-Inverting**, **Differential**, and **Instrumentation Amplifiers** were designed and their performance successfully tested using Op-Amp IC 741.

---
