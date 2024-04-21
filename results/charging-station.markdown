## Charging Stations

<img src="dependency.PNG" style="height: 500px;"> 

> <small>The LEGO Group. (n.d.). Boutique Hotel. Retrieved 2022, from https://www.lego.com/en-ca/product/boutiquehotel-10297</small>

### Functionality and Dependency

The charging stations will be connected to a power 
grid which will then be used to charge the autonomous 
vehicles.
This system will rely on the Power Grid, GPS system, 
Payment system (if implemented) and the autonomous 
vehicle concept that will be present in the city.

<img src="functionality.PNG" style="width: 624px;"> 

>
### Sensors and Motors

• Distance sensor – to check if the charging 
station is occupied or not
• Switch – to start/stop the charging process
• Lights – to display the occupancy status for the 
stations
• Cables – for connecting the systems


<img src="sensors.PNG" height="200">

## Pseudocode

```pseudocode
While (availability == true) {
set lights = “Green”;
UpateGPS( );
if (payment == successful) {
Charging( );
else {
return “Payment 
unsuccessful”;
```

## API Endpoints
/api/chargingStation/list
Will return a list of charging station data in 
JSON, e.g. location, price, availability.

[&#10132; Back to Hackathon](/hackathon-set/)

---

<a href="https://brickmmo.com">
<img src="https://brickmmo.com/images/brickmmo-logo-horizontal.jpg" width="100">
</a>
