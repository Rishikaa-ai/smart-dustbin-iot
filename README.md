#  Smart Dustbin (IoT Based)

##  Project Overview
This project is an IoT-based Smart Dustbin that can automatically open its lid, detect garbage level, and move using remote control. It uses **Arduino** for automation and **ESP32** for IoT-based monitoring and control.

---

##  Features
- Automatic lid opening  
- Garbage level detection  
- Live status on mobile  
- Remote movement control  
- IoT-based smart monitoring  

---

##  Working

### 🔹 Lid Opening System
- Ultrasonic sensor detects hand/object  
- Arduino activates servo motor  
- Lid opens automatically  

### 🔹 Garbage Level Detection (IoT)
- Ultrasonic sensor (inside lid) measures garbage level  
- ESP32 sends data to Blynk app  
- Displays **Full / Empty** status  

### 🔹 Movement System
- Dustbin is placed on a robotic cart  
- Controlled using mobile app  

**Controls:**
- Forward  
- Backward  
- Left  
- Right  

---

##  Components Used

###  Lid System
- Arduino Board  
- Ultrasonic Sensor  
- Servo Motor  

###  IoT Monitoring
- ESP32  
- Ultrasonic Sensor  
- Blynk App  

###  Movement System
- L298N Motor Driver  
- DC Motors (2)  
- IR Sensor  
- Switch  
- Robotic Chassis  

---

##  Mobile App
**Blynk App** is used for:
- Monitoring dustbin status  
- Controlling movement  

---

##  Project Images

###  Smart Dustbin Setup
Complete view of the system  
`images/setup.jpg`

###  Wiring Connection
Hardware connections and wiring  
`images/wiring.jpg`

###  Working Model
Dustbin in action  
`images/working.jpg`

---

##  Blynk App Screenshots

###  Control Dashboard
Movement controls interface  
`images/blynk_dashboard.jpg`

###  Dustbin Status
Real-time garbage level  
`images/blynk_status.jpg`

---

##  Circuit Diagram
Connections between Arduino, ESP32, sensors, and motor driver  
`circuit_diagram/circuit.png`

---

##  Code
- Arduino code for lid opening system  
- ESP32 code for IoT monitoring and movement control  
  (Available in `/code` folder)

---

##  Future Scope
- Smart city integration  
- Automatic garbage collection system  
- GPS tracking  
- AI-based waste detection  

---

##  Author
**Rishika Sahu**

---

##  Conclusion
This project demonstrates how IoT and automation can improve waste management systems by making them smarter, efficient, and user-friendly.
