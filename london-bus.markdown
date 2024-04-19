## London bus
![12 Grimmauld Place](images/london-bus.png)

> <small>LEGO (n.d.). LEGO 40220 London Bus , from [https://www.lego.com/en-ca/product/london-bus-40220](https://www.lego.com/en-ca/product/london-bus-40220)</small>

### Description

The official [London Bus](https://www.lego.com/en-ca/product/london-bus-40220) London Bus is our module so basically when the bus goes from one stop to another with the use of sensor the bus doors will automatically open 10 seconds and if passengers are not there the bus will automatically close its doors. Apart from this one feature we would like to add is that when the moving vehicle passes or comes in front of the bus to a certain distance of 10 meters and so the bus will automatically honk.

![London bus](images/london bus.png)

> <small>LEGO (n.d.). LEGO London Bus, from [https://www.lego.com/en-ca/product/london-bus-40220](https://www.lego.com/en-ca/product/london-bus-40220)</small>

This motion will be connected to a motor so the interaction can be automated.

### Requirements

This interaction will only require a large EV3 motor and the EV3 hub:

<img src="images/motor.jpg" height="200">

## Pseudocode

In this example, the location is only available when recently requested:

```pseudocode
Door_open_Time: 10 seconds
Vehicle_distance: 20 meters
Check for passengers at the bus stop
if Bus_stop():
open_doors()
BusStop_detected = True 
wait for time(DOOR_OPEN _TIME)
close_doors()
else:
BusStop_detected = False
```

[&#10132; Back to Hackathon](/hackathon-set/)

---

<a href="https://brickmmo.com">
<img src="https://brickmmo.com/images/brickmmo-logo-horizontal.jpg" width="100">
</a>
