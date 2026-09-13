# STM32F405 Flight Controller PCB

A custom flight controller PCB designed in KiCad 10 using the STM32F405 microcontroller.

This project focuses on embedded systems, PCB design, and drone electronics.

## Project Overview

The board includes:

- STM32F405 microcontroller
- ICM-20602 6-axis IMU
- BMP280 barometric pressure sensor
- AMS1117-3.3 voltage regulator
- USB interface
- ESC signal connections
- RC receiver connections
- Reset and boot controls
- Power filtering and decoupling capacitors

## Tools Used

- KiCad 10
- Embedded C
- Git
- GitHub

## PCB Design

### Schematic


<img width="1000" height="500" alt="Screenshot 2026-09-13 175106" src="https://github.com/user-attachments/assets/9bd7f989-d828-44a0-a533-fc272aa1cd14" />

### PCB Layout

<img width="400" height="500" alt="Screenshot 2026-09-13 175144" src="https://github.com/user-attachments/assets/5a6af25d-1641-4857-89e4-876dbc2d0088" />


### 3D View

<img width="500" height="515" alt="Screenshot 2026-09-13 175219" src="https://github.com/user-attachments/assets/5147a14c-6916-4006-ac74-f4afab4017ea" />


## Design Features

- STM32F405-based flight controller
- Dedicated ground plane
- Separate power and signal routing
- Decoupling capacitors near IC power pins
- IMU placed close to the microcontroller
- Power filtering for sensitive components
- Design-rule checking using KiCad

## Project Status

- [x] Schematic design
- [x] Component selection
- [x] Footprint assignment
- [x] PCB placement
- [x] PCB routing
- [x] Ground-zone filling
- [x] Design-rule checking
- [x] Gerber generation
- [ ] PCB manufacturing
- [ ] Hardware testing

## Reference

This project is inspired by PCB design learning material from Phil’s Lab.

## Disclaimer

This is a learning and development project. The board has not yet been flight-tested and should not be used in a real drone.

## Author

Sanchit Agarwal
