## Car Wash

![Car Wash](images/car-wash-lego.png)

> <small>The LEGO Group. (n.d.). Car Wash™. Retrieved 2022, from
[https://www.lego.com/en-ca/product/car-wash-60362](https://www.lego.com/en-ca/product/car-wash-60362)</small>

### Description

The [Car Wash] (https://www.lego.com/en-ca/product/car-wash-60362)
LEGO® set includes a car and the car
wash building with brushes that turn once a car
is pushed through.

This module will have a car that automatically drives through the car wash. Once a car enters
the car wash, a light will turn red to signal that
the car wash is in use. A countdown will start.
Once the countdown reaches 0, the “car wash
process” will be complete. The car will drive out
of the car wash and the light will turn green
signaling that the car wash is open and
available.

### Requirements

The car wash will require three output ports on
an EV3 brain.

#### Sensors and Motors

The first output port will be attached to a motion
sensor.
The second output port will be attached to a
motor pair.
The third output port will be attached to a light
matrix.

![Car Wash Sensors](images/car-wash-sensors.png)

#### Port Settings

Status: Can be set to "on" or "off".
When on car moves through the car wash, the
lights turn red and the timer starts. Once the
timer hits 120s the light turn green it’s set to off.

#### Port JSON

Buildings: The ID of the Car Wash building.

## Pseudocode

In this example, the location is only available when recently requested:

```pseudocode
If motion sensor = true

Then matrix light = red and countdown starts

If countdown = 0

Then car drives off
```

[&#10132; Back to Hackathon](https://github.com/BrickMMO/hackathon-set/blob/main/index.markdown)

---

<a href="https://brickmmo.com">
<img src="https://brickmmo.com/images/brickmmo-logo-horizontal.jpg" width="100">
</a>
