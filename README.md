<img src="https://github.com/user-attachments/assets/7001829a-08c7-46ca-a1e1-5cf2f8b73cc6" alt="Arogya Sathi Image" width="50%">

# 🏥 Arogya Sathi – IoT Based Pill Dispenser

- 🎥 [Watch Demo Video](https://youtu.be/E0JN5Vs1H8Q?feature=shared)  

An **IoT-enabled automatic pill dispenser** designed for elderly healthcare.  
The system ensures timely medicine intake with real-time monitoring, scheduling, and notifications through a companion mobile app.  


## 🚀 Features
- 📦 **Automatic Pill Dispensing** – Controlled via scheduled timings.  
- 📡 **IoT Integration** – Uses MQTT for real-time communication between server and dispenser.  
- 📲 **Companion App** – Built with Flutter for patients and caregivers.  
- 🔔 **Reminders & Alerts** – Voice based announcement notification for users when it’s time to take medicines.  
- 📑 **Doctor–Patient Management** – Doctors can assign medications, notes, and schedules.  
- 👴 **Elder-Friendly Design** – Simplified interface with minimal user effort.  


## 🛠️ Tech Stack
- **Hardware**: Raspberry Pi, IR Sensors, BO Motors & Motor Driver Module with PWM Control (Dispenser Modules), Green Diffused Led  
- **Backend**: Python, Flask, Mosquitto MQTT Broker  
- **Mobile App**: Flutter (Android/iOS)  
- **Database**: SQLite

## Resources:
- 💻 [Companion App Repo](https://github.com/SP-XD/pill_dispenser_client_.git)  
- 💻 [Server Repo](https://github.com/SP-XD/pill_dispenser_server)  
- 💻 [Pill dispenser device repo](https://github.com/)

## Pill Dispenser Device Overview
<img width="50%" alt="Pill dispenser overview" src="https://github.com/user-attachments/assets/a7ff70e0-ead5-4d87-8715-5ed282388d02" />

## 📐 System Architecture

1. **Raspberry Pi Client**  
   - Controls pill dispenser modules  
   - Detects pill pickup via IR sensors  
   - Communicates with server via MQTT  

2. **Server (Backend)**  
   - Manages doctors, patients, medicines, and schedules  
   - Publishes MQTT commands for dispensing  
   - Stores logs and health-related notes  

3. **Companion App**  
   - Doctor and patient login  
   - Medicine schedule management  
   - Notifications & reminders  

## Circuit Diagram (Pill Dispenser System)
<img width="50%" alt="circuit diagram" src="https://github.com/user-attachments/assets/9813ff85-7c45-404d-a9c7-b87f4074dd6d" />



