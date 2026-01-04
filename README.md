# SCADA_system_using_LabVIEW
Introduction
The SCADA Solar Rooftop System project aims to build a smart monitoring and control system for rooftop solar power using SCADA technology.
It integrates hardware (PV, Inverter, Battery, Data Logger, Raspberry Pi) and software (SCADA/HMI, Cloud) to monitor, control, and optimize solar energy operations.

Key Benefits:

Reduce electricity costs.
Utilize clean & renewable energy.
Real-time monitoring and predictive maintenance.
Increase energy independence for households and businesses.
System Architecture
The system is divided into 3 SCADA levels: scada

Field Level

PV Array (solar panels)
Combiner Box, Fuse, AC Breaker
Battery Bank (energy storage)
Weather Station (measures irradiance, temperature, wind, humidity)
Inverter (DC → AC conversion)
Charge Controller
Control Level

Inverter (PWM, MPPT control, voltage/current monitoring, SCADA communication)
Charge Controller (controls charging process)
Data Logger (can trigger safety cut-offs)
Supervisory Level

Plant SCADA (Server + HMI)
Raspberry Pi & Data Logger (data acquisition and transmission)
Dashboard (real-time monitoring, alarms, performance analysis)

