# DSB-SC-AM-MODULATOR-AND-DEMODULATOR-USING-SCILAB-T1-M4-ODD
# DSB-SC-AM MODULATOR AND DEMODULATOR

## AIM

To write a program to perform DSBSC modulation and demodulation using SCI LAB and study its spectral characteristics.

---

## EQUIPMENTS REQUIRED

* Computer with i3 Processor
* SCI LAB

> **Note:** Keep all the switch faults in off position.

---

## ALGORITHM

### 1. Define Parameters:

* **Fs:** Sampling frequency.
* **T:** Duration of the signal.
* **Fc:** Carrier frequency.
* **Fm:** Frequency of the message signal.
* **Amplitude:** Maximum amplitude of the message signal.

### 2. Generate Signals:

* **Message Signal:** A sinusoidal signal that will be modulated.
* **Carrier Signal:** A high-frequency sinusoidal signal used for modulation.

### 3. DSBSC Modulation:

* **Modulated Signal:** Multiply the message signal by the carrier signal to produce the DSBSC signal.

### 4. DSBSC Demodulation:

* **Multiplication:** Multiply the modulated signal by the carrier signal to get the product of the message signal with itself (i.e., the original message signal plus high-frequency components).
* **Low-pass Filtering:** Apply a Butterworth low-pass filter to remove the high-frequency components and recover the original message signal.

### 5. Visualization:

Plot the message signal, carrier signal, DSBSC modulated signal, and the recovered signal after demodulation.

---

## PROCEDURE

* Refer Algorithms and write code for the experiment.
* Open SCILAB in System.
* Type your code in New Editor.
* Save the file.
* Execute the code.
* If any Error, correct it in code and execute again.
* Verify the generated waveform using Tabulation and Model Waveform.
---

## TABULATION
<img width="899" height="1599" alt="WhatsApp Image 2026-09-24 at 3 32 03 PM" src="https://github.com/user-attachments/assets/d63a5306-77a4-4605-8842-436142d3b6e4" />

## PROGRAM
<img width="899" height="1599" alt="WhatsApp Image 2026-09-24 at 3 32 12 PM" src="https://github.com/user-attachments/assets/5993dc1d-6d84-436e-9d7d-e2670d1ee691" />

## GRAPH
<img width="899" height="1599" alt="WhatsApp Image 2026-09-24 at 3 32 19 PM" src="https://github.com/user-attachments/assets/3b00937a-4111-47fa-9aa1-86277d0901bf" />

## RESULT
<img width="899" height="1599" alt="WhatsApp Image 2026-09-24 at 3 32 26 PM" src="https://github.com/user-attachments/assets/569ec2c8-ea0a-4300-9ffa-1fff13d2cd7e" />

## MARK ALLOCATION
<img width="899" height="1599" alt="WhatsApp Image 2026-09-24 at 3 32 32 PM" src="https://github.com/user-attachments/assets/22635156-75bd-42be-bf27-b28a33baf42e" />


---
