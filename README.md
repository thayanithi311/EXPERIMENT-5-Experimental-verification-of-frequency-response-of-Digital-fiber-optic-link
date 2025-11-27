
# Exp 5 Experimental verification of frequency response of Digital fiber optic link
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

<img width="904" height="535" alt="image" src="https://github.com/user-attachments/assets/f3f2413c-0b52-4057-8475-5ebf00cfb30e" />

---


## CONNECTION DIAGRAM  
**Setting up a Digital Link**

*(Insert connection diagram here)*

---

## TABULATION  
**Transmission through Digital Link**

 (Vi = 12 V)

| Frequency (Hz) | Output Signal Amplitude (Vo) | Gain (Vo / Vi) | Gain (dB) |
| -------------- | ---------------------------- | -------------- | --------- |
| 800 Hz         | 2.5 V                        | 0.5            | 13.1      |
| 1 kHz          | 32 V                         | 6.4            | 16.12     |
| 2 kHz          | 34 V                         | 6.8            | 16.6      |
| 5 kHz          | 36 V                         | 7.2            | 17.14     |
| 10 kHz         | 37 V                         | 7.4            | 17.38     |
| 20 kHz         | 37 V                         | 7.4            | 17.38     |
| 50 kHz         | 27 V                         | 5.4            | 17.38     |
| 100 kHz        | 27 V                         | 5.4            | 14.64     |
| 250 kHz        | 12.7 V                       | 2.521          | 8.09      |


---

## MODEL GRAPH

<img width="1236" height="693" alt="image" src="https://github.com/user-attachments/assets/69678b68-ac0a-41f4-b992-34f5b64d02a2" />
<img width="1243" height="826" alt="image" src="https://github.com/user-attachments/assets/730e7cc4-f560-4f6a-a9f6-1b98c34bea69" />

---

## RESULT

Thus the optic fibre digital link is studied succesfully.
