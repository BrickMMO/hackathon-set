## T. rex Skull

![T. rex Skull](images/dinosaur-fossils.png)

> <small>LEGO (n.d.). LEGO Jurassic World Dinosaur Fossils: T-rex Skull. Retrieved 12 February, 
2024, from [https://www.lego.com/en-ca/product/dinosaur-fossils-t-rex-skull-76964](https://www.lego.com/en-ca/product/dinosaur-fossils-t-rex-skull-76964)</small>

### Description
The T-Rex Skull Module can be placed 
next to the Loop Coaster Module. The 
Skull can be a part of the Amusement park 
part of the Lego city

The Dinosaur will have a sensor that 
detects the arrival of the cart and we can 
program it to open its mouth as the cart 
reaches it.

![Rolling Coaster](images/rolling-coaster.png)

### Requirements
We need the below mentioned devices for 
making the T-Rex Skull open and close
- A sensor - To detect the incoming cart on 
the roller coaster
- Speaker - For making the dinosaur 
screech
- Motor - Attached to the skull, will make the 
mouth open and close

#### Electric components
- Technic Motor
- Battery pack
- Color & Distance Sensor
![88](images/loop-coaster-88013.png)
![89](images/loop-coaster-88015.png)
![90](images/loop3.png)

## Pseudocode
LOT Loop

```
While True:
    if status == "on"
        if cartDetected == True and motor is at initial upright position:
            Turn Technic motor 45 degrees counter-clockwise
            mouthOpen = True 
        else 
            mouthOpen = False
            move Technic back to initial position.
        if mouthOpen == True:
            make screech sound.
        else 
            stop sound.
```

[&#10132; Back to Hackathon](https://github.com/BrickMMO/hackathon-set/blob/main/index.markdown)

---

<a href="https://brickmmo.com">
<img src="https://brickmmo.com/images/brickmmo-logo-horizontal.jpg" width="100">
</a>
