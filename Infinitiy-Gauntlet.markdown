## Infinity Gauntlet

<img src="images/Infinity-Gauntlet-box.webp" style="height: 500px;"> 

> <small>LEGO (n.d.). LEGO Nano Gauntlet. Retrieved February 12 2024, from [https://www.lego.com/en-ca/product/nano-gauntlet-76223](https://https://www.lego.com/en-ca/product/nano-gauntlet-76223)</small>

### Description

Tony Stark's [Infinity Gauntlet](https://www.lego.com/en-ca/product/nano-gauntlet-76223) from Avengers Endgame. We will add lights in the infinity stones and a moto in the base to make the whole hanf spining  LEGO® set has a built in intaractive feature. 
![Infinity Gauntlet](images/Infinity-Gauntlet.webp)

> <smalll>LEGO (n.d.). LEGO 12 Grimmauld Place. Retrieved August 7, 2023, from [https://www.lego.com/en-ca/product/12-grimmauld-place-7640](https://www.lego.com/en-ca/product/12-grimmauld-place-7640)</small>

This motion will be connected to a motor so the interaction can be automated.

This interaction will have an interesting effect on the GPS and mapping tools. UNlike most buildings, this building only exists at certain times. OR the building could be in hiding until the mapping system receives a request for this address.

### Requirements

This interaction will only require a large EV3 motor and the EV3 hub:

<img src="/media/ev3/servo-motor.png" height="200">
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
