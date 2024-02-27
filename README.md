<div align="center">

# Raspberry Pi Pico Servo Driver

Servo driver for raspberry pi pic (pico c/c++ sdk projects).
this code libraray developed as part of my main project "FCP" (autonomous flight controller project),
it can be used for other projects thats need servo control.

Hardware:

[Raspberry Pi Pico](https://www.raspberrypi.com/products/raspberry-pi-pico/) •
regular 9g servos

</div>

<div>

# Example Of Use

```c++
SERVOdriver roll_servo;
const uint roll_servo_pin = 7;
roll_servo.pwmservo_init(roll_servo_pin);
roll_servo.pwmservo_write_micros(roll_servo_pin, (roll_angle));
```

</div>
