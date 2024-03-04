## Daily Bugle

![Daily Bugle](images/daily-bugle.png)

> <small>LEGO (n.d.). LEGO Daily Bugle. Retrieved February 12, 2024, from [https://www.lego.com/en-ca/product/daily-bugle-76178](https://www.lego.com/en-ca/product/daily-bugle-76178)</small>

### Description

The  [Daily Bugle's](https://www.lego.com/en-ca/product/12-grimmauld-place-76408) antenna, crowned with a 
pulsating red light, elegantly illuminates when a 
passing vehicle triggers its sensor.

![Daily Bugle](images/bugle-antenna.png)

<small>LEGO (n.d.). LEGO Daily Bugle. Retrieved February 12, 2024, from [https://www.lego.com/en-ca/product/daily-bugle-76178](https://www.lego.com/en-ca/product/daily-bugle-76178)</small>

### Sensors

The output will be a Color & Distance sensor 
which will be detecting motion in front of the 
building’s street. 

![Sensor](images/bugle-sensor.png)

### Ports

Daily Bugle will require one output port on an 
EV3 hub to connect a sensor. Sensor will be 
sending signal to the tower light through a wire.


![Sensor](images/bugle-port.png)

### Variables/Settings

Status: When a vehicle passes in front of the 
tower, status switches to on. When on, the red 
light on the tower will blink at interval of 3 
seconds. Status returns to off after that.

Interval can be changed

![Variables](images/bugle-variables.png)


## IOT Loop

In this example, the location is only available when recently requested:

```pseudocode
While True

    IF status == "on" THEN

        LocationStatus = TRUE
        RotateMotor to 0

        IF counter % 3 == 0 THEN

        Turn off the light

        ELSE

        Turn on the light

        ENDIF
    ENDIF

ENDREPEAT
```

![lighthouse](images/bugle-light.png)


[&#10132; Back to Hackathon](/hackathon-set/)

---

<a href="https://brickmmo.com">
<img src="https://brickmmo.com/images/brickmmo-logo-horizontal.jpg" width="100">
</a>
