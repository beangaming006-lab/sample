# 🧠💊 SYNC-BOX  
### *A Smart, Time-Synced RFID-Based Medicine Dispensing System*

---

## 🎯 SKILL LAB PRACTICAL HACKATHON

> **Project Weight:** 100%  
> **Team Size:** 4 Students  
> **Duration:** 8 Hours  
> **Effort:** 32 Team Hours  
> **Category:** Interactive Embedded System  

---

# ✨ Project Overview

**Sync-Box** is an intelligent, time-synchronized medicine dispensing system designed to ensure that **the right person takes the right medicine at the right time**.

Using **RFID authentication**, **time-slot logic**, and **interactive feedback**, the system eliminates confusion in multi-user environments such as **homes, hostels, and elderly care centers**.

---

# 👥 Team Identity

## 🏷️ Team Name  
**STOPPABLE**

## 👨‍💻 Team Members

| Name              | Primary Role             | Secondary Role  | Strengths |
|-------------------|--------------------------|------------------|----------|
| Saumitra Bata     | Hardware & Coding        | Documentation    | Communication, Clarity |
| Anish Deodhar     | Fabrication              | Coding           | Material Handling |
| Virat Dhoot       | Documentation            | Hardware         | Structured Thinking |
| Nitisha Dung      | Hardware & Fabrication   | Coding           | Precision, Assembly |

---

# 🚀 Project Title  
## **SYNC-BOX**

---

# 💡 One-Line Pitch

> A **smart RFID-enabled medicine box** that ensures **accurate, personalized, and timely medication delivery**.

---

# 🧩 Expanded Idea

Sync-Box is a **multi-user intelligent medicine management system**.

It:
- Alerts users when it’s time to take medicine  
- Identifies users via **RFID cards**  
- Dispenses only their assigned medication  
- Prevents overdosing  
- Tracks adherence  

### 🔧 Core Technologies:
- Raspberry Pi Pico 2  
- RC522 RFID Module  
- Touch Sensors  
- LEDs + Buzzer  
- Time-slot Logic  

---

# 🎭 Experience Philosophy

This project is not just a utility — it’s an **interactive experience**.

It transforms:
- ❌ Confusion → ✅ Clarity  
- ❌ Dependency → ✅ Independence  
- ❌ Manual tracking → ✅ Smart automation  

---

# 🌍 Inspiration

| Source | Insight |
|------|--------|
| NCBI Report | Medication errors cause preventable deaths |
| Wikipedia (Overmedication) | Multi-drug management is complex |

---

# ⚡ Original Twist

Unlike traditional pill boxes:

✅ **User Verification (RFID)**  
✅ **Time-slot intelligence**  
✅ **Multi-user safe system**  
✅ **Real-time tracking possibility**  

---

# 👤 User Journey

At **8:00 AM**, Sync-Box lights up.

A user:
1. Walks to the device  
2. Taps their RFID card  
3. System verifies identity  
4. Correct compartment is indicated  
5. User takes medicine  
6. Confirms via touch sensor  

➡️ System logs: **“Dose Taken”**

Caregiver can:
- Monitor remotely  
- Identify missed doses  
- Track compliance  

---

# ✅ Definition of Success

## ✔️ Usable System

A successful system:
- Is intuitive for elderly users  
- Prevents incorrect usage  
- Requires minimal learning  

---

## 🎯 Minimum Viable Version

- Single user  
- LED/Buzzer reminder  
- Button confirmation  
- Basic logging  

---

## 🚀 Stretch Features

- Automated dispensing  
- Web dashboard  
- Voice assistant integration  

---

# ⚙️ System Overview

## 🔁 Workflow

### INPUT
- RFID Scan  
- Time Logic  
- Touch Confirmation  

### PROCESS
- User identification  
- Time-slot verification  
- Dose validation  

### OUTPUT
- LEDs guide user  
- Buzzer alerts  
- Serial logging  

---

## 🧠 System Architecture

```
RFID → Pico → Logic Engine → LEDs / Alerts → Confirmation → Logging
```

---

# 🔌 Electronics

## 🧾 Components

| Component | Qty | Purpose |
|----------|----|--------|
| Raspberry Pi Pico 2 | 1 | Controller |
| RFID RC522 | 1 | User Identification |
| Touch Sensors | 5 | Confirmation |
| LEDs | 8 | Visual Feedback |
| Buzzer | 2 | Alerts |

---

## 🔗 Wiring Highlights

- SPI Communication (RFID)  
- GPIO-controlled LEDs  
- Touch sensors → Input pins  
- Common Ground architecture  

---

# 🔋 Power Plan

| Parameter | Value |
|----------|------|
| Source | USB |
| Voltage | 3.3V |
| Concern | LED brightness drop |

---

# 💻 Software Logic

## 🔄 Flow

1. Initialize system  
2. Wait for RFID scan  
3. Identify user  
4. Check time slot  
5. Activate LEDs  
6. Wait for touch confirmation  
7. Log status  
8. Reset  

---

# 📦 Bill of Materials

| Item | Cost (₹) |
|------|--------|
| Electronics | 400 |
| Mechanical | 200 |
| Contingency | 300 |
| **Total** | **900** |

---

# 🛠️ Fabrication

## Process

- CAD Design  
- Laser Cutting  
- Assembly  
- Wiring  
- Finishing  
- Iteration  

---

# 🧪 Testing

## ✔️ Tested Areas

- RFID Detection  
- Sensor Input  
- LED Output  
- Time Logic  

---

## 🐞 Debug Log Example

| Issue | Fix |
|------|-----|
| Unstable detection | Adjusted wiring |

---

# 🎮 Final Outcome

## 🧾 Description

The final Sync-Box successfully:
- Identifies users  
- Prevents incorrect dosage  
- Guides via LEDs  
- Logs actions  

---

## ✅ What Works Well

- Reliable RFID detection  
- Clear user interaction  
- Simple and intuitive design  

---

## ⚠️ Improvements Needed

- Add display screen  
- Improve enclosure finish  
- Add cloud dashboard  

---

## 🔄 Changes from Plan

- Simplified mechanical dispensing  
- Focus shifted to reliability over complexity  

---

# 🧠 Reflection

## 💪 Team Strengths
- Strong collaboration  
- Clear communication  
- Efficient execution  

## ⏳ Challenges
- Time constraints  
- Hardware debugging  

---

## 📚 Technical Learnings

- Embedded systems integration  
- RFID communication  
- Real-time logic handling  

---

## 🎨 Design Learnings

- Simplicity improves usability  
- Visual feedback is powerful  
- Iteration is essential  

---

## ⏱️ If We Had 1 More Hour

We would:
- Add web dashboard  
- Improve aesthetics  
- Optimize code  

---

# 📸 Build Gallery

### 🧩 Concept
![Concept](https://github.com/ViratDhoot/SKILLLAB__PROR-2026-STOPPABLE/blob/main/images/non%20labled.png)

### 🔧 Build
![Build](https://github.com/ViratDhoot/SKILLLAB__PROR-2026-STOPPABLE/blob/main/images/Basic%20Build.jpeg)

### 🧪 Testing
![Testing](https://github.com/ViratDhoot/SKILLLAB__PROR-2026-STOPPABLE/blob/main/images/Build%20Testing.jpeg)

---

# ✅ Submission Checklist

- [x] Documentation complete  
- [x] Build completed  
- [x] Testing done  
- [x] Reflection written  

---

# 🌟 Final Note

> Sync-Box is not just a device —  
> it’s a step toward **safer, smarter, and independent living**.

---
