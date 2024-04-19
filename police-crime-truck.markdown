## Police Crime Truck

![Police Crime Truck](images/police-mobile-crime-lab-truck.png)

> <small>The LEGO Group. (n.d.). Police Mobile Crime Lab Truck™. Retrieved 2024, from
[https://www.lego.com/en-ca/product/police-mobile-crime-lab-truck-60418](https://www.lego.com/en-ca/product/police-mobile-crime-lab-truck-60418)</small>

### Description

Whenever a crime is committed in the city and alerted,
the [Police Crime Truck](https://www.lego.com/en-ca/product/police-mobile-crime-lab-truck-60418) will receive the
location and navigate there.

> <small>The LEGO Group. (n.d.). Police Mobile Crime Lab Truck™. Retrieved 2024, from
[https://www.lego.com/en-ca/product/police-mobile-crime-lab-truck-60418](https://www.lego.com/en-ca/product/police-mobile-crime-lab-truck-60418)</small>

#### Sensors and Motors

The 4 outputs will be attached to an EV3 brain.
The truck will need a small motor to move the
wheels and a GPS module to interact with the
alert location.
The truck will need a distance sensor to detect
obstructions.
Additionally, it will also need LED lights turning
ON and OFF as well as audio outputs to
simulate a siren.  
<img src="images/police-mobile-crime-lab-truck-large-motor.png" width="624" alt="police mobile crime lab truck large motor">
<img src="images/police-mobile-crime-lab-truck-light.png" width="624" alt="police mobile crime lab truck light">

#### Ports

Crime Truck will require two output ports on an
EV3 hub to connect a motor and LED lights.  

<img src="images/police-mobile-crime-lab-truck-ports.png" width="624" alt="police mobile crime lab truck ports">

#### Variables/Settings

Status: Can be set to "on" or "off". When there is an
alert in the city. 

## Pseudocode

In this example, the location is only available when recently requested:

```pseudocode
While True

    If status == “ON"

        Start motor and Light

        Go to the alert location using the GPS

        Stop motor and light

    else status == “OFF”

        Stop motor and light
```


[&#10132; Back to Hackathon](/hackathon-set/)

---

<a href="https://brickmmo.com">
<img src="https://brickmmo.com/images/brickmmo-logo-horizontal.jpg" width="100">
</a>
