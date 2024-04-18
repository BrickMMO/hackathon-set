## 39 Cops and Robbers

![39 Cops and Robbers](images/cops-robbers1.jpg)

> <small>LEGO (n.d.). LEGO 39 Cops and Robbers. Retrieved August 7, 2023, from [https://lego.com/en-ca/product/police-station-chase-60370](https://lego.com/en-ca/product/police-station-chase-60370)</small>

### Description

The official [39 Cops and Robbers](https://lego.com/en-ca/product/police-station-chase-60370) introduces kids to a world of imaginative play with this LEGO® City Police Station Chase (60370) toy playset for kids aged 4+. The station building features a raisable barrier and houses an office and a jail with a breakout function. This set also includes a police car and a crook’s getaway motorcycle, plus 2 police officer and 2 crook minifigures.

![39 Cops and Robbers](images/cops-robbers2.jpg)

> <smalll>LEGO (n.d.). LEGO 39 Cops and Robbers. Retrieved August 7, 2023, from [https://www.lego.com/en-ca/service/buildinginstructions/60370](https://www.lego.com/en-ca/service/buildinginstructions/60370)</small>

The police will chase and arrest the robber, then escort the robber back to the police station when a siren is triggered. The police car will have two motors: rear wheels and front wheels. The robber will have one motor.

### Requirements

This interaction will require three motors: two for the cars. One for the bike.

<img src="media/ev3/servo-motor.png" height="200">
<img src="media/ev3/brick.jpg" height="200">

## Pseudocode

In this example, The police will chase and arrest the robber, then escort the robber back to the police station when a siren is triggered:

```pseudocode
Function Chase Robber
WHILE siren NOT triggered
	Continue police patrol route

	IF siren IS TRUE THEN
		Change to police chase route

	END IF
END WHILE

Function Arrest Robber
WHILE distance between robber and police car < 2cm
	Robber follow the police car back to plice station
	Reset route
END WHILE

Function Robber
WHILE ditance between robber and police car > 2cm
	Continue robber route
	IF distance between robber and police car < 2cm
	Call Arrest Robber Function

END WHILE
```

[&#10132; Back to Hackathon](/hackathon-set/)

---

<a href="https://brickmmo.com">
<img src="https://brickmmo.com/images/brickmmo-logo-horizontal.jpg" width="100">
</a>
