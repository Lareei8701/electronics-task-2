## electronics-task-2
# 4-Servo Sweep and Hold – Arduino circuit using tinkercard

# Description
This Arduino sketch controls 4 servo motors connected to pins 8, 9, 10, and 11.  
Each motor performs a full sweep from 0° to 180° and back to 0°, then all motors are set to 90° and stay there.

# Components
- Arduino Uno (or compatible board)  
- 4x Servo motors   
- wires
  
# How It Works
1. All 4 servos start together.
2. Sweep from 0° → 180° → 0°.
3. Motors stop and hold at 90°.

# Library Used
- [Servo.h](https://www.arduino.cc/reference/en/libraries/servo/)

# Pin Configuration
| Servo | Pin |
|-------|-----|
| 1     | 9   |
| 2     | 8   |
| 3     | 10  |
| 4     | 11  |
