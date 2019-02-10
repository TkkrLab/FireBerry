---
title: "FireBerry: The digital fireplace sporting a RaspBerry Pi"
date: 2018-12-01
thumbnail: ""
---
# FireBerry
*The digital fireplace sporting a RaspBerry Pi*

## Materials used 
* [IKEA BISSA black shoe cabinet](https://www.ikea.com/nl/nl/catalog/products/90248426/)
* Thrifted 17" EIZO monitor (model tba)
* Black acrylic paint
* Four pre-drilled aluminum L-hooks
* Unbranded deco fireplace
* Raspberry Pi, with black casing
* MicroSD 10 speed card
* DVI to HDMI cable
* Mini-jack to mini-jack cable
* Black outlet strip with on/off button
* Copper kitchen cabinet handle

## Construction
Long ago, in 2016, the deco fireplace was given to me by a friend. 
After a few years of sitting in my living room, oftentimes on a pedestal of square bricks, 
I decided it should become part of a digital fireplace. I did not know how.

It was not until spring 2018, when I visited a German cottage with a lovely wood stove.
After using that wood stove for a week, I knew how to construct my digital one.

By coincidence, I spotted a black IKEA BISSA in my (fellow hacker) neighbour's home. 
It appeared to have the right measures to house the deco fireplace, and it looked a bit like the wood stove.

Together with my neighbour, I picked up the BISSA, and constructed it completely, except for the upper drawer and it's hinges.
We used the drawer's front plate for a back plate. We attached it at the back, between the side panels, with the four aluminum hooks.
The top of the panel was aligned flush with the top board of the cabinet.

I taped off the EIZO monitor's screen, to prevent smears. I painted it black and let it dry.
Punched the speaker holes with a toothpick to keep them open. 

Because the EIZO has VESA-10 mount, we could screw it to the back plate easily. 
Though keep in mind that this is done best by two people, or while the cabinet lays on its back on two stools.
Depending on your monitor, you will want to connect the video and audio cable already.
Attach the cabinet handle to the lower drawer.

Install the RaspBerry Pi with Raspbian on the MicroSD card. 
Download a fireplace video from Youtube that matches your fireplace looks and wishes. Resolution does not need to match.

Put the black outlet strip in the lower drawer. Cord comes out at the back. 
Connect the monitor with the cable to the RaspBerry Pi, and give it power at the outlet strip.
Put the RaspBerry Pi in the lower drawer as well, and power it up at the outlet strip.
Connect the audio cable to the Pi.

Boot the Pi.
You can either boot in command line, load a lot of libraries, and launch the video from there;
or you can boot to desktop, create a custom bootup script (links tba) and launch VLC and the video fullscreen from there.
I did the latter. 

In my VLC line, I fumbled long until the video displays zoomed, exactly to the size of the EIZO screen, with respect to ratio.
Check your audio to see if it is set to analog line out.

## Enjoy
Open your 'ash drawer' and toggle the on/off button on the outlet strip. The Pi wil boot.
Switch on the deco fireplace. Wait and see.

## Improvements
* Add photos and a video to this project!
* Make Raspberry Pi boot from network
* Tidy up cables in the lower drawer
* Build riser under deco fireplace, so its height matches the screen bottom
* Cover up inside, because you still see unused hinge holes
* Improve the safety fence
