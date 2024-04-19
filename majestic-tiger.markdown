## 50 Majestic Tiger 
<!--50 Majestic Tiger  -->
![50 Majestic Tiger](images/majestic-tiger-box.jpg)

> <small>LEGO (n.d.). LEGO 50 Majestic Tiger. Retrieved August 7, 2023, from [https://www.lego.com/en-ca/product/majestic-tiger-31129](https://www.lego.com/en-ca/product/majestic-tiger-31129)</small>

### Description

The official [50 Majestic Tiger ](https://www.lego.com/en-ca/product/majestic-tiger-31129) The tiger can move its head at a maximum of 45 degrees. When there is a trigger, it will open and close its mouth.

![50 Majestic Tiger](images/majestic-tiger-interactive.jpg)

<small>LEGO (n.d.). LEGO 50 Majestic Tiger. Retrieved August 7, 2023, from [https://www.lego.com/en-ca/product/majestic-tiger-31129](https://www.lego.com/en-ca/product/majestic-tiger-31129)</small>

### Requirements

Sensors and Motors
The only output port will be attached to an EV3 servo motor. 

1. 1st the status is “on”- one port(opening the tiger mouth)
2.	2nd status is: “off” -(closing the mouth of tiger)
2nd port
3.	3rd status:-moving head 45 degrees at right side
4.	4th status-moving head 45 degrees at left side

<img src="images/motor.jpg" height="200">
<img src="images/tiger-mouth.jpg" height="200">

## Pseudocode

IOT Loop

While True      If status == "on"

        If counter == 0
            Start head motor slow clockwise
        Else If counter == 15
            Stop head motor

Start mouth motor clockwise
         Else If counter == 20

Start mouth open motor counter-clockwise

         Else If counter == 25 Stop mouth motor
            Start head motor slow counter-clockwise
        Else If counter == 40
            Stop head motor

End

[&#10132; Back to Hackathon](/hackathon-set/)

---

<a href="https://brickmmo.com">
<img src="https://brickmmo.com/images/brickmmo-logo-horizontal.jpg" width="100">
</a>
