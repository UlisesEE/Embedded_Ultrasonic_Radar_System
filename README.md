# Embedded_Ultrasonic_Radar_System
Embedded Ultrasonic Radar System
📖 Overview

The Embedded Ultrasonic Radar System is a project that combines Arduino hardware with Processing visualization to create a real-time radar-like display. Using an ultrasonic sensor mounted on a servo motor, the system continuously scans the environment, measures distances, and sends that data to the computer for graphical rendering in a radar interface.

This project demonstrates how embedded systems, sensors, and visualization software can work together to create a functional prototype that mimics real-world radar technology.

🔧 Equipment Used

ELEGOO UNO R3 (Arduino Uno compatible microcontroller board)

HC-SR04 Ultrasonic Sensor (for distance measurement)

SG90 Servo Motor (to rotate the ultrasonic sensor for scanning)

Breadboard & Jumper Wires (for connections)

USB Cable (to connect Arduino to computer)

Computer with:

Arduino IDE (for writing and uploading Arduino code)

Processing IDE (for radar visualization)

⚙️ Hardware Assembly

Mount the Ultrasonic Sensor

Attach the HC-SR04 sensor on top of the SG90 servo motor so that it can rotate and scan.

Secure with hot glue or a small bracket.

Wire the Components

Servo Motor → Arduino

VCC → 5V

GND → GND

Signal → Digital Pin 9

HC-SR04 Ultrasonic Sensor → Arduino

VCC → 5V

GND → GND

Trig → Digital Pin 10

Echo → Digital Pin 11

Power Supply

The Arduino Uno is powered via the USB cable from your computer.


🚀 How It Works

The Arduino sweeps the ultrasonic sensor using the servo motor.

At each angle, it measures distance and sends the result via serial.

The Processing sketch receives this data in real time.

A radar interface is drawn, showing:

Circular arcs = distance ranges.

Green sweeping line = current sensor angle.

Blips = detected objects.

🔮 Future Improvements

Store distance data and generate a 2D map.

Integrate with wireless modules (Bluetooth/WiFi) for remote radar.

![IMG_4914](https://github.com/user-attachments/assets/d9bf78c1-c573-49bb-81d0-ae1d8542037d)


