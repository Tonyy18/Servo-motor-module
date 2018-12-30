# Raspberry Pi Servo motor module
Control servo motor with raspberry pi and python

Uses <a href="https://pypi.org/project/RPi.GPIO/">RPi.GPIO</a> and time libraries.

<h2>Constructor</h2>
Create new servo instance

```
import Servo

servo = Servo.Init(7)
```
Provide your control/pwm pin in the constructor

<h2>Run()</h2>
Use this method to control your motor by degree<br />
Accepts degrees between 0 and 180

```
import Servo

servo = Servo.Init(7)
servo.run(90)
```
