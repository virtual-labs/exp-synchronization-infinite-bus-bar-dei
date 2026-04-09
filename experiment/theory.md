# Experiment 1: Synchronization of Alternators

This project is part of the **Virtual Power Laboratory at D.E.I.**, focusing on the theoretical and practical requirements for synchronizing an incoming alternator with a bus bar or another alternator.

---

## 📋 Pre-Synchronization Conditions

Before an alternator can be safely connected to the system, the following three conditions **must** be satisfied:

1.  **Equality of Voltage**: The terminal voltage of the incoming alternator must match the bus bar voltage.
2.  **Phase Sequence**: The phase sequence (order of rotation) of both systems must be identical.
3.  **Equality of Frequency**: The frequency of the incoming machine must match the system frequency.

> [!NOTE]
> Voltage is verified using a voltmeter, while phase sequence and frequency are checked using synchronizing methods.

---

## 🛠 Synchronizing Methods

There are two primary methods discussed in this lab:

### A. Incandescent Lamp Method
This method uses three lamps ($L_1, L_2$, and $L_3$) connected between the incoming machine (G2) and the running bus bar (G1).

* **Dark Lamp Method**: Synchronization is performed at the middle of the "dark period" when the voltage difference is zero.
* **Flickering**: If frequencies differ, the lamps flicker at a rate equal to the frequency difference (beats).
* **Siemens & Halske Connection**: By transposing two lamps (e.g., $L_2$ between $B_1$-$C_2$ and $L_3$ between $C_1$-$B_2$), the lamps glow in a cyclic succession. This indicates if the machine is **FAST** or **SLOW**.

#### Drawbacks:
* **Accuracy**: Lamps go dark at about 1/3 of the rated voltage, leading to potential phase errors.
* **Quantitative Data**: It cannot specify exactly how much the frequency differs.
* **High Voltage**: Not directly applicable to HV alternators without step-down transformers.

### B. Synchroscope Method
A synchroscope is a dedicated instrument providing a more precise indication for synchronization.

* **The Pointer**: A rotating pointer indicates the phase difference.
* **Direction of Rotation**: 
    * **Clockwise**: Incoming machine is running too **FAST**.
    * **Anti-clockwise**: Incoming machine is running too **SLOW**.
* **Synchronization Point**: The switch is closed when the pointer stays stationary at the 12 o'clock (vertical) position.

---

## 🖼 Figures and Visuals

| Figure | Description |
| :--- | :--- |
| **Fig. 1** | Synchronization using the three-lamp method circuit diagram. |
| **Fig. 2** | Waveforms of two systems operating at different frequencies. |
| **Fig. 3** | Synchroscope dial and connection. |

---

## 🚀 Navigation

* [Objective](./objective1.html)
* [Equipments](./equip1.html)
* [Theory](./theory1.html)
* [Connection Diagram](./connection1.html)
* [Procedure](./proce1.html)
* [Simulation](./sim1.html)
* [Quiz](./quiz1.html)

---
© Virtual Labs - Dayalbagh Educational Institute
