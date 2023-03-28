# Thermistor Amplifier

A thermistor amplifier for capturing sniff signals in rodents

## General Use

The circuit takes +5V DC and converts to +/-5V DC for the amp. Using the bias trimmer (the blue thing), you can roughly zero the input from the thermistor, allowing +/-5V swings depending on which side of the sniff you're on. I say roughly because the temperature is never static, so the baseline will drift up and down over the experiment. I considered using a chopper amp to pin the baseline to zero, but there's too much signal loss.

The thermistor gets connected to the 3-position screw terminal. "+5V" is going out from the board into the thermistor, while "In" is the input from the thermistor to the amp. The third position is connected to ground so you can connect cable shielding, which is techinally optional, but very highly recommended.

![](Docs/Images/Amp.png)

## Building

This board uses some surface mount parts. Don't be afraid of soldering them. They're big enough to solder with an iron - no special equipment required. Just practice a couple of times and you'll get the hang of it. You can try tinning one of the pads first, then using some tweezers to press the component down while you re-melt the solder on the pad. Then it's stuck in position and the other side is easy. Solder all the surface mount components first to make sure you have plenty of space to maneuver your iron.

Of course, you don't have to use the board I made. You can order your own through-hole equivalent parts and do it on a breadboard (or better yet, an Adafruit half-size perma-proto), but it's really not difficult to assemble and the boards are cheap. I usually get them from SeeedStudio's FusionPCB service, but anywhere that offers PCBs shouldn't have any trouble with it. 