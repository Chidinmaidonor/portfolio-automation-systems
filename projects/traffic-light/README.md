# 🚦 Traffic Light Control with PLC (TIA Portal + HMI)

## 🔹 Overview
This project demonstrates a **PLC-controlled traffic light system** built with **Siemens TIA Portal**.  
The system ensures safe and efficient control of vehicle and pedestrian signals, with an **HMI interface** for operator monitoring and manual override.  

---

## 🔹 Architecture
![Traffic Light PLC](../../assets/img/traffic_plc.png)

- **PLC:** Siemens S7-1200  
- **Programming Language:** Ladder Logic (TIA Portal)  
- **HMI:** WinCC Basic → Start/stop, status indicators, pedestrian request button  
- **Simulation:** TIA Portal PLC simulator  

---

## 🔹 Features
- 🚦 Automatic sequencing of **Red → Green → Yellow** cycles  
- 🕒 Adjustable timer values for each phase  
- 🚶 Pedestrian crossing mode with push-button request  
- 🔒 Interlocks to prevent unsafe states (e.g., green in both directions)  
- 🎛️ HMI for monitoring + manual override of signals  

---

## 🔹 Steps
1. Designed the traffic signal **state diagram**  
2. Programmed Ladder Logic in **TIA Portal** with timers and interlocks  
3. Built an **HMI screen** in WinCC with start/stop and pedestrian request  
4. Simulated operation in **TIA Portal PLC simulator**  
5. Verified safety logic under different scenarios  

---

## 🔹 Demo
🎥 [Watch Video Demo](https://youtube.com/your-demo-link)  
📷 Screenshots available in `/assets/img/`  

---

## 🔹 Files
- `code/` → TIA Portal project files  
- `state-diagram.png` → Traffic light state diagram  
- `traffic_plc.png` → Screenshot of HMI/PLC simulation  
- `README.md` → Project documentation  

---

## 🔹 Learning Outcomes
- Practical use of **Timers (TON, TOF)** in Ladder Logic  
- Designing safe **interlocks** for automation logic  
- Building simple **HMI interfaces** in WinCC  
- Understanding how PLCs control real-world systems  

---
