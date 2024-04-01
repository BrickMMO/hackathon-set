## Hospital

![Hospital](images/hospital.png)

> <small>The LEGO Group. (n.d.). Hospital. Retrieved 2022, from
[https://www.lego.com/en-ca/product/hospital-60330](https://www.lego.com/en-ca/product/hospital-60330)</small>

### Description

The [Hospital] (https://www.lego.com/en-ca/product/hospital-60330)
This LEGO® Hospital set will send out an ambulance when it 
receives a signal.

### Requirements

The Hospital will require a prime hub with 6 
port

#### Sensors and Motors

The sensors and motors required at this time is 
the prime hub, small motors, and lights

<img src="media/spike/hub-prime.jpeg" height="200">
<img src="media/power-functions/motor-small.jpeg" height="200">
<img src="media/power-functions/lights.jpeg" height="200">

#### Port Settings

Ambulance will remain “off” until it receives a 
signal to move when it turns “on” and once task 
is complete it will remain “off” at the original 
location 

## Pseudocode

In this example, the location is only available when recently requested:

```pseudocode
IOT Loop
Emergency = 0
If emergency = 1
call function to get shortest path to address,
Contact GPS for roadblocks
Move to the coordinates
Go back to the hospital
Make emergency to 0 (In order to serve
again)
```

[&#10132; Back to Hackathon](https://github.com/BrickMMO/hackathon-set/blob/main/index.markdown)

---

<a href="https://brickmmo.com">
<img src="https://brickmmo.com/images/brickmmo-logo-horizontal.jpg" width="100">
</a>
