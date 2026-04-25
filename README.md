🤖 HUMANO-X Robotic System
Design and Development of a Servo-Based Humanoid Robot
<img width="3024" height="4032" alt="WhatsApp Image 2026-04-24 at 6 20 21 PM - Copy" src="https://github.com/user-attachments/assets/51ae6227-87fb-4976-8f7d-5e81f210cdd9" />
<img width="3024" height="4032" alt="WhatsApp Image 2026-04-24 at 6 20 12 PM" src="https://github.com/user-attachments/assets/d0e3ba44-2898-4449-a201-9573eafb6eff" />
<img width="3024" height="4032" alt="WhatsApp Image 2026-04-24 at 6 20 25 PM (1)" src="https://github.com/user-attachments/assets/7202152d-efc2-4fd6-b8a3-3694cc6fb7e7" />
<img width="3024" height="4032" alt="WhatsApp Image 2026-04-24 at 6 20 25 PM" src="https://github.com/user-attachments/assets/e61ae32d-54f2-4945-a518-afdb21fd780e" />
<img width="3024" height="4032" alt="WhatsApp Image 2026-04-24 at 6 20 27 PM" src="https://github.com/user-attachments/assets/df11c6d6-4ad1-424e-9c47-ca3334e0c96b" />
<img width="3024" height="4032" alt="WhatsApp Image 2026-04-24 at 6 20 26 PM" src="https://github.com/user-attachments/assets/fc51249b-1131-4df8-82af-23d8c4fdfb54" />
<img width="3024" height="4032" alt="WhatsApp Image 2026-04-24 at 6 20 25 PM (2)" src="https://github.com/user-attachments/assets/bc1afa33-098b-4e11-8b53-c56269a40252" />
<img width="3024" height="4032" alt="WhatsApp Image 2026-04-24 at 6 20 27 PM (1)" src="https://github.com/user-attachments/assets/dedb5b28-7a1e-4a36-ad26-fb6b5eb83929" />
<img width="3024" height="4032" alt="WhatsApp Image 2026-04-24 at 6 20 27 PM (2)" src="https://github.com/user-attachments/assets/111157ce-c19c-4cb8-82cf-148be7a21b42" />
<img width="3024" height="4032" alt="WhatsApp Image 2026-04-24 at 6 20 28 PM" src="https://github.com/user-attachments/assets/9dee53a0-bbdd-4658-a659-a6bfb600c3f1" />
https://github.com/user-attachments/assets/05a5552b-1a72-418b-9cae-a3fa836f495a
https://github.com/user-attachments/assets/a65c34e8-ce78-4934-87da-b6ffa4edbbbb
https://github.com/user-attachments/assets/e283d3dc-78db-4725-829d-d5b454fe5302
https://github.com/user-attachments/assets/c414e51a-8a40-434a-944b-0603d154a406

📌 📖 Overview

The HUMANO-X Robotic System is a servo motor-based humanoid robot designed to simulate human-like movements using multiple joints.

This project combines:

⚙️ Mechanical Design
🔌 Electronics
💻 Embedded Programming

The robot is capable of performing basic arm and leg movements and serves as a foundation for future AI-based robotics systems.

🖼️ 📷 Project Preview

👉 Replace YOUR_IMAGE_LINK with your uploaded GitHub image links

🎯 🎯 Objectives
Build a multi-joint humanoid robot
Implement servo motor control system
Achieve stable standing posture
Enable basic movement (arms & legs)
Prepare for AI and sensor integration
⚙️ 🔩 Components Used
Component	Description
Servo Motors	MG996R / SG90 for joint movement
Arduino UNO	Microcontroller for control
Power Supply	5V–6V external battery
Jumper Wires	Connections
Frame Material	Metal / Acrylic structure
Screws & Brackets	Assembly support
🧠 ⚡ Working Principle
Arduino sends PWM signals to servo motors
Each servo rotates to a specific angle
Each joint is controlled individually
Combined movement creates humanoid motion
🔌 🔧 Circuit Connection
Servo Wiring:
🔴 Red → 5V
⚫ Brown/Black → GND
🟡 Yellow/Orange → Signal Pin
Example Arduino Pins:
Servo	Pin
Right Arm	D3
Left Arm	D5
Right Leg	D6
Left Leg	D9

⚠️ Important:
Use external power supply for multiple servos!

💻 🤖 Arduino Code
#include <Servo.h>

Servo rightArm;
Servo leftArm;
Servo rightLeg;
Servo leftLeg;

void setup() {
  rightArm.attach(3);
  leftArm.attach(5);
  rightLeg.attach(6);
  leftLeg.attach(9);
}

void loop() {

  // Arms Up
  rightArm.write(90);
  leftArm.write(90);
  delay(1000);

  // Arms Down
  rightArm.write(0);
  leftArm.write(0);
  delay(1000);

  // Legs Move
  rightLeg.write(45);
  leftLeg.write(45);
  delay(1000);

  // Reset
  rightLeg.write(0);
  leftLeg.write(0);
  delay(1000);
}
🧪 🧪 Testing
✔ Servo Movement Testing
✔ Stability Testing
✔ Power Supply Testing
📊 📈 Results
Robot successfully performs basic movements
Stable standing achieved
Movement control is smooth
🚀 🔮 Future Improvements
🤖 Walking algorithm
📡 Bluetooth/WiFi control
📷 Camera + AI vision
📏 Ultrasonic sensor (obstacle detection)
🎮 Mobile app control
📚 📌 Applications
Robotics learning
Research & development
Automation systems
AI robotics
👨‍💻 Author

Janaka Kumar
💻 Software Engineering Student
📍 Sri Lanka

⭐ Support

If you like this project:
👉 Give a ⭐ on GitHub
👉 Share with others
