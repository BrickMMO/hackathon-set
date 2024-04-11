# Firestation 

![Firestation](images/firestation.png)

> <small>LEGO. (n.d.). Fire Station and Fire Truck. Retrieved February 12, 2024, from [https://www.lego.com/en-ca/product/fire-station-and-fire-engine-60375](https://www.lego.com/en-ca/product/fire-station-and-fire-engine-60375)</small>

## Description

The fire station management system is equipped with a fire truck(nozzles, fire extinguishers and ventilators), administration, emergency dispatchers, firefighters and truck drivers, these entities will respond to a fire alarm when triggered within the city. 

<img src="images/lego-box.jpg" height="300" width="400" alt="FireStation Lego set">

## Requirements

* Fire Alarm in every house
* GPS System for navigation
* Map for tracking location

<img src="images/requirements.jpg" height="300" width="400" alt="Requirements page screenshot">

## Sensors and Motors

* Sound Sensor
* Distance Sensor

<img src="images/sound-sensor.jpg" height="200" width="300" alt="Sound Sensor Image">
<img src="images/distance-sensor.jpg" height="300" width="400" alt="Distance Sensor Image">

## Port Settings

* Port is “on” when the alarm is more on for more then 1 minute otherwise its “off”.
* Output port will be the Fire station from where the truck will go to destination.

<img src="images/port-settings.jpg" height="300" width="400" alt="Port Settings">

## Pseudocode

```Pseudocode
var map = map of the lego city
var emergencyLocation = null;

emergency = false;

IF fireAlarmRings > 1 minute 
emergency == true
emergencyLocation = building on fire location

function goToLocation(emergencyLocation)
{
 use the map and the emergencyLocation to get the route for the firestruck
 }

IF firestruck == available 
goToLocation() 
emergency = false

ELSE
wait for firestruck to be available

ELSE emergency is false

ENDIF
```

[&#10132; Back to Hackathon](/hackathon-set/)

---

<a href="https://brickmmo.com">
<img src="https://brickmmo.com/images/brickmmo-logo-horizontal.jpg" width="100">
</a>
