# Smart Pin Trash: Automatic Waste Classification System

## 🚀 Project Overview

**Smart Pin Trash** is an innovative automatic waste classification system developed by a team of students from **Helwan University**. The system intelligently sorts waste into *metallic* and *non-metallic* categories using embedded systems technology. It incorporates **multiple ATmega32 microcontrollers**, **ultrasonic sensors**, and an **inductive proximity sensor** to detect both the type and proximity of waste — enabling efficient and reliable waste management.

---

## 🔑 Key Features

- **Real-time Waste Level Monitoring**  
  Continuously tracks bin fill levels using ultrasonic sensors for each compartment.

- **Automatic Door Operation**  
  Detects user presence and opens the lid automatically; closes after a set time of inactivity.

- **Accurate Classification**  
  Employs sensor fusion to distinguish between metallic and non-metallic materials with precision.

- **User-friendly Interface**  
  LCD display provides live status updates, supported by a servo-powered sorting mechanism.

- **Modular Design**  
  Built with custom PCBs and inter-board communication, allowing for future expansion and maintenance.

---

## 🧠 System Architecture

The system integrates sensing, processing, actuation, and display modules. Core components include:

- `2x` ATmega32 microcontrollers  
- `4x` HC-SR04 Ultrasonic Sensors  
- `1x` Inductive Proximity Sensor  
- `2x` Servo Motors  
- `1x` LCD Display Module  
- Custom PCBs and additional electronic circuits

---

## 🛠 Implementation

- **Hardware:**  
  Designed using two custom PCBs that host the microcontrollers and sensor interfaces.

- **Software:**  
  Written in C using **Atmel Studio**, with modular code for:
  - Sensor data acquisition  
  - Motor control  
  - LCD interaction

- **Working Principle:**  
  Waste is detected via ultrasonic and inductive sensors, then sorted by servo motors. The LCD shows fill levels in real time.

---

## 🔭 Future Improvements

Thanks to its modular nature, the system can be enhanced with:

- More advanced or varied sensors  
- Improved classification algorithms  
- IoT integration for remote status monitoring and data collection

---

## 📌 Conclusion

The **Smart Pin Trash** system showcases the power of embedded systems in sustainable waste management. It offers a robust, automated solution requiring minimal user interaction — a strong step toward smarter, greener cities.  
Proudly developed by the engineering team at **Helwan University**.
