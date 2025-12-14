---
title: "Projects"
permalink: /projects/
author_profile: true
---

## Flute Musician
'Flute Musician' was the final project for my mechatronics course (ME 4405). The motivation for this project was:
> Can we replicate the embouchure technique and
synchronize with physical key combinations to play a
flute using mechanical design and mechatronics?

There were 4 main subsystems for this robot:​
1. **Mouthpiece & Pneumatics**: provides airflow to the flute via a 3D-printed mouthpiece to produce sound. Also includes a bullet valve to replicate tongue articulation.
2. **Key Articulation**: actuate keys via cable-drive from servos to execute the correct fingerings. The servos are located on linear rails to allow for in-situ adjustment of servo positioning.
3. **Flow Control**: stepper motor adjusts flow for each note depending on pre-set, experimentally-derived steps to produce the best tone.
4. **Sensing & Feedback**: microphone monitors output frequency of the flute and executes tuning sequence.

### Component Overview
| Component                | Purpose                                      | Part Number               | Part Type     |
|--------------------------|----------------------------------------------|---------------------------|---------------|
| Servo (9x)               | Flute key actuation                          | MG996R                    | Actuator      |
| Servo (1x)               | Flow valve actuation                         | MG996R                    | Actuator      |
| Flow Control Valve       | Flow control from compressed air tank        | McMaster 3019N124         | Regulator     |
| Bullet Valve             | Flow articulation (simulating mouth)         | MV310                     | Actuator      |
| 24 V DC Power Supply     | Power supply                                 | NA                        | Power         |
| Step Down Buck Converter | 24V to 5V step down                          | EA50                      | Power         |
| Relay Switch             | Bullet valve control                         | Aediko 5V Relay Module   | Driver Board  |
| PWM Servo Driver         | Servo control                                | PCA9685                   | Driver Board  |
| Microphone               | Frequency monitoring                         | MAX9814                   | Sensor        |
| Ultrasonic Sensor        | Start/stop flow based on user input          | HC-SR04                   | Sensor        |

### System Snapshot
![System Snapshot](/images/Slide3.jpg)

### Mary Had a Little Lamb
<video width="640" controls>
  <source src="/files/Mary_Had_A_Little_Lamb.mp4" type="video/mp4">
</video>

