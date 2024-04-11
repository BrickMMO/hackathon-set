## Jazz Quartet

![Jazz Quartet](images/jazz-quartet.jpg)

> <small>LEGO (n.d.). LEGO Jazz Quartet. Retrieved 12 February, 2024, from [https://www.lego.com/en-ca/product/jazz-quartet-21334](https://www.lego.com/en-ca/product/jazz-quartet-21334)</small>

### Description

The [Jazz Quartet](https://www.lego.com/en-ca/product/jazz-quartet-21334) LEGO® will play whenever there are people infront of them in a certain distace.

![Jazz Quartet](images/jazz-quartet-interactive.png)

> <small>LEGO (n.d.). LEGO Jazz Quartet. Retrieved 12 February, 2024, from [https://www.lego.com/en-ca/product/jazz-quartet-21334](https://www.lego.com/en-ca/product/jazz-quartet-21334)</small>

### Ports

Jazz Quartet will output port on an EV3 hub to connect ultrasonic sensor.

<img src="./media/ev3/ports-sensors.png" height="200">

### Sensors and Motors

Untrasonic Sensor will be used to detect object distance.

<img src="./media/ev3/untrasonic-sensor.jpeg" height="200">

### Variable and Settings

Status: Can be set to "on" or "off". When on the quartet will move/play whenever there are object that are 15" or closer.

![Jazz Quartet](images/jazz-quartet-variables.png)

## Pseudocode

In this example, the Jazz quartet will only play when there are any objects at 15' or closer:

```pseudocode
WHile distance<=15

    IF status == "off"

        status = "on"
        Start Playing the jazz

    ELSEIF status == "on"

        status = "on"
        keep playing

    ELSE

        status = "off"
        stop playing

    ENDIF
```

[&#10132; Back to Hackathon](/hackathon-set/)

---

<a href="https://brickmmo.com">
<img src="https://brickmmo.com/images/brickmmo-logo-horizontal.jpg" width="100">
</a>
