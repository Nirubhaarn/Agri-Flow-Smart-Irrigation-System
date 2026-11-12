# Agri-Flow-Smart-Irrigation-System
STM32 Based Smart Irrigation System using Soil Moisture Sensor
# 🌱 Agri Flow & Smart Irrigation System

## Project Overview
Agri Flow is an STM32-based automatic irrigation system that monitors soil moisture and controls a DC water pump through a relay module.

The system automatically switches ON the water pump when the soil is dry and switches OFF when sufficient moisture is detected.

## Objectives
- Monitor soil moisture continuously.
- Use an STM32 microcontroller to process sensor readings.
- Control the water pump automatically using a relay.
- Reduce water wastage and manual effort.
- Improve irrigation management.

## Hardware Components
- STM32 Development Board
- Soil Moisture Sensor
- Relay Module
- DC Water Pump
- Power Supply
- Connecting Wires
- Water Storage Tank

## Software and Tools
- Embedded C
- STM32 HAL Library
- STM32CubeIDE
- Proteus Design Suite

## Working Principle
1. The soil moisture sensor measures the soil moisture level.
2. The sensor sends the reading to the STM32 controller through ADC.
3. The controller compares the reading with a predefined threshold.
4. The relay activates the pump when the soil is dry.
5. The pump switches OFF when sufficient moisture is detected.
6. The process repeats continuously.

## Pin Configuration
| Component | STM32 Pin |
|---|---|
| Soil Moisture Sensor | PA0 (ADC) |
| Relay Module | PA1 (GPIO) |

Threshold value: 2000 (12-bit ADC).

## Project Files

- [Project Report](Agri-Flow-Project-Report.docx)
- [Project Presentation](Agri-Flow-Presentation.pptx)

## Project Demonstration Videos

- [Proteus Simulation Video](Proteus-Simulation.mp4)
- [Hardware Implementation Video](Hardware-Implementation.mp4)

## Team Members

1. R.N. Nirubhaa
2. P. Mani Vardhan
3. G. Dhuranth Reddy
4. V. Suganya

## Project Guides

- External Guide: Mr. Pavan Kumar E
- Internal Guide: Mrs. Loyola Jasmine

## Applications
- Agricultural fields
- Home gardens
- Greenhouses
- Plant nurseries
- Small-scale farming

## Future Scope
- IoT-based remote monitoring
- Weather sensor integration
- Mobile application
- Solar power integration
- Multiple soil moisture sensors

## Conclusion
Agri Flow demonstrates an automatic irrigation system using STM32, soil moisture sensing, relay control and a DC water pump. It aims to reduce unnecessary water usage and manual monitoring while supporting smart agriculture.

---
**Project:** Mini Project – Electronics and Communication Engineering  
**Academic Year:** 2025–2026
