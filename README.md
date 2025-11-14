# DIY-Spacemouse
Backlog of my DIY Spacemouse Project

I want to design my own CAD Input device setup, beginning with a Spacemouse. The goals are:
- 6 DGF
- 4 Macrobuttons 
- Different Profiles (indicated by LED)
- OLED Display
- Compatible with Fusion360
- USB-C
- Premium feeling (surface finishing & weight)
- Cheap (using parts I already have or parts that are easy/cheaply available)

The general Idea is:
- a Spring-loaded knob
- Motion decoding using 4 magnets and 8 hall sensors (in groups of 2). The hall sensors are mounted with an offset to the magnets to detect a relative shift in 2 directions
- Different Profiles for different uses: 1 Sketch made (yellow) / 2 Move mode (blue) / 3 edit mode (green) / 4 default mode (orange)
- Display the button functions and the profile on the screen

Current Status:
- sensores/elektronics: working circuit for reading 8 analog hall sensores, completed PCB design V1, ordered PCB
- Spring-loaded knob: working spring setup (still too hard)
- general design: general concept
- software: working using a web Interface to input 6 DOF
