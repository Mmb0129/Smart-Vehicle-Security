# Smart-Vehicle-Security
https://drive.google.com/drive/folders/1kY5IYFDf-bgPrGKP49D3qB0dDGZFniiI?usp=sharing

🚗 Smart Vehicle Security and Safety System
Project Type: Internally Funded Student Project (IFSP-2023)
Institution: SSN College of Engineering
Budget: ₹16,000
Duration: 12 Months
Department Involved: Computer Science & Engineering

📌 Abstract
The Smart Vehicle Security and Safety System addresses two pressing challenges in the automotive domain: vehicle theft prevention and accident detection & rescue. Leveraging Raspberry Pi, facial recognition, alcohol sensing, GPS, GSM, and accelerometer-based IoT technologies, the system provides real-time theft alerts, remote ignition control, and immediate accident notifications — ensuring safety for both vehicle and driver.

🎯 Objectives
🔐 Detect unauthorized vehicle access attempts.

📸 Use facial recognition to authenticate the driver.

🍷 Prevent drunk driving via alcohol sensors.

📉 Detect accidents using an accelerometer sensor.

📍 Send real-time location alerts to guardians/rescue services.

💬 Enable live vehicle tracking and SMS/email notifications.

🔧 Tech Stack and Hardware Components
Category	Tools/Modules Used
Microcontroller	Raspberry Pi
Communication	GSM Module, GPS Module
Sensors	Alcohol Sensor (MQ-3/MQ-135), Accelerometer
Image Processing	Facial Recognition using OpenCV (Python)
Communication	SMS/Email Notifications
Software	Python, SMTP, Twilio API (optional), Flask
🔍 Features & Innovations
Feature	Available in Proposed System
GSM Module for communication	✅
Remote engine lock via SMS	✅
GPS-based real-time vehicle tracking	✅ (accuracy within 10m)
Alcohol detection before ignition	✅
Facial recognition for owner verification	✅
Accelerometer-based accident detection	✅
Email + SMS notifications	✅
Cost-effective compared to commercial models	✅
🧠 System Workflow
1. Vehicle Theft Detection
Intrusion detected → SMS sent to owner.

Owner replies with command → Engine locked remotely.

Email notification also triggered.

2. Alcohol & Face Recognition Check
Driver's face is scanned.

Alcohol level is detected via MQ sensor.

If valid face & no alcohol detected → ignition allowed.

3. Accident Detection & Emergency Alert
Accelerometer detects unusual shock/tilt.

GPS location is fetched and sent to emergency contacts.

Email/SMS alerts sent instantly.

📸 Screenshots and Architecture
🧱 System Architecture Diagram

🔁 Process Flow Diagram

📷 Alcohol detection and face recognition UI

📩 Sample SMS/email alert screenshots

📍 Location tracking demo (Google Maps integration)

📊 Cost Advantage
Feature	Existing Commercial Telematics	Proposed System
Price	₹30,000/year (subscription) or high-end cars (₹1L+)	₹15,000–₹20,000 one-time
Alcohol Detection	❌	✅
Facial Recognition	❌	✅
Custom Alerts (Email/SMS)	❌	✅
🚀 Future Scope
Integrate real-time cloud dashboard for owners.

Improve facial recognition with deep learning models.

Add video-based driver drowsiness detection.

Mobile app for real-time notifications and control.

👥 Team
Nandhalal S – CSE, II Year

Prashanna Kumar S – CSE, II Year

Micheal Berdinanth M – CSE, II Year

Pranav CM – EEE, II Year

Mentor: Ms. Lakshmi Priya S, Assistant Professor, CSE
