
# CMOS Schmitt Trigger using Cadence Virtuoso (45nm)

This repository contains the complete design and simulation of a CMOS Schmitt Trigger using the GPDK045 (45nm) library in Cadence Virtuoso.

---

## 🧠 Project Summary

A Schmitt Trigger is a comparator circuit with hysteresis that provides noise immunity and clean digital transitions. This project implements a custom IC design flow from schematic to verified layout.

---

## 🖊️ Design Overview

- **Technology**: 45nm (GPDK045)
- **Tool**: Cadence Virtuoso
- **Design**: Core inverter with positive feedback using PMOS/NMOS
- **Simulation**: Displays digital-level output with input sine waveform — showing clear hysteresis behavior
- **Layout**: Custom layout created and verified
- **LVS**: Layout vs Schematic check passed ✅

---

## 📁 Project Structure

### 🔧 Schematic (Virtuoso)
The schematic consists of a CMOS inverter with positive feedback to realize hysteresis.

![schematics](schematic.png)

---

### ⚡ Simulation Result
Simulation confirms proper hysteresis behavior. Input is a sine wave, and output shows clean digital transitions.

![simulation](simulation.png)

---

### 🧱 Layout View
Custom layout was designed manually and verified using DRC and LVS tools. LVS passed successfully.

![Layout](layout.png)

---

## 🛠️ Tools Used

- Cadence Virtuoso
- GPDK045 PDK
- Spectre Simulator

---

## ✅ Achievements

- Complete custom IC design flow
- Clear digital transitions and hysteresis behavior
- LVS matched with schematic

---

## 📌 Tags

`#VLSI` `#CadenceVirtuoso` `#SchmittTrigger` `#AnalogDesign` `#CMOS` `#GPDK045` `#LVS`

---

## 👤 Author

**Sarthak Aher**  
*Feel free to connect on [LinkedIn](https://www.linkedin.com/in/sarthak-aher-9a54a1258/)*

