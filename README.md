# scuba_flashlight

This was a project to make my own flashlight for scuba diving. See the result [here](https://www.youtube.com/shorts/ozFHNRW_oJQ) and some prototypes [here](https://www.youtube.com/shorts/tD2r_iiCCAc).

![flashlight](./assets/20260902_230148.jpg)

As I got more into Scuba diving in 2026, I realized I needed a flashlight. The English waters are cold, dark, and murky, and a flashlight helps cut through the gloom to signal to other divers. I knew a flashlight would have a couple components, namely the lighting mechanism that shigns a light and the sealing mechanism that keeps water out. Both equally important. I did some research and saw most people used aluminium, they used the body of the flashlight to complete the circuit and cool the LED and they used O-Rings to seal the flashlight. With that, I sketched some design options.

![design](./assets/design_options.png)  

The tradeoffs were mainly decided by how many seals (2 vs 3, the fewer the better as the less likelihood of leaks) and material size. Also pictured were some ambitious face designs for the flashlight that were cut...

In January I ordered the electronics I would need, picking powerful CREE LEDs.
![ledebay](./assets/ebay_order.png)  

and 26650 batteries to fuel them for about an hour (I hoped) though they were longer than 65mm due to the battery protection and charging at the top...
![batteries](./assets/20260124_140242.jpg)

I started to prototype with 3D Printing, see an early prototype on a test dive in a stone quarry.

![test_mercer](./assets/20260307_130332.jpg)

But it leaked...

![leaky](./assets/20260510_101342.jpg)

And so did the next one
![leaky2](./assets/20260518_230949.jpg)  

As I realized this would take me longer than I thought, I bought a used flashlight off of Ebay to use while diving in the summer, pictured below with another prototype...  
![leaky2-boat](./assets/20260525_154507.jpg)  

Eventually  got prototypes that could last the night in a tupperware full of water without leaking but couldn't withstand a dive. I began to believe it was the layer lines inside of the 3D print that under pressure were letting water through. I decided to move to aluminium. See here some Aluminium stock and the cut lines from the bandsaw:  
![ali_stock](./assets/20260609_120312.jpg)  

I got an induction on a lathe at the Institute of Making and Lucy a savvy technician there graciously spent a lot of time training me:
![lathe1](./assets/20260610_145825.jpg)

This process took months and in the meantime I did a lot more diving like at the Lundy Islands where I saw so many seals!
![lundy](./assets/20260725_141301.jpg)  

Including this one that was not impressed..."What, you again?"
![seals](./assets/seal.png)  

Lucy was teaching me all sorts of tricks to persuade metal into more conducive shapes to illumination, including some that ressembled medeval torture devices.
![boring](./assets/20260728_110154.jpg)

I turned my 3D Design into mechanical drawings to aid fabrication on the Lathe.
![mech_draw](./assets/20260728_121308.jpg)  

And did a lot of work (with a lot of help and guidance from Lucy).  
![work1](./assets/20260728_122600.jpg)  

In the below operation I drilled holes to mount the acryllic panel to the front of the flashlight, but I used a technique where I laser cut an acryllic template and then used a center punch to mark where I wanted holes. Unfortunately I was not as careful as I should have been here and 7 holes were perfect but my template must have slipped and 3 were off center. I accomodated this by carefully laser cutting new acryllic front panels till I got something that matched the pattern that was on the front of the flashlight.  
![work2](./assets/20260728_150714.jpg)  
![work3](./assets/20260806_121829.jpg)  

Now I needed to create the big (M32x1.5) threads on the flashlight. See the big tap compared to a normal big metric tap: 
![my_tap_is_bigger](./assets/20260824_153045.jpg)  

During summer break I couldn't use the lathe and the labs I worked in didn't have tap wrenches big enough. So I made my own...
![3d-tap-wrench](./assets/20260902_111410.jpg)

![die_wrench](./assets/20260901_160132.jpg)  

Unfortunately I had left an internal diameter oversized on the lathe as I couldn't measure it at the time and thought it was safer to leave it that way. This was the same diameter I had to tap. I used a file to remove material because I didn't want to wait for the workshop with the lathe to open, but this ruined the concentricity of the surface and meant the back of the flashlight was angled relative to the front and wouldn't go all the way as surfaces that should have had clearance were jammed together.
![crooked](./assets/20260902_115458.jpg)  

I persuaded those surfaces to loosen up a little...
![persuasion](./assets/20260902_122308.jpg)  

This led me to final assembly:
![assembly](./assets/20260902_213456.jpg)  

and electronics...
![assembly2](./assets/20260902_214041.jpg)

and finally a succesful test. There were definetly some lessons learned. I think the biggest mistake I made was rushing the threading at the end where I should have waited to use a lathe and kept concentricity. That said, my design would still not have screwed all the way together because I didn't leave enough room on the back part of the flashlight for threads given the die I used has about 2mm of soft or uncut threads in it. So, I don't feel that bad about rushing it. Smaller issues include a lack of a mechanism to secure the driver board in place, the reflector hole being too tight, and usage of a spring that was too tall and put too much force on the driver board when fully compressed yielding some damage to the PCB. 

All in all this project took me from January to September, one of my longer ones...Is it water proof? T.B.D.
