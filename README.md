# PWMServo
Control RC Servo motors with interrupt-resilient PWM

This fork is done from former [PaulStoffregen/PWMServo](https://github.com/PaulStoffregen/PWMServo)'s repository.  
The last commit dated from 2018/07/16.  
  
I wanted to add few methods to the PWMServo object:
* writeMicroseconds() to be able to get more precise positionning
* setPeriod() because RC servo accept a period from 10ms to 22ms with a default usually set to 20ms. Being able to reduce the period could increase responsivness for critical applications.
