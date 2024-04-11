## London Architecture

![London Architecture](images/london-architecture.jpeg)

> <small>LEGO (n.d.). LEGO London #21034. Retrieved February 12, 2024, from [https://www.lego.com/en-ca/product/london-21034](https://www.lego.com/en-ca/product/london-21034)</small>

### Description

The official [London Architecture ](https://www.lego.com/en-ca/product/london-21034) LEGO® set has a built in intaractive feature. The London Eye will turn at a steady pace with lights. The London Bridge will sense movement of boats and will open until sensor stops detecting.  Will also change traffic lights accordingly. If possible, add a clock on Big Ben. It will chime every hour. 

The LEGO Group. (n.d.). London™. Retrieved 2024, from 
https://www.lego.com/en-ca/product/london-21034.

![London Architecture](images/londoncity.png)

> <smalll>LEGO (n.d.). LEGO London Architecture. Retrieved February 12, 2024, from [https://www.lego.com/en-ca/product/london-21034](https://www.lego.com/en-ca/product/london-21034)</small>

### Requirements

This interaction will only require a large EV3 motor:

<img src="media/ev3/servo-motor.png" height="200">

### Port Settings

Status: Can be set to "on" or "off". 
Port 1: When on the wheel will spin, and lights turn on.
Port 2: when on, the bridge will open. 
Port 3: when on, clock will make a sound. When off, it will stop.

### Port JSON

Wheel: stop, start for 1 minute.
Bridge: open while no movement at a certain 
distance, close.
Clock: chime every hour

## Pseudocode

In this example,

```pseudocode
1. London eye:
    When switch is on:
        Turn motor on
    When witch is off:
        Turn motor off

2. London bridge:
    If sensor detects motion within close distance
        Open.
    Close when movement is gone.
    Else 
        Stay closed.

3. Clock:
    If time is the hour in standard time
    Chime amount of times equal to hour
```


[&#10132; Back to Hackathon](/hackathon-set/)

---

<a href="https://brickmmo.com">
<img src="https://brickmmo.com/images/brickmmo-logo-horizontal.jpg" width="100">
</a>
