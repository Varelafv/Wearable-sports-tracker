#🏃‍♂️ Wearable Sports Tracker

This project was created as a learning exercise in developing a new electronic product, from concept to prototype.

The goal is to design a smart wearable device — integrated into a vest — that can monitor an athlete’s performance and provide useful data to improve training results.

* 🎯 Project Objectives 

	Learn and practice the full process of hardware and firmware development.

	Define and implement key features and sensors for performance tracking.

	Build a compact and efficient PCB suitable for integration into sports gear.

	Collect, store, and analyze biometric and movement data from the user.

*  ⚙️ Planned Features

	Motion tracking using IMU sensors (accelerometer, gyroscope, magnetometer).

	Heart rate and SpO₂ monitoring using optical sensors (MAX30102).

	GPS positioning for speed, distance, and route tracking.

	Data logging to SD card (CSV format).

	Wireless communication via Bluetooth Low Energy (BLE).

	Optional modules depending on sport type or activity.

🔩 Hardware Overview

	MCU: STM32WB5MMG (Bluetooth Low Energy + Cortex-M4)

	IMU: ICM-20948 or MPU-9250 (9-axis)

	Heart Rate Sensor: MAX30102

	GPS Module: NEO-M8N

	Storage: microSD module (SPI interface)

	Power: Li-Po battery + TP4056 charger + 3.3V regulator

🧠 System Concept

	Sensors continuously collect movement and physiological data.

	The MCU processes and stores data on a microSD card.

	Data can later be transferred via BLE to a computer or smartphone for analysis.

	Different firmware modes may adapt tracking depending on the type of sport.

📄 Next Steps

	Define detailed specifications for each module.

	Create the first PCB prototype.

	Develop embedded firmware using STM32CubeIDE.

	Build a simple data visualization tool (Python or mobile app).

📘 Datasheet & Documentation

	Detailed component datasheets and system diagrams will be added in future updates on Datasheet .
