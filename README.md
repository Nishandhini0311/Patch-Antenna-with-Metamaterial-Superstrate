# 📡 Simulation of Patch Antenna with Metamaterial Superstrate

![OpenEMS](https://img.shields.io/badge/OpenEMS-FDTD-blue?style=for-the-badge)
![GNU Octave](https://img.shields.io/badge/GNU-Octave-orange?style=for-the-badge)
![RF](https://img.shields.io/badge/RF-Antenna-green?style=for-the-badge)

---

## 📖 Overview

This project presents the design and simulation of a **Rectangular Microstrip Patch Antenna** operating at **2.45 GHz** using **OpenEMS** and **GNU Octave**. A **Metamaterial Superstrate** is incorporated above the antenna to improve gain, directivity, impedance matching, and radiation characteristics.

---

## 🎯 Objectives

- Design a rectangular patch antenna operating at **2.45 GHz**.
- Improve antenna performance using a metamaterial superstrate.
- Analyze antenna characteristics including:
  - Reflection Coefficient (S11)
  - Feed Impedance
  - Radiation Pattern
  - 3D Far-Field Pattern

---

## ✨ Features

- 📡 Microstrip Patch Antenna Design
- 🛰️ Metamaterial Superstrate
- 📈 Reflection Coefficient (S11)
- 📊 Feed Impedance Analysis
- 🌐 Far Field Radiation Pattern
- 🧩 3D Antenna Visualization
- ⚡ OpenEMS FDTD Simulation

---

## 🛠️ Software Used

- GNU Octave
- OpenEMS
- CSXCAD
- ParaView

---

## 📐 Antenna Parameters

| Parameter | Value |
|------------|-------|
| Frequency | 2.45 GHz |
| Patch Width | 32.86 mm |
| Patch Length | 41.37 mm |
| Feed Resistance | 50 Ω |
| Substrate Thickness | 1.524 mm |
| Metamaterial εr | 12 |

---

## ⚙️ Simulation Workflow

1. Create rectangular patch antenna.
2. Define substrate and ground plane.
3. Add metamaterial superstrate.
4. Configure lumped port excitation.
5. Run OpenEMS simulation.
6. Calculate feed impedance.
7. Calculate S11.
8. Generate radiation pattern.
9. Visualize 3D far-field.

---

## 📂 Repository Structure

```
Patch-Antenna-with-Metamaterial-Superstrate
│
├── Documentation
│      └── EMF_REPORT_FINAL.pdf
├── README.md
└── LICENSE
```

---

## 📊 Simulation Outputs

- Time Domain Voltage
- Feed Impedance
- Reflection Coefficient (S11)
- Far Field Radiation Pattern
- 3D Radiation Pattern

---

## 📈 Results

- Operating Frequency: **2.45 GHz**
- Return Loss (S11): **Below −10 dB**
- Feed Impedance: **Approximately 50 Ω**
- Improved Directivity using Metamaterial Superstrate
- Enhanced Radiation Characteristics

---

## 🚀 Future Improvements

- HFSS implementation
- Antenna fabrication
- Measured VSWR comparison
- Higher gain optimization

---

## 👩‍💻 Author

**Nishandhini S**
