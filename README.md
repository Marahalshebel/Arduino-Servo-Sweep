# Arduino-Servo-Sweep
An Arduino-based multi-servo control system that synchronizes the movement of four servo motors using the Servo library. The project demonstrates coordinated motion control through the Sweep algorithm followed by precise positioning at 90°, providing a foundation for robotic arm and automation applications.

## Overview
The system uses four servo motors connected to an Arduino Uno. All motors perform the Sweep movement simultaneously by rotating from **0° to 180°** and back to **0°**. After completing the movement, each servo is positioned at **90°** and remains fixed.
The project was programmed using Arduino IDE and tested in Tinkercad.


## Technologies Used
- Arduino Uno
- Arduino IDE
- Servo Library
- Tinkercad


## Components
- Arduino Uno
- 4 × Servo Motors
- Jumper Wires


## Project Files
```
4-Servo-Motors-Sweep-Control/
│
├── Servo_Sweep.ino
├── Circuit.png
├── README.md
└── Arduino.mp4
```

| File | Description |
|------|-------------|
| [Servo_Sweep.ino](Servo_Sweep.ino) | Arduino program that controls the four servo motors |
| [Circuit.png](Circuit.png) | Circuit wiring diagram created in Tinkercad |
| [README.md](README.md) | Project documentation |
| [Arduino.mp4](Arduino.mp4) | showing the servo motors during execution |


## Circuit Connections
| Servo Motor | Signal Pin |
|-------------|------------|
| Servo 1 | D8 |
| Servo 2 | D7 |
| Servo 3 | D6 |
| Servo 4 | D9 |

### Power Connections
- All VCC pins → 5V
- All GND pins → GND


## Features
- Control four servo motors simultaneously.
- Implement the Arduino Sweep example.
- Move all servo motors smoothly together.
- Automatically position all motors at **90°** after the Sweep movement.
- Simple and easy-to-understand Arduino implementation.


## How It Works
1. Initialize the Servo library.
2. Attach each servo motor to its assigned digital pin.
3. Execute the Sweep movement for all four servo motors.
4. Move every servo motor to **90°**.
5. Keep the motors fixed at the final position.


## Output
- All four servo motors rotate together from **0° to 180°**.
- The motors return from **180° to 0°**.
- Finally, all servo motors move to **90°** and remain in that position.


## Simulation

### Circuit
```
ScreenshotArduino.png
```

### Output



