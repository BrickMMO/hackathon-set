## Motorized Lighthouse

![Motorized Lighthouse](./images/motorized-lighthouse1.png)

> <small>LEGO (n.d.). LEGO Motorized Lighthouse. Retrieved August 7, 2023, from [https://www.lego.com/en-ca/product/motorised-lighthouse-21335](https://www.lego.com/en-ca/product/motorised-lighthouse-21335)</small>


### Description

The light for the [Motorized Lighthouse](https://www.lego.com/en-ca/product/motorised-lighthouse-21335) set can be turned on. 
This module will turn on the light and spin it 360 
degrees every 5 minutes. It will run for 5 minutes.

![Motorized Lighthouse](./images/motorized-lighthouse2.png)

> <small>LEGO (n.d.). LEGO Motorized Lighthouse. Retrieved August 7, 2023, from [https://www.lego.com/en-ca/product/motorised-lighthouse-21335](https://www.lego.com/en-ca/product/motorised-lighthouse-21335)</small>


### Requirements

The only output port will be attached to an EV3 servo motor. 

<img src="./images/freight-sensor.png" height="200">

Motorized Lighthouse will require one output port on an EV3 hub to connect a motor.

<img src="./images/motorized-lighthouse-port.png" height="200">


### Variables/Settings

Status: Can be set to "on" or "off". When on, the light will turn on and rotate 360 degrees
Interval can be changed.

<img src="./images/motorized-lighthouse-settings.png" height="100">


## Pseudocode

```pseudocode
While True
    If status == "on"
        If counter == 0
            Start motor clockwise
Turn light on
        Else If counter == 5
            Stop motor
Turn light off
        Else If counter == 10
           counter = 0
//restart loop
```

[&#10132; Back to Hackathon](/hackathon-set/)

---

<a href="https://brickmmo.com">
<img src="https://brickmmo.com/images/brickmmo-logo-horizontal.jpg" width="100">
</a>
