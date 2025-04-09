# Analog Temperature Sensor (ASAP7 CTAT, Monte Carlo, CMOS Inverter)

> This project demonstrates the development and statistical validation of a silicon-based analog temperature sensor using CTAT and PTAT voltage generation. Designed in ASAP7, simulated using HSPICE, and analyzed with Python scripts.

---

### 📌 **Project Overview**
- **Objective:** Design and verify a temperature-dependent analog voltage generator using CTAT and PTAT behavior to monitor silicon temperature changes.
- **Methodology:** Built individual CTAT and PTAT generators using diode-connected MOSFETs and current mirrors. Simulated 100+ Monte Carlo cases at each temperature using HSPICE. Final output was processed using a subtractor stage.

---

### 💡 **Key Features**
- CTAT and PTAT stage integration  
- Full Monte Carlo sweep across temperatures (-25°C to 125°C)  
- Statistical evaluation of VOUT vs Temp  
- ASAP7 process for nanometer-scale simulation  

---

### 🧰 **Skills Used**
Analog Circuit Design, Monte Carlo Simulation, Temperature Sensor Modeling, Python Automation

---

### 🧪 **Technologies & Tools**
ASAP7 PDK, HSPICE, Python

---

### 🔍 **Key Findings**
Generated reliable analog voltage with predictable temp response. Captured VOUT variation due to process changes.

---

### 🎓 **What I Learned**
Silicon behavior with temperature, process variability, statistical data analysis of analog outputs.

---

### 🚀 **Future Work**
Create layout and run post-layout simulation. Calibrate to real temperature sensor datasets.

---

### 📂 **Files Attached**
ctat_generator.sp, ptat_generator.sp, sensor_combined.sp, python_parser.py, vout_vs_temp_plots.png
