Smart Pin Trash: Automatic Waste Classification System


Project Overview
The "Smart Pin Trash" project is an innovative automatic waste classification system developed by a team of students from Helwan University. This system efficiently sorts waste into metal and non-metal categories using embedded systems technology. It leverages multiple ATmega32 microcontrollers, ultrasonic sensors, and an inductive proximity sensor to detect waste type and proximity, ensuring effective waste management.


Key Features

Real-time Waste Level Monitoring: Continuously tracks fill levels in each compartment using ultrasonic sensors.
Automatic Door Operation: Opens upon user detection and closes after a predefined period of inactivity.
Accurate Classification: Utilizes sensor fusion techniques to distinguish between metallic and non-metallic waste.
User-friendly Interface: Features an LCD display for status updates and a servo-controlled sorting mechanism.
Modular Design: Includes custom PCBs and inter-board communication for scalability.

System Architecture
The system comprises sensing, processing, actuation, and interface modules, powered by:

2x ATmega32 microcontrollers
4x Ultrasonic sensors (HC-SR04)
1x Inductive proximity sensor
2x Servo motors
1x LCD display module
Custom PCBs and supporting electronics

Implementation

Hardware: Designed with two custom PCBs housing the microcontrollers and sensor circuits.
Software: Written in C using Atmel Studio, with modular functions for sensor reading, motor control, and LCD interaction.
Working Principle: Detects waste via ultrasonic and inductive sensors, sorts it using servo motors, and displays fill levels on the LCD.

Future Improvements
The modular design allows for enhancements such as additional sensor types, improved accuracy, and integration with IoT for remote monitoring.
Conclusion
The Smart Pin Trash system demonstrates the practical application of embedded systems in waste management, offering a reliable, automated sorting solution with minimal user intervention. Developed by a dedicated team from Helwan University, this project paves the way for sustainable waste handling practices.
