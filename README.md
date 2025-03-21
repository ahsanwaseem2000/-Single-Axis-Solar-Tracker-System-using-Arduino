# Single Axis Solar Tracker System using Arduino

This project demonstrates the development of a **Single Axis Solar Tracker System** using **Arduino**. The system follows the sun's path throughout the day to maximize the energy output from a solar panel. It uses **Light Dependent Resistors (LDRs)** to detect sunlight intensity and adjusts the position of the solar panel with a **servo motor**.

## **Project Overview**

Solar power is a clean, renewable source of energy. However, to maximize the efficiency of a solar panel, it must always face the sun. This project aims to design a **single-axis solar tracker** that adjusts the position of a solar panel based on the movement of the sun.

### **Key Features:**
- **Arduino UNO**: Used as the central microcontroller to process the sensor data and control the servo motor.
- **LDR (Light Dependent Resistor)**: Detects the intensity of sunlight and sends data to the Arduino.
- **Servo Motor**: Moves the solar panel based on the LDR sensor data.
- **Solar Panel**: The photovoltaic panel generates energy, which is aligned with the sun using the servo motor.
- **Tinkercad Simulation**: The circuit and design are simulated on Tinkercad for testing.

### **Objective**
- To design and implement a cost-effective **single-axis solar tracker** that maximizes solar panel efficiency.
- To demonstrate how simple sensors and a microcontroller can work together to create a functional solar tracking system.

## **Tools Used**

1. **Arduino UNO**: The microcontroller board used to process sensor data and control the system.
2. **Servo Motor**: Controlled by PWM to rotate the solar panel.
3. **LDR (Light Dependent Resistor)**: Used to measure the intensity of sunlight.
4. **Solar Panel**: The primary energy source.
5. **Tinkercad**: An online platform used to simulate the circuit and design.

## **System Design**

The system continuously monitors sunlight intensity using two LDRs. Based on the difference in light intensity, the **Arduino** sends a signal to the **servo motor** to move the solar panel and keep it aligned with the sun.

### **Circuit Diagram**
You can simulate the system on **Tinkercad** using the following components:
- **Arduino UNO**
- **2 LDRs** connected to analog pins of the Arduino
- **Servo motor** connected to a PWM pin
- **Solar panel** (simulated in the design or actual hardware)


