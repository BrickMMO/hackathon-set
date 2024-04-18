## 11 Lunar Lander

![11 Lunar Lander](images/lunar-lander.png)

> <small>LEGO (n.d.). LEGO 11 Lunar Lander. Retrieved February 12, 2024, from [https://www.lego.com/en-ca/product/nasa-apollo-11-lunar-lander-10266](https://www.lego.com/en-ca/product/nasa-apollo-11-lunar-lander-10266)</small>

### Module Description

The official [11 Lunar Lander](https://www.lego.com/en-ca/product/nasa-apollo-11-lunar-lander-10266) LEGO® set has a built in interactive feature. Lunar Lander set already has a lever to lift the cabin manually. This module will lift Lunar Lander automatically every 10 minutes and light it up.

![11 Lunar Lander](images/lunar-lander-interactive.png)

> <small>LEGO (n.d.). LEGO 11 Lunar Lander. Retrieved February 12, 2024, from [https://www.lego.com/en-ca/product/nasa-apollo-11-lunar-lander-10266](https://www.lego.com/en-ca/product/nasa-apollo-11-lunar-lander-10266)</small>

This interaction can be automated through the motor, lights and a converter.

### Sensors, Motors and Ports

For this to work, we’ll need to use EV3 motor, LED lights, and a converter. Lunar Lander will require two output ports on an EV3 hub to connect a motor and a converter with lights.

<img src="./images/sensor.png" height="200">
<img src="./images/lights.png" height="200">
<img src="./images/converter.png" height="200">

### Variables/ Settings
Status: Can be set to "on" or "off". When on Lunar Lander will lift every ten minutes and the lights will be on while lifted. Interval can be changed.

<img src="./images/code.png" height="200">

## Pseudocode

```pseudocode
While true
    if status == on
        if counter == 0 
            switch on lights
            start motor slow clockwise 
            //It lifts up
        else if counter == 10
            stop motor
            // comes down 
            switch off lights
```

[&#10132; Back to Hackathon](/hackathon-set/)

---

<a href="https://brickmmo.com">
<img src="https://brickmmo.com/images/brickmmo-logo-horizontal.jpg" width="100">
</a>
