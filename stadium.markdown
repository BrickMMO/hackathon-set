## Stadium

![Stadium](images/stadium.png)

> <small>The LEGO Group. (n.d.). Football-stadium™. Retrieved 2022, from
[https://www.lego.com/en-ca/product/real-madrid-santiago-bernabeu-stadium-10299](https://www.lego.com/en-ca/product/real-madrid-santiago-bernabeu-stadium-10299)</small>

### Description

The [Football Stadium] (https://www.lego.com/en-ca/product/real-madrid-santiago-bernabeu-stadium-10299)
Th main idea behind this project is to create a stadium and built in some lights which goes “ON” or “OFF” as per the lights hits the sensor and to built-in some speaker to make some crowd noise such that a game is going on.


### Requirements
1.Lights
2.A hub
3.Color and distance sensor
4.Remote Control and Sound Kit


#### Lights

The lights are going to be atached to the hub to provide illumina􀆟on to the stadium.

![Lights](images/lights.png)

#### Ev3 Brick

This is the brains of whole contrap􀆟ons; the ev3 brick would be plugged in to the computer while will send the code to the hub which will process and send it to the lights and components.

![ev3 Brick](images/ev3.png)

#### Color and distance sensor

This would be used as a daylight sensor which will constantly calculate the brightness in nits. When the nits dropped below 150 then the lights will turn on.

![Color and distance sensor](images/colorsensor.png)

#### Remote Control and Sound Kit

This will be plugged into the hub and used to be create ambient noise at set interval of 􀆟me.

![Remote Control and Sound Kit](images/soundkit.png)

## Pseudocode
In this example, the location is only available when recently requested:

```pseudocode
1. For Lights
IF (sensor > 150 nits) THEN
Turn_lights = ON
ELSE
Turn_lights = OFF
2. Speaker
For Time = 3 hours + Prev_Time
Turn_Speaker = ON
Run Scripts(2 min)
Then Run the loop again in every 3 hours.
```


[&#10132; Back to Hackathon](https://github.com/BrickMMO/hackathon-set/blob/main/index.markdown)

---

<a href="https://brickmmo.com">
<img src="https://brickmmo.com/images/brickmmo-logo-horizontal.jpg" width="100">
</a>
