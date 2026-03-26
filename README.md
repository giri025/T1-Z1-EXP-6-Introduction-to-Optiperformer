## Giri R (212223060068)
## Exp 6 Simulation of Optical Communication System
## Introduction to OptiPerformer 
## Aim
To analyze and evaluate the performance of an optical communication system by studying the relationship between fiber length, received power, Q factor and Bit Error Rate(BER) and to observe changes in the eye diagram with increasing fiber length using optiperformer.

---

## Theory

Optiwave introduces **OptiPerformer**, a free photonic design automation tool that harnesses the full power of OptiSystem and creates specific dynamic design scenarios for student use.

The first simulation file (`Introduction_OptiPerformer.osp`) models a basic fiber optic system consisting of:
- A transmitter
- A fiber
- A receiver

The system includes:
- An optical power meter at the receiver input (fiber output)
- A Bit Error Rate (BER) analyzer

---

## Procedure

1. Download and install OptiPerformer from [optiwave.com](https://optiwave.com).  
2. Copy the `Introduction_OptiPerformer.osp` file to your PC.  
3. Launch OptiPerformer.  
4. Use the **File** menu or **Open File** button to open the fiber optic system file.  
5. Study the layout:
   - **Transmitter** section includes:
     - Binary source (PRBS generator)
     - Electrical pulse generator
     - Laser diode
     - External modulator  
   - **Receiver** section includes:
     - Photodiode
     - Low-pass filter
     - Decision circuit with BER analyzer  
6. Run the simulation using the **Start** button.  
   - Progress will be displayed.
   - Message “Calculation Finished!” appears upon completion.  
7. Double-click the **optical power meter** and **BER analyzer** windows.  
   - Check “Show Eye Diagram” in the BER window.  
   - Optical power meter shows power in watts and dBm.  
   - BER window displays:
     - Eye diagram
     - Max Q Factor
     - Min BER  
8. The simulation runs 5 iterations with fiber length varying from 50 to 150 km.  
   - Use forward/reverse buttons to step through iterations.  
   - Observe changes in received power, BER, Q factor, and eye diagram.

---

## Observation

1. Cover sheet (as per attached example).  
2. Tabulation of received power, Q factor, and BER for 5 fiber lengths.  
3. Plot of received power, Q factor, and BER vs. fiber length.  
4. Description of eye diagram changes with increasing fiber length.

---

## Tabulation

**Transmission Analysis Across Fiber Lengths**

<img width="1273" height="1412" alt="image" src="https://github.com/user-attachments/assets/16a3e08b-3e5b-4c33-8aba-ba6d20f09fe2" />

## MODEL GRAPH
<img width="1089" height="562" alt="image" src="https://github.com/user-attachments/assets/0165a165-d39a-409c-a9f3-6e22656f1f19" />

---

## GRAPH 
<img width="940" height="335" alt="image" src="https://github.com/user-attachments/assets/f6ecb75a-be76-41e7-9916-b63737e61585" />
<img width="940" height="326" alt="image" src="https://github.com/user-attachments/assets/e14c8215-bb41-44be-9ef4-4206ee2e3811" />
<img width="1728" height="677" alt="image" src="https://github.com/user-attachments/assets/805ede93-a37f-4156-8329-f55fa30dde5b" />
<img width="1723" height="600" alt="image" src="https://github.com/user-attachments/assets/adbea82c-064c-413b-bd44-5bb81cff1141" />
<img width="1734" height="601" alt="image" src="https://github.com/user-attachments/assets/65fa200d-9bb7-4a01-b69b-17c5a191d64a" />


---

## RESULT
Thus,The Introduction-to-Optiperformer is calculated and output is verified.
