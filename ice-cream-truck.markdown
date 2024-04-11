## 6 Ice Cream Truck

![6 Ice Cream Truck](images/ice-cream-truck.png)

><small>LEGO (n.d.). LEGO 6 Ice Cream Truck. Retrieved Frebrary 12, 2024, from [https://www.lego.com/en-ca/product/ice-cream-truck-41715](https://www.lego.com/en-ca/product/ice-cream-truck-41715)</small>

### Description

The Ice-Cream Truck will drive around Lego City and stop for people who want to buy ice cream. It will use a motor to create motion, cameras to detect perdestrians, LED lights to simulate color, and audio outputs to play music according to the presence of the perdestrians.

![6 Ice Cream Truck](images/ice-cream-truck2.png)

### Requirements

The Ice-Cream Truck will require 4 outputs on an EV3 brain.

![6 Ice Cream Truck](images/sensor-and-motor.png)

## Pseudocode

1) Psuedo code for music:
```pseudocode
IF camera detects human THEN{
    Play music
    Turn on lights
}
else{
    stop audio and lights
}
```

2) Pseudo code for motion:
```pseudocode
if distance sensor detects obstructions THEN{
    Stop motor
}
else{
    run motor
}
```

[&#10132; Back to Hackathon](/hackathon-set/)

---

<a href="https://brickmmo.com">
<img src="https://brickmmo.com/images/brickmmo-logo-horizontal.jpg" width="100">
</a>
