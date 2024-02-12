## T-REX SKULL
BY:
- Ting Liu
- Reddy Nagendra

### Dinosaur Fossils: T.rex Skull
<small>LEGO  (n.d.). JuRassic World Dinosaur Fossils: T. rex Skull(76964)</small>
![DF](images/Dinosaur-Fossils.png)
![DF2](images/Dinosaur-Fossils-2.png)
![DF3](images/Dinosaur-Fossils-3.png)

### Module Description
The T-Rex Skull Module can be placed 
next to the Loop Coaster Module. The 
Skull can be a part of the Amusement park 
part of the Lego city

The Dinosaur will have a sensor that 
detects the arrival of the cart and we can 
programme it to open its mouth as the cart 
reached it.

![Rolling Coaster](images/Rolling-Coaster.png)

## Requirements
We need the below mentioned devices for 
making the T-Rex Skull open and close
- A sensor - To detect the incoming cart on 
the roller coaster
- Speaker - For making the dinosaur 
screech
- Motor - Attached to the skull, will make the 
mouth open and close

## Electric components
- Technic Montor
- Battery pack
- Color & Distance Sensor
![88](images/loop-coaster-item-88013.png)
![89](images/loop-coaster-item-88015.png)
![90](images/loop3.png)

## LOT Loop
```
While True:
    if status == "on"
        if cartDetected == True and motor is at initial upright position:
            Turn Technic motor 45 degree anti-clockwise
            mouthOpen = True 
        else 
            mouthOpen = False
            move Technic back to initial position.            
        if mouthOpen == True:
            make screech sound.
        else 
            stop sound.
```