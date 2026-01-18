# 2.4 GHz Antenna Design — CST Simulation & Real-World Validation

This repository contains the complete design, simulation, and physical testing of a **2.4 GHz dipole antenna**, developed using **CST Studio Suite** and validated through experimental measurements.

The goal of the project was to design an efficient antenna for the 2.4 GHz ISM band, simulate its electromagnetic behavior, fabricate a real prototype, and compare simulated vs measured results.

---

## 📡 Overview

The project includes:

- **Theoretical analysis** of a 2.4 GHz dipole antenna  
- **CST electromagnetic simulation** (geometry, ports, mesh, S-parameters)  
- **Fabrication and testing** of the physical prototype  
- **Comparison between CST predictions and real measurements**

This repository showcases the complete engineering workflow from concept to validation.

---
## Repository Structure

### CST Project
- [Dipolo2,4.cst](cst/Dipolo2,4.cst) → CST Studio Suite project file

### Documentation
- [Relazione_Dipolo_2.4GHz.pdf](docs/Relazione_Dipolo_2.4GHz.pdf) → Theory + CST simulation report
- [Report_Attività_Sperimentale_Dipolo_2.4GHz.pdf](docs/Report_Attività_Sperimentale_Dipolo_2.4GHz.pdf) → Physical prototype test report

---

## 🧠 Documentation

### **Relazione_Dipolo_2.4GHz.pdf**
Includes:
- Antenna theory  
- Dipole design equations  
- CST model setup  
- Ports, mesh, boundaries  
- S11 and radiation patterns  

### **Report_Attività_Sperimentale.pdf**
Includes:
- Prototype fabrication  
- Measurement setup  
- VNA results  
- Comparison with simulation  

---

## 🖥 CST Simulation

The CST project file (`Dipolo2_4.cst`) contains:

- 3D antenna geometry  
- Excitation / discrete ports  
- Meshing and solver settings  
- Far-field and S11 analysis  

---

## 📊 Key Results

- S11 curve centered around **2.4 GHz**  
- Good agreement between simulation and real measurement  
- Stable radiation pattern and impedance matching in ISM band  

---

## 🛠 Tools Used

- **CST Studio Suite 2023**
- **Vector Network Analyzer (VNA)**
- **Copper wire / PCB prototype**
- **Mathematical modeling**
- **RF measurement techniques**

---

## 📜 License

This project is available for educational and non-commercial use.

