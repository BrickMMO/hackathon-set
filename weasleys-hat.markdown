## Weasley’s Hat

![Weasleys-Hat](images/weasleys-hat.png)

> <small>The LEGO Group. (n.d.). Weasley's-Hat™. Retrieved 2022, from
[https://www.lego.com/en-ca/product/diagon-alley-weasleys-wizard-wheezes-76422](https://www.lego.com/en-ca/product/diagon-alley-weasleys-wizard-wheezes-76422)</small>

### Description

The [Weasley's Hat] (https://www.lego.com/en-ca/product/diagon-alley-weasleys-wizard-wheezes-76422)
LEGO® set from the Diagon Alley set already
has a lever to tip his hat manually. This module
will tip his hat automatically every ten seconds.


### Requirements

Weasley’s hat will require one output port on an
EV3 brain

#### Sensors and Motors

The only output port will be attached to an EV3
servo motor.

![Hat Sensor](images/sensor.png)

#### Port Settings

Status: Can be set to "on" or "off". When on
Weasley’s hat will tip every ten minutes.

#### Port JSON

Buildings: The ID of the Weasleys' Wizard
Wheezes building

## Pseudocode

In this example, the location is only available when recently requested:

```pseudocode
While True
If status == "on"
If counter == 0
Start motor slow clockwise
Else If counter == 10
Stop motor
Else If counter == 50
Start motor slow counter-clockwise
Else If counter == 60
Stop motor
```

[&#10132; Back to Hackathon](https://github.com/BrickMMO/hackathon-set/blob/main/index.markdown)

---

<a href="https://brickmmo.com">
<img src="https://brickmmo.com/images/brickmmo-logo-horizontal.jpg" width="100">
</a>
