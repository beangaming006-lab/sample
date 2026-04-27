# 🌟 SKILL LAB PRACTICAL HACKATHON  
## Final Project Documentation

---

# 1. Team Identity

## 1.1 Studio / Group Name  
**Team STOPPABLE**

---

## 1.2 Team Members

| Name | Primary Role | Secondary Role | Strengths |
|------|-------------|---------------|----------|
| **Saumitra Bata** | Hardware & Coding | Documentation | Strong communication, structured thinking |
| **Anish Deodhar** | Fabrication & Hardware | Coding | Material handling, practical execution |
| **Virat Dhoot** | Documentation & Hardware | Coding | Organization, clarity in presentation |
| **Nitisha Dung** | Fabrication & Hardware | Coding | Hands-on building, hardware integration |

---

## 1.3 Project Title  
### **Sync-Box**

---

## 1.4 One-Line Pitch  
*A time-synchronized, RFID-enabled smart medicine system that ensures the right person takes the right medication at the right time.*

---

## 1.5 Expanded Project Idea

**Sync-Box** is an intelligent medication management system designed for shared environments such as old-age homes, hostels, or care facilities.

The system integrates:
- RFID-based identity recognition  
- Time-based medication scheduling  
- Interactive feedback (LEDs, touch sensors, buzzer)  

Each user carries a unique RFID tag. When scanned:
- The system identifies the patient  
- Determines the current time slot  
- Activates only the relevant medicine compartments  

This ensures:
- No confusion between users  
- No incorrect medication  
- No accidental overdosing  

By combining embedded electronics with simple interaction design, Sync-Box transforms a passive medicine box into an **active, decision-driven assistant**.

---

# 2. Project Philosophy

## 2.1 Experience Focus

While rooted in a real-world problem, Sync-Box is designed as an **interactive system experience**:

- RFID scan creates personalization  
- LEDs provide visual guidance  
- Touch sensors provide feedback  
- Alerts create urgency  

This makes the system:
- intuitive  
- responsive  
- engaging  

---

# 3. Inspiration

## 3.1 References

| Source | Insight |
|------|--------|
| Scientific Study | Medication errors are a leading cause of preventable harm |
| Research Articles | Multi-drug management is complex in shared environments |

---

## 3.2 Original Contribution

Sync-Box introduces:

- Identity-based dispensing (RFID)  
- Time-aware logic  
- State-based tracking (Taken / Not Taken)  
- Error prevention (double-dose blocking)  

This transforms the system from a **passive reminder** into an **active decision engine**.

---

# 4. User Experience Journey

It is morning in a shared care facility.

A patient approaches the Sync-Box and taps their RFID card.

Instantly:
- The system recognizes them  
- Identifies the correct medicines  
- Lights up only the required compartments  

The user simply follows the lights.

After taking each medicine:
- They confirm via touch  
- The system records completion  

If another patient arrives:
- The system adapts instantly  
- Displays a different set of medicines  

Meanwhile, a caregiver can monitor:
- Who has taken medication  
- Who is late  
- Who missed doses  

---

# 5. Definition of Success

## 5.1 Usability

A system is usable if:
- it is easy to understand  
- requires minimal thinking  
- prevents user errors  

Sync-Box achieves this by:
- replacing instructions with visual guidance  
- replacing memory with automation  
- replacing trust with verification  

---

## 5.2 Minimum Viable System

The core system includes:

- RFID identification  
- Time-slot logic  
- LED guidance  
- Touch confirmation  
- Basic alert system  

---

## 5.3 Stretch Features

- Automatic dispensing  
- Mobile/web dashboard  
- Remote alerts  
- Voice assistant integration  

---

# 6. System Overview

## 6.1 System Type

- Electronics-based  
- Sensor-based  
- Interactive system  
- Logic-driven system  

---

## 6.2 High-Level Working

### Input Stage
- RFID → patient identity  
- Time → slot detection  
- Touch → confirmation  

### Processing Stage
- Match RFID to patient  
- Determine current slot  
- Fetch medicine schedule  
- Check if already taken  

### Output Stage
- LEDs indicate medicines  
- Red LED shows error  
- Buzzer gives alerts  
- Serial logs activity  

---

## 6.3 Core Logic

The system operates as a **state machine**:
