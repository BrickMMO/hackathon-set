## Infinity Gauntlet

<img src="images/infinity-gauntlet-box.png" style="height: 500px;"> 

> <small>LEGO (n.d.). LEGO Nano Gauntlet. Retrieved February 12 2024, from [https://www.lego.com/en-ca/product/nano-gauntlet-76223](https://https://www.lego.com/en-ca/product/nano-gauntlet-76223)</small>

### Description

Tony Stark's [Infinity Gauntlet](https://www.lego.com/en-ca/product/nano-gauntlet-76223) from Avengers Endgame. We will add lights in the infinity stones and a motor in the base to make the whole hand spinning.

<img src="images/infinity-gauntlet.png" style="width: 624px;"> 

> <smalll>LEGO (n.d.). LEGO Nano Gauntlet. Retrieved February 12 2024, from [https://www.lego.com/en-ca/product/nano-gauntlet-76223](https://https://www.lego.com/en-ca/product/nano-gauntlet-76223)</small>

This interaction will only require a motor and lights.


### Requirements

The first output will be attached to an EV3 servo motor. The second port will be connected to EV3 Lights.

<img src="media/ev3/servo-motor.jpeg" height="200">
<img src="media/power-functions/lights.jpeg" height="200">

## Pseudocode

This would be the code for the Hand rotation that would be 2 rotations, that will be completed in 1 minute:

```pseudocode
While True

If status == "on"

If counter == 0
    Start motor slow clockwise

Else if counter == 30
    Stop motor

Else if counter == 35
    Start motor slow counter-clockwise

Else if counter == 60
    Stop motor
```

And for the lights in the Infinity Stones, this would go as follow:

```pseudocode
While True

If status == "on"

If counter == 0
    Turn on lights

If counter == 100
    Turn off lights
```

## Port Settings

Rotating hand Stauts: Can be set "on" or "off". (Rotate back and forth constantly)

Lights Status: Can be sent to "on" or "off". (The Infinity Stones will light up and turn off automatically)

[&#10132; Back to Hackathon](/hackathon-set/)

---

<a href="https://brickmmo.com">
<img src="https://brickmmo.com/images/brickmmo-logo-horizontal.jpg" width="100">
</a>
