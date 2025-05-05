Self-Balancing Two-Wheeled Robot

🔧 Project Overview

This project is a two-wheeled, self-balancing robot built as a graduation project. It uses a feedback control system (PID) to maintain its balance, even when pushed slightly or when it encounters minor disturbances. The robot is programmed using the Arduino IDE and the code is uploaded to an Arduino Nano microcontroller.

📦 Project Contents

SelfBalancingRobot.ino: Arduino source code

Self_Balancing_Robot_Documentation/: A folder containing the full project documentation, including theory, hardware details, and implementation

pcb/PCB_Schematic.fzz: A Fritzing-based schematic of the custom PCB

project video/: Demonstration video of the self-balancing robot in action

Supporting files: Libraries, diagrams, or calibration data (if any): Libraries, diagrams, or calibration data (if any): Libraries, diagrams, or calibration data (if any): Libraries, diagrams, or calibration data

📁 Folder Structure

Self-Balancing-Robot/
├── code/
│   └── SelfBalancingRobot/
│       └── SelfBalancingRobot.ino
├── pcb/
│   └── PCB_Schematic.fzz
├── project video/
│   └── demo_video.mp4
├── Self_Balancing_Robot_Documentation/
│   └── Full_Project_Report.pdf
├── Project_Report.pdf
└── README.md

🛠️ Hardware Used

Arduino Nano

MPU6050 (Gyroscope + Accelerometer)

L298N Motor Driver

2 DC motors with wheels

18650 Li-ion batteries (or other power source)

Chassis or frame

Jumper wires

🧠 How It Works

The robot uses data from the MPU6050 sensor to determine its tilt angle. A PID control algorithm processes this data and adjusts the motor speeds to keep the robot upright.

🚀 Getting Started

Prerequisites

Arduino IDE installed on your PC

USB cable for Arduino Nano

Required Arduino libraries (e.g., Wire, I2Cdev, MPU6050)

Uploading the Code

Open the Arduino IDE.

Open SelfBalancingRobot.ino.

Connect your Arduino Nano using a USB cable.

Go to Tools > Board and select Arduino Nano.

Go to Tools > Port and choose the correct COM port.

Click the Upload button.

⚠️ Important: Always ensure the correct COM port is selected. Wrong selection may result in upload errors.

📄 Documentation

See Project_Report.pdf for detailed explanation of:

Control system design (PID tuning)

Hardware assembly

Calibration steps

Challenges and solutions

✨ Features

Real-time balancing using PID

Manual PID tuning possible

Easily customizable for additional features (Bluetooth control, obstacle avoidance, etc.)

🧑‍🎓 Credits

This project was created as a final-year graduation project by [Your Name].

📜 License

This project is open-source and available under the MIT License.

