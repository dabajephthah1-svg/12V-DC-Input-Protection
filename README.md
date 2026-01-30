# 12V-DC-Input-Protection
# 12 V DC Input Protection Circuit

## Description
This project demonstrates a simple 12 V DC input protection circuit using a Schottky diode to protect against reverse polarity connection.

## Selected Diode
**1N5819 Schottky Diode**

## Justification

**Voltage Rating:**  
The 1N5819 has a maximum reverse voltage of 40 V, which safely exceeds the 12 V input requirement.

**Current Rating:**  
The diode supports up to 1 A average forward current, suitable for low-power DC input circuits.

**Forward Voltage Drop:**  
The low forward voltage drop (~0.3–0.4 V) minimizes power loss compared to standard silicon diodes.

**Cost & Availability:**  
The diode is inexpensive, widely available, and commonly used in power protection applications.

## Simulation
The circuit was simulated in LTspice using an operating point (.op) analysis.  
Correct polarity allows current flow, while reverse polarity blocks current, confirming protection functionality.

## Files Included
- `schematic.asc` – LTspice schematic
- `circuit.png` – Circuit diagram
- `simulation.png` – LTspice simulation result
