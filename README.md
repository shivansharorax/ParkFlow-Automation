# 🚗 ParkFlow Automation – PLC Smart Parking System

> PLC-Based Smart Parking Management System using Mitsubishi PLC, GX Works3, Ladder Logic, and HMI

![PLC](https://img.shields.io/badge/PLC-Mitsubishi-blue)
![Platform](https://img.shields.io/badge/Software-GX%20Works3-orange)
![Language](https://img.shields.io/badge/Programming-Ladder%20Logic-green)
![Status](https://img.shields.io/badge/Project-Educational-success)

---

# 📌 Project Overview

**ParkFlow Automation** is a PLC-based Smart Parking System developed using **Mitsubishi PLC**, **GX Works3**, **Ladder Logic**, and **HMI Design** for automated parking management and monitoring.

The system automates:
- Vehicle entry and exit control
- Parking slot allocation
- Slot occupancy monitoring
- Parking full detection
- Vehicle counting
- Revenue analytics

The project demonstrates industrial automation concepts using PLC memory mapping, Ladder Logic programming, timers, counters, and HMI communication.

---

# 🎯 Objectives

- Automate parking management using PLC
- Reduce manual parking operations
- Monitor parking occupancy in real time
- Maintain vehicle and revenue statistics
- Implement industrial automation concepts practically

---

# ⚙️ Features

## 🚘 Parking Management
- Automatic parking slot allocation
- Sequential free slot detection
- Parking full detection
- Slot release during vehicle exit

## 🚦 Vehicle Control
- Automated entry gate
- Automated exit gate
- 2-Wheeler and 4-Wheeler handling

## 📊 Monitoring & Analytics
- Real-time occupancy monitoring
- Available slot calculation
- Vehicle counting
- Revenue tracking

## 🖥️ HMI Features
- Dashboard screen
- Entry and exit screens
- Parking lot visualization
- Revenue analytics display
- Gate status indicators

---

# 🔄 System Workflow

## 🚗 Vehicle Entry

1. User selects vehicle type from HMI
2. PLC checks next available slot
3. Free slot is assigned automatically
4. Entry gate opens
5. Slot occupancy updates
6. Vehicle counters update

---

## 🚙 Vehicle Exit

1. User selects occupied slot
2. PLC clears slot memory
3. Parking fee is calculated
4. Revenue updates automatically
5. Counters decrease
6. Exit gate opens

---

# 🧠 PLC Logic Overview

| Logic Section | Function |
|---|---|
| Timer Logic | Parking duration and delays |
| Slot Allocation | Sequential free slot assignment |
| Slot Memory | M200–M209 occupancy memory |
| Vehicle Counting | Total, 2W, and 4W counters |
| Gate Control | Entry and exit gate operation |
| Parking Full Logic | Detects full parking condition |
| Revenue Calculation | Revenue analytics |
| HMI Communication | PLC-HMI data transfer |
| Slot Release Logic | Clears occupied slot |

---

# 🔌 I/O List

## Inputs

| Device | Description |
|---|---|
| M100 | Entry Trigger |
| M101 | Exit Trigger |
| M102 | 2W Vehicle Selection |
| M103 | 4W Vehicle Selection |
| HMI Slot Selection | Exit Slot Selection |

---

## Outputs

| Device | Description |
|---|---|
| Y0 | Entry Gate |
| Y1 | Exit Gate |
| M200–M209 | Slot Occupancy Memory |
| HMI Indicators | Slot Status Display |
| Revenue Registers | Revenue Analytics |

---

# 📊 Revenue Analytics

The system maintains:
- 2W Revenue
- 4W Revenue
- Total Revenue
- Occupied Vehicle Count
- Available Slot Count

Parking fees are calculated according to:
- Vehicle type
- Parking duration

---

# 🖥️ HMI Overview

The HMI includes:
- Dashboard Screen
- Vehicle Entry Page
- Vehicle Exit Page
- Parking Lot View
- Revenue Analytics Page
- Parking Full Indicator
- Gate Status Display
- Occupancy Counters

---

# 📂 Repository Structure

```text
ParkFlow-Automation/
│
├── ladder-logic/
│   ├── parking_ladder.pdf
│   └── gxworks_project/
│
├── hmi-screens/
│   ├── dashboard.png
│   ├── entry_page.png
│   ├── exit_page.png
│   ├── lot_view.png
│   └── revenue_page.png
│
├── images/
│   ├── block_diagram.png
│   └── lot_view.png
│
├── report/
│   └── ParkFlow_Report.pdf
│
└── README.md
```
---

# 🎯 Applications

- Smart City Parking
- Shopping Mall Parking
- Office Parking Systems
- Residential Parking
- Industrial Parking Areas
- College Parking Management

---

# ⚠️ Limitations

- Fixed parking capacity
- Manual exit slot selection
- No RFID integration
- No camera-based identification
- Local PLC-based data storage only

---

# 🚀 Future Improvements

- RFID-based vehicle identification
- Number plate recognition
- IoT integration
- Cloud database connectivity
- Mobile app monitoring
- Online parking reservation
- Automatic payment gateway integration

---

# 🛠️ Technologies Used

- Mitsubishi PLC
- GX Works3
- GX Designer3
- Ladder Logic Programming
- HMI Design
- Industrial Automation Concepts

---

# 👨‍💻 Author

**Shivansh Arora**  
Electronics & Instrumentation Engineering  
Institute of Technology, Nirma University

---

# 📜 License

This project is developed for educational and learning purposes only.
