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
| 6 | Resistors | 1.5K, 15K | 2 |
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

<img width="624" height="269" alt="image" src="https://github.com/user-attachments/assets/635c9837-d5f5-4d6f-acc9-8a47a4368230" />

CIRCUIT DIAGRAM: INVERTING AMPLIFIER:
![WhatsApp Image 2025-11-30 at 13 36 57_684d1516](https://github.com/user-attachments/assets/e24dc597-1d8f-4792-ab83-2597e3555e46)



MODEL GRAPH 

<img width="543" height="357" alt="image" src="https://github.com/user-attachments/assets/1836d120-768e-454f-bfe4-682ce70ea7a1" />



DESIGN:

Inverting amplifier:

A = -Rf/R1
Take  A = 10
Rf =10 R1
Choose R1 = 1.5kΩ, Rf=15kΩ

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

![WhatsApp Image 2025-11-30 at 13 59 19_722d6a9f](https://github.com/user-attachments/assets/3c80904e-3e27-4b5b-8cb9-2f3f8295a8cc)




## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-30 at 14 09 58_3e0307ee](https://github.com/user-attachments/assets/502348d0-a9fe-4f95-be82-69990c4e5a84)


---
### **Non-Inverting Amplifier**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1 RF = 15kohms R1 = 2kohms


---

## CIRCUIT DIAGRAM
![WhatsApp Image 2025-11-30 at 14 03 15_3a28eb8a](https://github.com/user-attachments/assets/22bc9cda-f7bc-4f17-8170-b15d5b19c1fe)




---

## MODEL GRAPH

<img width="456" height="340" alt="image" src="https://github.com/user-attachments/assets/00c7aaec-b4d8-414e-afa3-e985eb3dd902" />

---
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
![WhatsApp Image 2025-11-30 at 14 05 45_51c4ce4b](https://github.com/user-attachments/assets/dbea9f8b-5a0a-4191-848c-5e5cccf044f8)



---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-30 at 14 08 10_6ebb465a](https://github.com/user-attachments/assets/19ef5057-cc17-4914-ab8a-d30cd4055beb)
![WhatsApp Image 2025-11-30 at 14 08 32_9a6564f0](https://github.com/user-attachments/assets/0518c06f-4088-4f0c-a548-5064c522f7ee)


---
## DIFFERENTIAL AMPLIFIER

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1
## CIRCUIT DIAGRAM
![WhatsApp Image 2025-11-30 at 14 17 22_43382a52](https://github.com/user-attachments/assets/63a408b5-2771-4327-9da4-9d918007dbd6)



## MODEL GRAPH
<img width="678" height="334" alt="image" src="https://github.com/user-attachments/assets/6aa1b9dd-b112-4be1-a37a-d5ee19607b1d" />

---

## DESIGN


### **Differential Amplifier**

AV = Vo/{V1 - V2} = -Rf/R1


Take  A = 10 
⇒  Rf = 15R1   
Choose  R1 = 1.5kOhm, Rf = 15kOhm

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

![WhatsApp Image 2025-11-30 at 14 24 26_3346f341](https://github.com/user-attachments/assets/46617a97-e022-45c6-ab3f-9ad83f4d3cf1)


---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-30 at 15 11 24_705714c9](https://github.com/user-attachments/assets/bbaf19e0-c334-4bc6-8914-c81b73d74250)


---
## INSTRUMENTATION AMPLIFIER

THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER
![WhatsApp Image 2025-11-30 at 15 18 58_76cb9498](https://github.com/user-attachments/assets/ed719538-1513-4ec1-9ca6-f03f2287a1e1)



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
![WhatsApp Image 2025-11-30 at 15 22 59_c022a910](https://github.com/user-attachments/assets/d971b624-5ba5-4ec3-b053-b7e0efcfd5b1)


---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-30 at 15 25 49_716fa8da](https://github.com/user-attachments/assets/b07c9386-7553-4267-9799-b437c71a7059)


---
## RESULT
Thus, the **Inverting**, **Non-Inverting**, **Differential**, and **Instrumentation Amplifiers** were designed and their performance successfully tested using Op-Amp IC 741.

---
