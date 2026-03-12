Hi everyone :3 i am Ishaan Nawani from India, i am 16 years old. I wanted to say that the experience the learning and the designing in the process of creating this project was very amazing , i managed to build this in really less amount of time, I had to learn PCB designing , how to make CAD files and etc. but the experience and what i learned in the way was priceless and i loved doing this project and i never imagined in a million years that i would be able to pull this off <3.

.

.

.

.

Project Description – Transistor Guitar Distortion Pedal

This project is a small distortion pedal made with transistors.
It takes the sound from an electric guitar and changes it to make a distorted tone that works well with rock and experimental music. The pedal uses a high-gain NPN transistor to boost the signal and diodes to clip the waveform, which creates the distortion effect. It runs on a 9V DC power supply and has a 3PDT footswitch for switching between bypass and distortion mode. There's also an LED light that shows if the pedal is on.

The project includes a custom-designed PCB made in KiCad, wires for the footswitch, audio jacks, and power input, and a 3D layout for the enclosure.

It is really simple to use it too:

To use the pedal, connect your electric guitar to the input jack and plug the output jack into an amplifier.
Then, connect a 9V DC power supply to the pedal.

When you press the 3PDT footswitch, it turns the pedal on or off.
When it's on, the LED lights up and the signal goes through the distortion circuit, changing the sound to a distorted tone. When it's off, the signal goes straight from input to output without any change.

Wondering why i made this project?
I made this project to learn about analog audio electronics and guitar effects.
The main aim was to understand how transistor amplification, biasing, and diode clipping affect the guitar signal to create distortion.

Building the pedal also helped me learn how to design PCBs in KiCad, wire hardware, and layout enclosures.
Instead of just copying an existing pedal, I created my own design and layout to better understand the whole process of building a pedal from a circuit diagram to the final product.

Images:

PCB Layout:
[FILE](https://github.com/ishaannawani25007-hash/Distortion-Circuit/tree/main/PCB)

The hardest part specially for me was to design the PCB as i am not an absolute professional at this although i did manage to make this from the schematic and was fun.

![Img](https://github.com/ishaannawani25007-hash/Distortion-Circuit/blob/main/Photos/pcb.png)


CAD Enclosure
[FILE](https://github.com/ishaannawani25007-hash/Distortion-Circuit/blob/main/Enclosure/EnclosureBodyLedVertical.STL)

![Img](https://github.com/ishaannawani25007-hash/Distortion-Circuit/blob/main/Photos/enclosure%20body.png)

[FILE](https://github.com/ishaannawani25007-hash/Distortion-Circuit/blob/main/Enclosure/BottomPart.STL)

![Img](https://github.com/ishaannawani25007-hash/Distortion-Circuit/blob/main/Photos/enclosure%20bottom.png)


Wiring 

There is no fancy wiring i have made the pcb in such a way such that the layout of the pcb mainly the terminals are easy to understand and follow the PedalPCB website's wiring diagram, it has made my work a lot easier and the diagram also shows how to easily wire the pedal.

The wiring labels on the board indicate the following:

InG - Intended for input jack ground

In - Input Jack Signal

SW - Switch connection to footswitch

SwG - Ground connection to footswitch

O - Output Jack Signal

OG - Intended for output jack ground

Gnd - Intended for power jack ground

9v - Positive 9v power


Note: The pedal wiring works the same as most PedalPCB pedals with a 3PDT footswitch unless otherwise noted. You can use this  [this build documentation](https://docs.pedalpcb.com/project/Amentum.pdf) build documentation as a wiring reference.

![Img](https://github.com/ishaannawani25007-hash/Distortion-Circuit/blob/main/Photos/Screenshot%202026-03-06%20004447.png)
==================================================================================================
List Of Material 

Theese materials are MOSTLY from robu although some parts if any that wont be on the website are updated below and links to each and every component is also given.

[Material List](https://github.com/ishaannawani25007-hash/Distortion-Circuit/blob/main/BOM.csv)

RESISTORS (1/4 watt)

| QTY | VALUE |

| 1 | [390](https://robu.in/product/mf25-390r-multicomp-pro-through-hole-resistor-390-ohm-mf25-series-250-mw-±-1-axial-leaded-250-v/) ohm |

| 1 | [4K7](https://robu.in/product/mf25-4k7-multicomp-pro-through-hole-resistor-4-7-kohm-250-mw-±-1-axial-leaded-250-v/) ohm |

| 1 | [10K](https://robu.in/product/mf25-10k-multicomp-pro-through-hole-resistor-10-kohm-250-mw-±-1-axial-leaded-250-v/) ohm |

| 1 | [43K](https://robu.in/product/mf25-43k-multicomp-pro-through-hole-resistor-43-kohm-mf25-series-250-mw-±-1-axial-leaded-250-v/) ohm |

| 1 | [430K](https://robu.in/product/mf25-430k-multicomp-pro-through-hole-resistor-430-kohm-mf25-series-250-mw-±-1-axial-leaded-250-v/) ohm |




CAPACITORS

| QTY | VALUE |

| 2 | [0.1 UF](https://robu.in/product/100nf-50v-disc-capacitor/) (100nF) |



TRANSISTORS(currently not available on Robu)

| QTY | Part # |

| 1 | [2N5088](https://www.amazon.in/2N5088-Transistor-NPN/dp/B08YFF1JN7) |



DIODES

| QTY | Part # |

| 1 | [1N5817](https://robu.in/product/1n5817-t-diodes-incorporated-20v-750mv3a-1a-do-41-schottky-diodes-rohs/) |

| 1 | [5mm LED](https://robu.in/product/tj-l5fytghrmfcsflc2r-a5-togialed-20ma-foggy-red-lens-20℃80℃-red-45-5mm-round-lamp-head-plugind5mm-led-indication-discrete-rohs/) (color of choice) | Note: Tayda drill template assumes the LED is in a 5mm bezel, change LED hole size as desired.



POTENTIOMETERS

| QTY | VALUE |

| 1 | [A100K](https://robu.in/product/p160knp-0qc20a100k-tt-electronics-bi-technologies/) | Note: B100K for linear taper works fine. Use 16mm right angle PCB mount if using 1590a drill template.



SWITCHES

1 | [3DPDT footswitch](https://robu.in/product/pbs-24-302-latching-push-button-switch-9pin/)


JACKS

2 | [1/4" Mono Audio Jack](https://robu.in/product/1-month-warranty-179/)

1 | 9 volt power from [PSU:](https://robu.in/product/dc-jack-022/) or [Battery:](https://robu.in/product/9v-battery-snap-connector-dc-jackbattery-connector-cap/) (center negative) Note: No space for battery in 1590a enclosure

============================================================================================

ALL THE DESIGNING AND MODELLING WERE DONE ON


  . [Kicad](https://www.kicad.org)
          
  . [Blender](https://www.blender.org)


. PCB From

  . [JlcPcb](https://jlcpcb.com)
  

.  Components From


  . [Robu](https://robu.in) & [Amazon](https://www.amazon.in)

===========================================================================================
