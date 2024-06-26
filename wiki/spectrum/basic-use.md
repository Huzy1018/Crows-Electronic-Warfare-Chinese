# Spectrum device usage
The spectrum device is capable of tracking, listening and jamming depending on antenna and source. It can be used for various cases for tracking objects, jammers or units. It can also be used as a "detector" by setting the signal source range to like 0.5 meters.

## Antennas
The spectrum device has three different antennas which covers different frequency ranges:  
* **Military Antenna:** Frequencies from: 30-513 MHz. Used for detecting/listening to radio communication with TFAR or with the RadioChatter module put on AI. Also covers the 443-445 MHz frequency span that is emitted from jammable drones.
* **Experimental Antenna:** Frequencies from: 520-1090 MHz. Used to track signals set by zeus or trackers like C-Track.  
* **Jamming Antenna:** Frequencies from: 433-445 MHz. Used to detect, track or jam drones/UGV. Jammers will also show up as a sweeping signal in this frequency. 

## Controls
**left-mouse:** Holding it down will activate either listening to a signal or the jammer depending on antenna type  
**scroll-wheel:** Will move the selected frequencies around. Used to listen/jam the right signal.   
**middle-mouse:** Clicking will zoom in and show the selected frequencies. Makes it easier to see if multiple signals are overlapping or right next to each other.   
**shift + middle-mouse:** Resets the zoom to the frequencies visible to the equipped antenna. 

## CBA Settings
There is two CBA settings that influence what signals you can see. By default you will not see TFAR signals from same side as you, nor your own radio signals. However if you enable the ``Self-Tracking`` setting, you will be able to see your own signals, however you need to also enable ``Track Friendly with Radio Tracking`` setting to be able to see your own TFAR radio signal. 

Enabling ``Track Friendly with Radio Tracking`` will also make radio signals from your side show up. If they are shown you can also listen into them and hear their communication. 

## Listening
Using the experimental or military antenna on frequencies that belongs to drones or the RadioChatter module makes it play voice lines or sounds to simulate you listening to the radio/signal. If the strength is not enough you will hear garbled sound instead. 

![img1](https://user-images.githubusercontent.com/7889925/134808185-765b827f-780d-435e-a16e-6094ebca9990.jpg)

<iframe width="560" height="315" src="https://www.youtube.com/embed/LZ4dyb8P7u8?si=oHuBcvXVnOw8Ob8V" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>