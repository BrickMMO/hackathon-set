## Freight Train

![Freight Train](images/freight-train.png)

> <small>The LEGO Group. (n.d.). Freight Train. Retrieved 2022, from
[https://www.lego.com/en-ca/product/freight-train-60336](https://www.lego.com/en-ca/product/freight-train-60336)</small>

### Description

The [Freight Train](https://www.lego.com/en-ca/product/diagon-alley-75978)
LEGO® set will travel around the loop. The train
can also switch to the straight track by toggling
the switch. 

### Requirements

The freight train will require one output port on
an EV3 brain to accelerate. Another output port
on an EV3 brain will be connected to the toggle
on the track to switch tracks.

#### Sensors and Motors

The output port will be attached to an EV3 servo
motor on the train to control acceleration. The
toggle on the track will have a small motor and
output port to switch directions.

![Freight Train Sensors and Motors](images/freight-sensor.png)

#### Port Settings

Status: Train motor can be set to “on” or “off”
and can control the acceleration of the train
while “on”.
Status: Can be set to "on" or "off" for the track
toggle in order to change directions. When
toggle is turned “on” using the interface, the
train will be taken off the loop and go to the
straight track.

#### Port JSON

Buildings: The ID of the Freight Train Track.

## Pseudocode

In this example, the location is only available when recently requested:

```pseudocode
Train motor:

While True

If status == "on"

Motor speed = 10

Else

Motor speed = 0
```

```pseudocode
Track toggle:

While true

If status = “on”

Switch track
```


[&#10132; Back to Hackathon](/hackathon-set/)

---

<a href="https://brickmmo.com">
<img src="https://brickmmo.com/images/brickmmo-logo-horizontal.jpg" width="100">
</a>
