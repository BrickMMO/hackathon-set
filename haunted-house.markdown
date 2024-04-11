## Haunted House

![Haunted House](images/haunted-house.png)

> <small>LEGO (n.d.). LEGO Haunted House. Retrieved February 12, 2024, from [https://www.lego.com/en-ca/product/haunted-house-10273](https://www.lego.com/en-ca/product/haunted-house-10273)</small>

### Description

Welcome to Manor von Barron, a spooky Haunted House theme-park ride packed with chills and thrills for all who dare to enter. Once home to one of the world’s greatest villains who travelled the globe in search of treasures to steal, this Haunted House is a nostalgic throwback to classic LEGO® adventure sets, so be sure to look for rare bricks and ancient artifacts hidden throughout this spooky set!

![Haunted House](images/haunted-house-interactive.png)

> <smalll>LEGO (n.d.). LEGO Haunted House. Retrieved February 12, 2024, from [https://www.lego.com/en-ca/product/haunted-house-10273](https://www.lego.com/en-ca/product/haunted-house-10273)</small>

### Requirements

1. Medium Linear Motor
2. Hub
3. Distance Sensor
4. Lights
5. Speaker

<img src="media/ev3/steering-motor.png" height="200">
<img src="media/spike/hub-robot-inventor.jpeg" height="200">
<img src="media/spike/distance-sensor.png" height="200">
<img src="media/power-functions/lights.jpeg" height="200">

### Sensors and Motors

The input port will be attached to an distance sensor . The output port will be attached to medium linear motor, lights and speaker.

### Port Settings

Port A - Output : Lights : on / oﬀ  
Port B - Output : Motor : on / oﬀ  
Port C - Input : Distance Sensor : 0-9  
Port D - Output : Speaker : on / oﬀ  

## Pseudocode

```pseudocode
While True:
  If distance_sensor.distance < 3:
    wait(5000) #wait 5000ms
   motor.rotate() #turns on lift motor
   light.blink(true) #blinks the light
   play_sound() # play spooky sounds
Else:
  light.blink(false) #stops blinking
  stop_sound() #stops spooky sounds
```

[&#10132; Back to Hackathon](/hackathon-set/)

---

<a href="https://brickmmo.com">
<img src="https://brickmmo.com/images/brickmmo-logo-horizontal.jpg" width="100">
</a>
