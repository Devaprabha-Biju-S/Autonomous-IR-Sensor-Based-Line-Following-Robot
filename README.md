# Autonomous IR Sensor-Based Line Following Robot

An Arduino-based autonomous robot that uses infrared (IR) sensors to detect and follow a line on the ground. The robot can move forward, turn left or right, and stop at intersections based on sensor input.

## 🚀 Features
- Follows a black line on a white surface using IR sensors
- Can automatically turn left/right at curves
- Stops when both sensors detect black (e.g., end of track or obstacle)
- Powered by an L293D motor driver for dual-motor control

## 🧠 Technologies Used
- Arduino UNO
- L293D Motor Driver
- IR Sensors (Left and Right)
- DC Motors (x2)
- Arduino IDE (C++)

## 🛠️ Circuit Connections

| Component         | Arduino Pin |
|------------------|-------------|
| IR Sensor Left    | 2           |
| IR Sensor Right   | 4           |
| Motor Enable A    | 5           |
| Motor Input 1     | 6           |
| Motor Input 2     | 7           |
| Motor Enable B    | 8           |
| Motor Input 3     | 9           |
| Motor Input 4     | 10          |


## 🔄 Working Logic

- **Forward:** Both sensors detect white → move forward
- **Turn Right:** Right = black, Left = white → turn right
- **Turn Left:** Left = black, Right = white → turn left
- **Stop:** Both sensors detect black → stop motors

## 🧪 Getting Started

1. Connect the circuit as per the pin configuration.
2. Upload the `.ino` or `.c` file to your Arduino board via Arduino IDE.
3. Place the robot on a track with a black line on a white surface.
4. Power it on and watch it follow the path autonomously!

## 🧑‍💻 Author

Devaprabha Biju S.

---

Feel free to fork, modify, or suggest improvements to the project.


