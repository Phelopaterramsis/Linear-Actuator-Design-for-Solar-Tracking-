# 🛠️ Machine Design II – Linear Actuator Design for Solar Tracking  
Design a complete mechanical system for a PV solar-tracking actuator: power screw, geartrain, shafts, bearings, keys, and full gearbox assembly.


## 📘 Project Overview  
This project involves designing a **linear actuator** for a solar tracking mechanism used in PV systems. The actuator converts motor rotation into linear motion to adjust the panel angle throughout the day.

The design includes:

- Power screw with self-locking and full stress analysis  
- Two-stage compound gear train  
- DC motor torque and power estimation  
- Fatigue design for input, intermediate, and output shafts  
- Bearing and retaining ring selection  
- Key design for torque transmission  
- Full gearbox assembly drawing (SolidWorks)

The actuator is required to deliver **1500 N thrust at 4 cm/s** with a **DC motor speed of 1250 rpm**.

---

## ⚙️ Key Technical Work

### **1. Power Screw Design**  
- Selected **D = 10 mm**, **pitch = 2 mm** single-square thread screw  
- Verified the self-locking condition  
- Calculated raising and lowering torques  
- Efficiency ≈ **20.9%**  
- Performed combined axial, bending, torsional, and shear stress analysis  
- Final **Factor of Safety ≈ 2.59 (accepted)**

---

### **2. Compound Gear Train Design**  
- Required gear ratio: **G ≈ 25/24**  
- Chosen gears:  
  - Stage 1: 52-tooth & 50-tooth  
  - Stage 2: 52-tooth & 50-tooth  
- AGMA bending and wear analysis performed for both stages  
- Both stages satisfied FOS requirements

A full gearbox assembly drawing is included in the report.

---

### **3. DC Motor Specs**  
- Required torque: **≈ 2.35 Nm**  
- Operating speed: **1248 rpm**

---

### **4. Shaft Design (Fatigue)**  
Designed three shafts under combined loading using:

- AISI 1020 cold-drawn steel  
- Modified Goodman criteria  
- Fully reversed fatigue loading  

Final selected diameter for all shafts:  
- **12 mm**

---

### **5. Bearing Selection**  
Selected:  
- **SKF 608 Single-Row Deep Groove Ball Bearing**  
- Bore diameter = **8 mm**

---

### **6. Retaining Rings**  
- Gears: **12 mm retaining ring (DSHR-012)**  
- Bearings: selected closest available standard size

---

### **7. Key Design**  
- Square keys selected for 12 mm shafts  
- Material: **G10200 (CD1020)** steel  
- Key lengths calculated for torque on each shaft  
- Designed for **Factor of Safety = 7**

---

## 🧩 Files in This Folder  
- **Machine II Final Report.pdf** – full design calculations and analysis  
- **drawing.pdf** – gearbox engineering drawing  
- **README.md** (this file)

---

## 📎 References  
Calculations and design methodology follow **Shigley’s Mechanical Engineering Design** and SKF bearing catalogs.
