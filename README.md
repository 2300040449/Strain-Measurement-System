## Strain Measurement System Using Arduino UNO
The Strain Measurement System is an embedded systems project designed to measure mechanical strain in real time using an Arduino Uno, HX711 amplifier module, 
and metallic foil strain gauges. The system acquires low-level strain signals, amplifies them using the HX711's 24-bit ADC, and processes the data through the 
Arduino to provide accurate and continuous strain measurements.This project demonstrates the integration of sensors, signal conditioning, analog-to-digital conversion, 
and embedded programming for structural health monitoring applications. It includes a tare calibration feature for improved measurement accuracy and outputs real-time 
strain values through the Arduino Serial Monitor.The project serves as a practical implementation of embedded system design, sensor interfacing, and data acquisition 
techniques, making it suitable for learning, research, and prototype development in structural monitoring and industrial measurement systems.
## Features
- 4-channel strain measurement
- Real-time data acquisition
- HX711 24-bit ADC interface
- Push-button tare calibration
- 10 Hz sampling rate
- Serial Monitor output

## Hardware Components
- Arduino Uno
- 4 × HX711 Amplifier Modules
- 4 × Metallic Foil Strain Gauges
- Wheatstone Bridge Circuit
- Push Button
- Connecting Wires

## Software Requirements
- Arduino IDE
- HX711 Library

## Circuit Diagram
<img width="1408" height="768" alt="image" src="https://github.com/user-attachments/assets/a0b7ee96-121f-4a22-810b-38c7cb477106" />



## How It Works
The Arduino IDE program for this project is designed using a simple embedded system architecture that continuously acquires, processes, and displays strain data 
from the HX711 amplifier module. The code mainly consists of three sections: initialization, sensor data acquisition, and event handling. During system startup, 
the Arduino initializes serial communication, configures the HX711 amplifier, sets the calibration factor, and performs an initial tare operation to establish 
a zero reference point. The main loop continuously reads strain values from the HX711 module and displays the processed output through the serial monitor. 
A push button is integrated into the system for performing re-tare or reset operations whenever required. The program architecture ensures real-time monitoring, 
stable sensor readings, and easy interaction between the hardware components and the microcontroller.

## Results
before tare: <img width="1108" height="370" alt="image" src="https://github.com/user-attachments/assets/47e446f5-e9b4-4e25-a10d-53af3ad8266d" />
after tare: <img width="1108" height="319" alt="image" src="https://github.com/user-attachments/assets/1ed62513-e7e8-4201-abb8-974c0c490cff" />

