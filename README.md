# Industrial Gas Safety Monitoring System

## Overview
An IoT-based industrial safety system designed to detect hazardous gas leaks and trigger automated safety responses in real time.

## Features
- Real-time gas leak detection
- SMS alerts using GSM module
- Automatic exhaust fan activation
- Buzzer-based local alarm
- Cloud monitoring dashboard using ThingSpeak
- Continuous industrial environment monitoring

## Hardware Components
- ESP32
- MQ-2 Gas Sensor
- MQ-135 Gas Sensor
- GSM Module
- Relay Module
- Buzzer
- Exhaust Fan
- Power Supply

## Working
The system continuously monitors gas concentration levels using MQ series sensors.

When gas levels exceed a predefined threshold:
1. Buzzer alarm is activated
2. SMS alert is sent
3. Exhaust fan turns ON automatically
4. Data is uploaded to ThingSpeak

## Applications
- Industrial Safety
- Chemical Plants
- Manufacturing Units
- Warehouses
- Laboratories

## Project Status
Prototype Completed

## Author
Awanish Mishra
