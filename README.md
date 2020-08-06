# MICRO-SERVO-BOT

![](https://github.com/GUSAC-GIT/MICRO-SERVO-BOT/blob/master/micro-images/micro1.jpg)


> MICRO-SERVO-BOT

---

### Contents


- [Components](#components)
- [Description](#description)
- [Team Info](#team-info)


---

## Components

- Unity 3d software
- Arduino mini pro 5V/16MHz
- 4 micro servos (180degrees)
- 4 22k potentiometer
- NmH Battery 4.8V
- Wires, Button, Switch
- Balsa wood, Metal, Plastic
- Zip Ties and Glue



[Back To The Top](#micro-servo-bot)




## Description

The Micro Servo Robot can be used for both electronics and mechanical applications. It is designed to respond in micro-scale. Being said, it is more efficient for different motion trajectories which are applied according to the requirements

Teach mode: After a reset the robot arm follows the teach in arm while simple mapping the analog inputs every 25ms to the servo motors. Pressing the button stores each servo position in a array

Play mode: Double press the button switch to play mode. The sketch reads the array step by step and and moves the robot arm. For cool loocking movements i added a routine calculates different micro steps for each servo to have moving start and end sync on all axis. Also added a ramp for soft increase/decrease velocity. Shorter travel distances the robot does slow, longer distances with faster speed. Its all about timing so my thoughts in this moment




[Back To The Top](#micro-servo-bot)

---



## Team Info

Gusac Projects Team

[Back To The Top](#micro-servo-bot)

