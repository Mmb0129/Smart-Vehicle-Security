#  Smart Vehicle Security and Safety System: Integration of Theft Detection and Accident Control



# Demo : 
https://drive.google.com/drive/folders/1kY5IYFDf-bgPrGKP49D3qB0dDGZFniiI?usp=sharing


## Institution
**SSN College of Engineering, Kalavakkam – 603110**  
**INTERNALLY FUNDED STUDENT PROJECT (IFSP-2023)**  
**Project Duration:** 12 months  
**Budget:** ₹16,000  

## 👥 Team Members
- **Micheal Berdinanth M** – II Year, Department of Computer Science and Engineering  
- **Nandhalal S** – II Year, Department of Computer Science and Engineering  
- **Prashanna Kumar S** – II Year, Department of Computer Science and Engineering  
- **Pranav CM** – II Year, Department of Electrical and Electronics Engineering  

**Project Guide:** Dr. Lakshmi Priya S, Assistant Professor, Department of CSE

---

## 📚 Broad Subject
Automotive Security and Accident Detection

## ❓ Problem Statement
Vehicle theft and delayed accident response are major global issues. Traditional systems like alarms and steering locks fail against modern theft techniques. Simultaneously, the lack of rapid accident detection mechanisms delays rescue, increasing injury severity or fatalities. A unified solution combining both theft prevention and accident control is needed.

---

## 🧠 Project Summary
This system integrates:
- **Vehicle Theft Detection**: Sends SMS and email alerts upon unauthorized access. Enables remote engine locking.
- **Facial Recognition**: Verifies the driver’s identity before ignition.
- **Alcohol Detection**: Prevents vehicle ignition if alcohol is detected in the driver’s breath.
- **Accident Detection**: Uses an accelerometer and GPS to detect crashes and alert guardians/emergency services with real-time location.

---

## 🔑 Keywords
`Vehicle theft detection` `Automatic accident detection` `Rescue system` `Facial recognition` `Alcohol sensor` `IoT` `SMS alerts` `Raspberry Pi`

---

## 🎯 Objectives
- Develop a remote theft detection and engine locking system
- Integrate facial recognition using Raspberry Pi
- Add alcohol detection sensor-based ignition lock
- Enable automatic accident detection using accelerometers
- Send emergency alerts and accident location via SMS and email
- Provide cost-effective telematic services

---

## 🛠️ Problem Definition

###  Vehicle Theft
- Financial loss and increased crime
- Traditional systems are ineffective
- Need for smarter theft deterrence

###  Alcohol Impairment
- Major cause of road accidents
- Legal and safety implications
- Must prevent drunk driving

###  Delayed Accident Response
- Golden Hour importance
- Difficulty in locating accident sites
- Need for automated, location-based alerts

---


## 🆕 Proposed System and Innovations

| Feature | GPS-GSM Tracking | Arduino-based Tracker | Accident Detection Tracker | **Proposed System** |
|--------|------------------|------------------------|-----------------------------|----------------------|
| GSM Module | ✅ | ✅ | ✅ | ✅ |
| SMS Notification | ✅ | ❌ | ✅ | ✅ |
| GPS Accuracy (≤10m) | ✅ | ✅ | ✅ | ✅ |
| Remote Engine Lock | ❌ | ❌ | ✅ | ✅ |
| Alcohol Sensor | ❌ | ❌ | ❌ | ✅ |
| Facial Recognition | ❌ | ❌ | ❌ | ✅ |
| Accident Detection | ❌ | ❌ | ✅ | ✅ |
| Real-time Location | ✅ | ✅ | ✅ | ✅ |

---

## Telematic Devices: Current vs Proposed

| Feature | Existing | Proposed |
|--------|----------|----------|
| Annual Cost | ₹30,000 | ₹15,000–₹20,000 |
| GPS Tracking | ✅ | ✅ |
| Remote Engine Control | ✅ | ✅ |
| Driving Behavior Analysis | ✅ | ✅ |
| Accessibility | Only high-end vehicles | Affordable for all |

---

## 🚀 Modules Description

### 1. Vehicle Theft Detection
- Raspberry Pi detects intrusion
- Sends SMS/email via GSM
- Owner can send SMS to remotely lock engine
- Live location sent via GPS every 10 mins

### 2. Facial Recognition & Alcohol Detection
- Camera + Facial Recognition algorithm (Raspberry Pi)
- Alcohol Sensor + MQ-135 sensor
- Prevents ignition if unknown face or alcohol detected
- Sends alerts to owner if violated

### 3. Accident Detection & Rescue
- Accelerometer detects impact severity
- Sends emergency alert + GPS location via SMS/email
- Alerts both guardian and rescue team

---

Future Scope

Integrate real-time cloud dashboard for owners.

Add video-based driver drowsiness detection.

Mobile app for real-time notifications and control.

