# SCADA System for Solar Power Generation using LabVIEW

## 📌 Overview
This project focuses on the design and implementation of a **SCADA (Supervisory Control and Data Acquisition) system** for an **off-grid rooftop solar power generation system** using **LabVIEW**.  
The system enables real-time monitoring, data acquisition, visualization, logging, and supervisory control to improve operational efficiency, reliability, and system performance.

## 🎯 Objectives
- Monitor real-time electrical parameters of a solar power system
- Acquire data from field devices via industrial communication protocols
- Visualize system status through an intuitive HMI developed in LabVIEW
- Log historical data for analysis and performance evaluation
- Support supervisory control to enhance system reliability

## 🏗️ System Architecture
The SCADA system is structured into three main levels:

### 1. Field Level
- Solar PV panels
- Hybrid / Off-grid inverter
- Battery Energy Storage System (BESS)
- Weather station (PV Met 75)
- Smart power meters (SDM630, SDM120)
- Sensors for voltage, current, power, temperature, and solar radiation

### 2. Control Level
- RTU / Modbus RTU to Modbus TCP Converter
- Raspberry Pi used as Data Logger / Data Manager
- Ethernet Switch & Router
- SMA Communication Gateway

### 3. Monitoring Level
- SCADA Server / Personal Computer
- LabVIEW-based HMI
- Real-time charts, alarms, and control panels

## 🔌 Communication Protocols
- **Modbus RTU (RS485)** for field devices
- **Modbus TCP/IP** for Ethernet-based communication
- Data conversion between RTU and TCP using protocol converters

## 🖥️ SCADA Features
- Real-time monitoring of voltage, current, power, energy, and system status
- Graphical visualization (charts, indicators, dashboards)
- Alarm and fault indication
- Data logging for historical analysis
- Remote supervisory control
- User-friendly HMI developed in LabVIEW

## 🛠️ Tools & Technologies
- **Software**:  
  - LabVIEW  
- **Hardware**:  
  - Solar PV Panels  
  - Hybrid / Off-grid Inverter  
  - PV Met 75 Weather Station  
  - SDM630 / SDM120 Power Meters  
  - Raspberry Pi 3  

  - RTU/TCP Converter  
- **Communication**:  
  - Modbus RTU  
  - Modbus TCP/IP  

## 📊 Applications
- Rooftop solar power monitoring
- Off-grid solar energy systems
- Smart energy management
- Educational and research purposes
- SCADA training and demonstration systems

## 📁 Project Structure


<img width="735" height="676" alt="image" src="https://github.com/user-attachments/assets/16ebff75-8ce2-49a7-accb-96b40e5b7d2a" />



## 👨‍💻 Team Members
- Nguyễn Hữu Hiệp  
- Nguyễn Minh Ngọc Huy  
- Lê Công Khoa  
- Quý Tâm Anh  

## 👨‍🏫 Supervisor
- **Dr. Lê Quốc Huy**  
Faculty of Advanced Science and Technology  
University of Science and Technology – The University of Danang

## 📅 Date
- September 2025

## 📜 License
This project is developed for **academic and educational purposes**.

