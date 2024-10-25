# ICM42688_MotionTracking
Description: This project is designed to build an interface for the ICM-42688 6-axis motion sensor, which can collect data in  of accelerometer, gyroscope, and temperature readings by SPI communication. It is designed for applications in motion tracking, vibration analysis, and environmental monitoring, this project reads sensor data and outputs it in a serial CSV format for easy logging and analysis.

Features
SPI Communication: Interface with the ICM-42688 sensor using SPI.
Data Collection: Reads acceleration (X, Y, Z), gyroscope (X, Y, Z), and temperature data.
Configurable Full-Scale Range: Set accelerometer and gyroscope sensitivity as needed.
Real-Time Serial Output: Displays data in CSV format for easy logging or integration with other analysis tools.

Hardware Requirements
ICM-42688 Sensor
Microcontroller - STM32 NUCLEO-G474RE
Serial monitor - Arduino Serial Monitor for viewing data

Getting Started
Connect the ICM-42688 sensor to the STM32 NUCLEO-G474RE via the SPI bus.
Upload the provided code to your microcontroller.
Open the serial monitor to view real-time sensor data.
