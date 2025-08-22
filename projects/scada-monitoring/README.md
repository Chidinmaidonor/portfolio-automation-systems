# 📊 SCADA Monitoring Dashboard

## 🔹 Overview
This project implements a **Supervisory Control and Data Acquisition (SCADA) dashboard** for monitoring and controlling an industrial process in real time.  
It demonstrates how **SCADA systems integrate with PLCs** to provide operators with visibility, alarms, and control over automation systems.

---

## 🔹 Architecture
![SCADA UI](../../assets/img/scada_ui.png)

- **PLC:** Siemens S7-1200  
- **SCADA Platform:** WinCC / TIA Portal  
- **HMI Elements:** Real-time process values, alarms, trend graphs, operator input  
- **Communication:** OPC UA / Profinet  

---

## 🔹 Features
- 📡 Real-time data acquisition from PLC sensors  
- ⚠️ Alarm management for abnormal process values  
- 📈 Historical trend logging for process variables  
- 🎛️ Operator controls for start/stop sequences  
- 🔒 Access levels for operators vs admins  

---

## 🔹 Steps
1. Configured **PLC tags** in TIA Portal for process inputs/outputs  
2. Integrated PLC tags with **WinCC SCADA environment**  
3. Built operator dashboard with gauges, buttons, and trend graphs  
4. Configured alarms and events for abnormal readings  
5. Simulated and tested with a PLC model  

---

## 🔹 Demo
🎥 [Watch Video Demo](https://youtube.com/your-demo-link)  
📷 Screenshots available in `/assets/img/`  

---

## 🔹 Files
- `code/` → PLC program exports (TIA Portal project files)  
- `scada_ui.png` → Dashboard interface screenshot  
- `README.md` → Project documentation  

---

## 🔹 Learning Outcomes
- Understanding SCADA system architecture  
- Linking **PLC logic to SCADA dashboards**  
- Alarm management and trend visualization  
- Basics of industrial communication protocols (OPC UA, Profinet)  

---
