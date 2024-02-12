## Infinity Gauntlet

<img src="images/Infinity-Gauntlet-box.webp" style="height: 500px;"> 

> <small>LEGO (n.d.). LEGO Nano Gauntlet. Retrieved February 12 2024, from [https://www.lego.com/en-ca/product/nano-gauntlet-76223](https://https://www.lego.com/en-ca/product/nano-gauntlet-76223)</small>

### Description

Tony Stark's [Infinity Gauntlet](https://www.lego.com/en-ca/product/nano-gauntlet-76223) from Avengers Endgame. We will add lights in the infinity stones and a motor in the base to make the whole hand spinning.
![Infinity Gauntlet](images/Infinity-Gauntlet.webp)

> <smalll>LEGO (n.d.). LEGO Nano Gauntlet. Retrieved February 12 2024, from [https://www.lego.com/en-ca/product/nano-gauntlet-76223](https://https://www.lego.com/en-ca/product/nano-gauntlet-76223)</small>

This interaction will only require a motor and lights.

### Requirements

The first output will be attached to an EV3 servo motor. The second port will be connected to EV3 Lights.

<img src="/images/Sensor.png" height="200">
<img src="/media/ev3/brick.jpg" height="200">

## Pseudocode

In this example, the location is only available when recently requested:

```pseudocode
REPEAT-EVERY 30 Seconds

    IF LastGpsRequest < 30 Minutes THEN

        LocationStatus = TRUE
        RotateMotor to 0

    ELSE

        LocationStatus = FALSE
        RotatMotor to 360

    ENDIF

ENDREPEAT
```

In this example, the building is only avialable between 11:00 am and 1:00 pm. A GPS request will return false when the building is not available:

```pseudocode
REPEAT-EVERY 1 Hour

    IF Hour > 11:00 AM AND Hour < 1:00 PM THEN

        LocationStatus = TRUE
        RotateMotor to 0

    ELSE

        LocationStatus = FALSE
        RotatMotor to 360

    ENDIF

ENDREPEAT

ON RequestGsLocation EVENT

    IF LocationStatus == TRUE THEN

        RETURN GpsLocation

    ELSE

        RETURN FALSE

    ENDIF

ENDEVENT
```

[&#10132; Back to Hackathon](/hackathon-set/)

---

<a href="https://brickmmo.com">
<img src="https://brickmmo.com/images/brickmmo-logo-horizontal.jpg" width="100">
</a>
