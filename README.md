<div align="center">

# 🏠 Room Occupancy Based Automatic Light & Fan Control  
### Digital Logic Design (DLD) – Semester 3 Project  

![DLD](https://img.shields.io/badge/Digital%20Logic%20Design-Semester%203-blue)
![Proteus](https://img.shields.io/badge/Simulation-Proteus-green)
![Status](https://img.shields.io/badge/Project-Completed-success)

![proteus](https://github.com/user-attachments/assets/0e98eec2-91b3-4be1-bfef-ebfac353492d)


</div>

---

## 📖 About The Project

This project presents an **intelligent room automation system** designed using **core Digital Logic Design concepts**.  
The system automatically controls **lights and fan** based on **real-time room occupancy**, ensuring **energy efficiency** and **hands-free operation**.

The design is purely **logic-based**, combining **sequential logic (counters)** and **combinational logic (gates)** to achieve a real-world automation solution.

---

## ✨ Key Highlights

- 🔢 Real-time **occupancy counting**
- 💡 Automatic **Light & Fan control**
- 🧠 Pure **Digital Logic Design**
- 🔄 **Entry & Exit** detection
- 🛑 **Manual Override** support
- 📟 **7-Segment Display** count visualization
- 🔌 Relay-based load switching
- 🧪 Fully tested in **Proteus**

---

## 🧠 Concepts Implemented

| Category | Concepts |
|--------|---------|
| Sequential Logic | Up/Down Counter (CD40192) |
| Combinational Logic | AND / OR Gates |
| Display Logic | 74LS47 BCD Decoder |
| Power Control | Relay + Transistor |
| Automation | Occupancy-Based Switching |

---

## 🏗️ System Block Diagram

Entry Switch ─┐

├──► Up/Down Counter ───► Logic Gates ───► Relay ───► Load

Exit Switch ─┘

Manual Override ───────────────────────────────▲



---

## ⚙️ Working Principle

1. System starts with **occupancy = 0**
2. Entry button → **counter increments**
3. Exit button → **counter decrements**
4. If **count > 0**
   - Lights & Fan turn **ON**
5. If **count = 0**
   - All appliances turn **OFF**
6. Manual override can force ON/OFF at any time

---

## 🔢 Boolean Logic

Output = A + B + C + D

If Output = 1 → Appliances ON

If Output = 0 → Appliances OFF


---

## 🔧 Hardware Components

- CD40192 – Up/Down Counter  
- 74LS47 – BCD to 7-Segment Decoder  
- 7-Segment Display (Common Anode)  
- Push Buttons (Entry / Exit)  
- Manual Override Switch  
- Relay Module  
- NPN Transistor  
- LEDs (Indicators)  
- DC Motor (Fan Simulation)  
- Resistors (10kΩ, 220Ω)  
- 7805 Voltage Regulator  
- 12V Power Supply  

---

## 💻 Software Tools

- **Proteus Design Suite** – Circuit Design & Simulation

---

## 🧪 Testing & Validation

✔ Accurate counting for multiple entries/exits  
✔ Correct ON/OFF switching  
✔ Manual override priority verified  
✔ Relay operation tested  
✔ Stable operation under continuous use  

---

## 📸 Simulation Results

### 🔴 Zero Occupancy (Power OFF)
![powerOff](https://github.com/user-attachments/assets/4d3679f1-ef07-402c-9b56-cca571a2dbc8)


### 🟢 Occupancy 1–9 (Power ON)
![poweOn](https://github.com/user-attachments/assets/fb252a79-980f-42a0-87cb-5116e2a827e1)


---

## 🎥 Project Demo Video

▶ **Full Working Demonstration:**  
👉 https://github.com/sohaibAkhlaq/room_occupancy/video-link.mp4

---

## 📂 Repository Structure

📦 Room-Occupancy-DLD


│ └── room_occupancy.pdsprj


│ └── DLD_Report_Final.pdf


│ ├── zero.png

│ └── nonzero.png

| └── video-link

└── README.md


---

## 📘 Project Report

📄 **Complete Project Documentation:**  
👉 [DLD Final Report](Dld_report_final.pdf)

---

## 🚀 Future Improvements

- IR Sensors instead of push buttons  
- Multi-room expansion  
- Microcontroller integration  
- IoT-based monitoring  

---

## 👨‍💻 Team Members

- **Sohaib Akhlaq** — 24i-3108  
- **M. Hasaam** — 24i-3107  
- **Shaiman** — 24i-3074  

---

## 👩‍🏫 Instructor

**Mrs. Hifza Umer**  
FAST – National University of Computer & Emerging Sciences  
Islamabad  

---

## ⭐ Support

If you found this project helpful or impressive,  
**please give this repository a ⭐**

---

<div align="center">

### 🔥 Built with Logic. Powered by Automation. 🔥

</div>

