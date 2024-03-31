## Christmas tree

![Christmas tree](images/christmas-tree.png)

> <small>The LEGO Group. (n.d.). Christmas tree™. Retrieved 2022, from
[https://www.lego.com/en-nl/product/christmas-tree-40573](https://www.lego.com/en-nl/product/christmas-tree-40573)</small>

### Description

The [Christmas tree] (https://www.lego.com/en-nl/product/christmas-tree-40573)
The lighting of the Christmas tree will work according to color brightness. To make it work, we are going to use a color sensor.
Input will be color brightness to the sensor.
Output led bulb will light.

### Requirements

Christmas tree will require two output port on an EV3 brain.

#### Sensors

The only output port(blub) will be attached to an EV3 brain.

#### Port Settings

Status: Can be set to "on" or "off". When on {"status": "off"} 25% Dark automatically on by the sensor.

#### Port JSON

Christmas trees turn on light by a sensor

## Pseudocode

In this example, the location is only available when recently requested:

```pseudocode
If ( sensor > 25){ turn off light}
else (sensor <= 25){ turn on light}
```

[&#10132; Back to Hackathon](https://github.com/BrickMMO/hackathon-set/blob/main/index.markdown)

---

<a href="https://brickmmo.com">
<img src="https://brickmmo.com/images/brickmmo-logo-horizontal.jpg" width="100">
</a>
