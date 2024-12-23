
## Overview
The Bluetooth Controlled Car project involves designing and implementing a car that can be controlled wirelessly using a smartphone or computer via Bluetooth. The system is built using Arduino, a Bluetooth module, and motor driver circuitry to enable smooth and responsive navigation.

## Features
- **Wireless Control:** Operated via a mobile app or PC using Bluetooth communication.
- **Easy to Build:** Utilizes commonly available components.
- **Real-time Navigation:** Provides responsive control for smooth driving.
- **Customizable:** Supports modifications for additional features like obstacle avoidance or speed control.

## Hardware Design
### Components
- **Microcontroller:** Arduino Uno to process commands and control the motors.
- **Bluetooth Module:** HC-05 for wireless communication.
- **Motor Driver IC:** L293D to control motor operations.
- **Chassis:** A robust frame for mounting motors and components.
- **Motors:** DC motors for movement.
- **Power Supply:** Battery pack to power the system.

### Assembly
1. Connect the HC-05 Bluetooth module to the Arduino.
2. Interface the L293D motor driver IC with the Arduino and motors.
3. Mount all components onto the chassis.
4. Ensure proper wiring for the power supply and connections.

## Software Design
### Programming
- **Control Logic:** Arduino processes commands received from the Bluetooth module and sends appropriate signals to the motor driver IC.
- **Command Protocol:** Predefined commands (e.g., `F` for forward, `B` for backward) are used for navigation.

### Tools and Libraries
- Arduino IDE for coding.
- Serial communication library for handling Bluetooth commands.

### Interface
- Control the car using a smartphone app (e.g., Bluetooth Terminal or custom app).

## Implementation
1. **Prototyping:** Assemble the hardware components on a breadboard for initial testing.
2. **Coding:** Upload the Arduino sketch with motor control and Bluetooth communication logic.
3. **Testing:** Verify functionality by sending commands via Bluetooth.
4. **Final Assembly:** Mount all components securely on the car chassis.

## Future Enhancements
- Add obstacle detection using ultrasonic sensors.
- Implement speed control for smoother driving.
- Integrate GPS for location tracking.
