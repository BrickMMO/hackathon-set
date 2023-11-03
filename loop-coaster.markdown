## Loop Coaster

![Loop Coaster](images/loop-coaster.png)

> <small>The LEGO Group. (n.d.). Loop Coater™. Retrieved 2023, from
[https://www.lego.com/en-ca/product/loop-coaster-10303](https://www.lego.com/en-ca/product/loop-coaster-10303)</small>

### Description

The [Loop Coaster](https://www.lego.com/en-ca/product/loop-coaster-10303)
LEGO® Loop Coaster is a theme park, where there is
motorized coaster going around once.

> <small>The LEGO Group. (n.d.). Loop Coaster™. Retrieved 2023, from
[https://www.lego.com/en-ca/product/loop-coaster-10303](https://www.lego.com/en-ca/product/loop-coaster-10303)</small>

#### Sensors and Motors

The Loop Coaster will require a Motor and Battery pack.

![Loop Coaster Sensors and Motors](images/loop-coaster-item-88013.png)

![Loop Coaster Sensors and Motors](images/loop-coaster-item-88015.png)


## Pseudocode

In this example, the location is only available when recently requested:

```pseudocode

Elevator code:

While true

If status == “on”

If counter == 0

Start motor elevating up

Else if counter == 10

Stop motor

Else if counter == 40

Start motor elevator down

Else if counter == 60

Stop motor
```

```pseudocode

Coaster Code:

While true

If status == “on”

If counter == 0

Start motor

Else if counter == 40

Stop motor forward

Else if counter == 50

Start motor backward

Else if counter == 60

Stop motor
```


[&#10132; Back to Hackathon](https://github.com/BrickMMO/hackathon-set/blob/main/index.markdown)

---

<a href="https://brickmmo.com">
<img src="https://brickmmo.com/images/brickmmo-logo-horizontal.jpg" width="100">
</a>
