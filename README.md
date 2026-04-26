# Arduino Line Follower Robot 🚗

This project is a simple line-following robot using an Arduino Uno.
The robot follows a black line and ignores the white surface.

## Components

* Arduino Uno
* 2 IR sensors
* Motor driver (L298N)
* 2 DC motors
* Wheels and chassis
* Battery pack

## How It Works

The robot uses two IR sensors to detect the line:

* Black surface → detected as LOW
* White surface → detected as HIGH

Based on the sensor readings:

* Both sensors on black → move forward
* Left sensor on black → turn left
* Right sensor on black → turn right
* No line detected → stop

## Arduino Code

Upload the `.ino` file to your Arduino board.

## Connections

* Left sensor → Pin 2
* Right sensor → Pin 3
* Motor driver pins connected to Arduino pins 5, 6, 7, 9, 10, 11

## Future Improvements

* Add PID control for smoother movement
* Use more sensors for better accuracy
* Add obstacle detection

## Author

Your Name
