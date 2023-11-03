# Ninebot-G30-ESC-modding

## A guide about how to mod your own G30 ESC.

### Preface

In this guide we will talk about how to mod your own ESC. We will find out how the ESCs actually work, which components specifically need to be replaced, how we reinforce conductor tracks, and how we avoid short circuits.

### ESC Generations


When it comes to the G30 ESCs, we differentiate between 3 different circuit boards, each of which is intended for different models.

- Generation 1

<img src="pictures/NinebotMaxGen1ESC.1Cap.jpg"
  width="305">
<img src="pictures/NinebotMaxGen1ESC.3Cap.jpg"
  width="305">
 <br>
*Credits: <a href="https://joeybabcock.me/">Joey Babcock</a>*


The first generation ESC is based on a STM32 chip and connects to the motor via bullet connectors. Those models were invented by the end of 2019, with the release of the G30.
We differientate between the 1 capacitor and the 3 capacitor version.
Both ESCs are cast with a type of “silicone” to prevent incoming water damaging the board. The 3-capacitor-version can also be found in other models, but is most likely used for the German series of the G30(D).

- Generation 2

<img src="pictures/NinebotMaxGen2ESC.jpg"
  width="305">
<img src="pictures/NinebotMaxGen2ESC.Without Case.jpg"
  width="305"
  height=230>
  <br>
*Credits: <a href="https://joeybabcock.me/">Joey Babcock</a> &<a href="https://discordapp.com/users/1030601422900834345"> Stoindl</a>*

The second generation is based on the AT32 Chip and connects to the motor via screwable connectors. This model was invented by the new G30 models in early 2022. The ESC is protected by a black plastic shell and therefore does not contain any silicone for water protection. In addition, the mosfets are held by a clamp, which presses the mosfets onto the housing with tension to generate heat dissipation.



