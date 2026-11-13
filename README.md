## EXPERIMENT NO. 1 – VERIFICATION OF KIRCHHOFF'S LAWS

| **Name:** | **Alvina Inayath Sha** | **Reg. No.:** | **26013515** |
|---|---|---|---|
| **Date:** | **12-11-2026** | **Batch / Section:** | **26ODJ084**  |

---

## AIM

a. To verify Kirchhoff's Voltage Law (KVL) for the given circuit.

b. To verify Kirchhoff's Current Law (KCL) for the given circuit.

## APPARATUS REQUIRED

| S. No. | Component | Range / Rating | Quantity |
|:---:|:---:|:---:|:---:|
| 1 | Resistor | 1 kΩ | 3 |
| 2 | DC Voltmeter | 0–30 V | 3 |
| 3 | DC Ammeter | 0–0.2 A | 3 |
| 4 | Breadboard | — | 1 |
| 5 | Regulated Power Supply (RPS) | 0–30 V | 1 |
| 6 | Connecting wires | As required | As required |
| 7 | Simulation software | Proteus Design Suite | 1 |

## THEORY

**Kirchhoff's Voltage Law (KVL):** The algebraic sum of all voltage rises and voltage drops around any closed loop in an electrical circuit is zero.

**Kirchhoff's Current Law (KCL):** The algebraic sum of currents at any node is zero. In other words, the total current entering a node is equal to the total current leaving the node.

## PROCEDURE

### A. Verification of KVL

1. Connect the circuit as shown in the KVL circuit diagram.
2. Ensure that the RPS output is set to zero volts before switching it on.
3. Check that all meters are correctly connected and set to their zero positions.
4. Switch on the RPS and gradually set the required input voltage within the specified range.
5. Measure and record the voltage across each resistor using the voltmeters.
6. Repeat the measurements for different input-voltage values and tabulate the readings.

### B. Verification of KCL

7. Connect the circuit as shown in the KCL circuit diagram.
8. Ensure that the RPS output is set to zero volts before switching it on.
9. Check that all meters are correctly connected and set to their zero positions.
10. Switch on the RPS and gradually set the required input voltage within the specified range.
11. Measure and record the current in each branch using the ammeters.
12. Repeat the measurements for different input-voltage values and tabulate the readings.

## CIRCUIT DIAGRAMS

### A. KVL circuit diagram

<img width="842" height="588" alt="Screenshot 2026-10-21 105222" src="https://github.com/user-attachments/assets/12a82d9c-a1cf-4d1d-ab12-f82c06930c12" />


**Figure 1:** KVL verification circuit

### B. KCL circuit diagram

<img width="1167" height="493" alt="Screenshot 2026-10-21 105627" src="https://github.com/user-attachments/assets/bfa35d08-b577-488e-86d0-5bf12658ee05" />


**Figure 2:** KCL verification circuit

## SIMULATION USING PROTEUS

Build the KVL and KCL circuits in Proteus using the same resistor values and supply voltage as the hardware circuit. Place DC voltmeters and DC ammeters from the Virtual Instruments mode, run the simulation, and paste a screenshot showing the meter readings for each circuit.

### A. KVL simulation

<img width="877" height="595" alt="Screenshot 2026-10-19 235517" src="https://github.com/user-attachments/assets/70f3e210-3ef8-432b-93c2-f60aa3a32c87" />


**Figure 3:** Proteus simulation of KVL circuit

### B. KCL simulation

<img width="1170" height="497" alt="Screenshot 2026-10-21 105609" src="https://github.com/user-attachments/assets/512b457f-137d-4abe-bc1d-a0b2f73e6b98" />


**Figure 4:** Proteus simulation of KCL circuit

## OBSERVATION AND TABULATION

### A. KVL – Voltage measurements

| S. No. | Supply voltage Vs (V) | VR1 (30 ohm) | VR2 (50 ohm) | VR3 (100 ohm) |
|:---:|:---:|:---:|:---:|:---:|
| 1 (Theoretical) | 100 | 16.5 | 27.5 | 55  |
| 2 (Practical)   | 100 | 16.7 | 27.8 | 55.6 | 

### B. KCL – Current measurements

| S. No. | I1 (30 ohm) | I2 (50 ohm) | I3 (100 ohm) | Node voltage Vn (V) |
|:---:|:---:|:---:|:---:|:---:|
| 1 (Theoretical) | 1.579 | 1.052 | 0.526 | 52.63 |
| 2 (Practical)   | 1.58 | 1.05 | 0.53 | 52.6 | 

## CALCULATIONS

### A. KVL

According to KVL, **ΣV = 0**.
Therefore, **Vs - V1 - V2 - V3 = 0**.

Substitute the observed values and verify that the algebraic sum of the voltages around the closed loop is equal to zero.

<img width="1052" height="1600" alt="image" src="https://github.com/user-attachments/assets/38da93fa-3224-4fc0-892e-cc8c1b792cc6" />


**Figure 5:** KVL calculation

### B. KCL

According to KCL, **ΣI entering = ΣI exiting**.
Therefore, **I1 = I2 + I3**.

Substitute the observed values and verify that the total current entering the node is equal to the sum of the currents leaving the node.

<img width="1068" height="1600" alt="image" src="https://github.com/user-attachments/assets/25e2207f-525a-47d7-aca0-093f0a653189" />
<img width="1600" height="1274" alt="image" src="https://github.com/user-attachments/assets/375bb7ae-2f54-4d17-814e-793bb755c085" />


**Figure 6:** KCL calculation

## RESULT

Thus, Kirchhoff's Voltage Law (KVL) and Kirchhoff's Current Law (KCL) were verified experimentally and through Proteus simulation for the given circuits.
