# 🔌 CMOS Logic Design & Analysis

This repository contains simulations and analysis of basic CMOS logic gates including **Inverter** and **NAND gate**, along with their **DC and Transient analysis**.

---

## 📁 Contents

- CMOS Inverter
- CMOS NAND Gate
- DC Analysis
- Transient Analysis

---

## ⚡ CMOS Inverter

### 🔹 Circuit Diagram
<img src="https://github.com/user-attachments/assets/9c893b69-cf4e-493a-b062-57b492a0eb37" width="500"/>

### 🔹 Simulation Output
<img src="https://github.com/user-attachments/assets/7d7fb9f4-2399-4cae-8787-e9f5fe344516" width="500"/>

### 🔹 Description
A CMOS inverter is the most fundamental logic gate built using:
- PMOS transistor (pull-up network)
- NMOS transistor (pull-down network)

**Working:**
- Input LOW → Output HIGH  
- Input HIGH → Output LOW  

---

## 🔗 CMOS NAND Gate

### 🔹 Circuit Diagram
<img src="https://github.com/user-attachments/assets/2194b644-fb52-43df-84bb-1e5d64c93a1c" width="500"/>

### 🔹 Simulation Output
<img src="https://github.com/user-attachments/assets/d234bf4e-6ecd-4c0c-81c0-cc30649d5135" width="500"/>

### 🔹 Description
The CMOS NAND gate consists of:
- Two PMOS transistors in parallel
- Two NMOS transistors in series

**Truth Table:**

| A | B | Output |
|---|---|--------|
| 0 | 0 | 1      |
| 0 | 1 | 1      |
| 1 | 0 | 1      |
| 1 | 1 | 0      |

---

## 📊 DC & Transient Analysis

### 🔹 DC Analysis

<img src="https://github.com/user-attachments/assets/a9a31e53-9f28-4fe9-b0b3-58201428c838" width="600"/>
<br/>
<img src="https://github.com/user-attachments/assets/7da9ffc0-838d-4805-b1b7-4b53ded67f00" width="600"/>

---

### 🔹 NMOS Characteristics

<img src="https://github.com/user-attachments/assets/bf9bb652-9eeb-422a-b462-6514a73d7bee" width="600"/>

---

### 🔹 Transient Analysis

<img src="https://github.com/user-attachments/assets/179e3b72-0996-4c5c-8b31-daa1dcc1a09b" width="600"/>
<br/>
<img src="https://github.com/user-attachments/assets/ad12bfef-b938-4997-96af-9e226cb2df50" width="600"/>
<br/>
<img src="https://github.com/user-attachments/assets/f7a31682-014c-4ace-a325-55625d169c03" width="600"/>
<br/>
<img src="https://github.com/user-attachments/assets/fd44b68c-f6a8-4284-bdbd-4db24566a468" width="600"/>
<br/>
<img src="https://github.com/user-attachments/assets/84097baa-6e26-4d2f-856d-8c5389bb6e53" width="600"/>
<br/>
<img src="https://github.com/user-attachments/assets/afac976e-20f9-42bf-84c2-b4689d4b02d9" width="600"/>
<br/>
<img src="https://github.com/user-attachments/assets/bc13ac7d-9260-4d40-9215-0f842ff81e8b" width="600"/>

---

## 🧠 Key Learnings

- CMOS logic provides low power consumption
- Inverter is the basic building block of digital circuits
- NAND gate is a universal gate
- DC analysis helps understand operating regions
- Transient analysis shows switching speed and delay

---

## 🚀 Future Improvements

- Add NOR gate analysis  
- Include layout design (VLSI)  
- Power-delay product comparison  
- Simulation using different technology nodes  
