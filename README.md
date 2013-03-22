Introduction
============

This repository holds all files and informations on my current tool-assisted speedrun of Braid.
It consists mainly of the .wtf file containing all inputs, and some general comments.

Configuration
=============

Hourglass
---------

Version r81
Configuration:
- Sound > Disable DirectSound Creation > checked
- Runtime > Performance > Store Video Memory in Savestates > unchecked
- Runtime > Performance > Store Guarded Memory Pages in Savestates > unchecked

Braid
-----

Version 1.015
Command line arguments: `-60fps -windowed -width 800 -height 600`

Computer
--------

Hourglass does not always behave the same depending on the computer, so here is my main specs:
- Dell Precision T3500
- Intel Xeon W3530 2.80Ghz
- 3 Go RAM
- NVIDIA Quadro FX 580
- Windows 7 Professionnel 32-bits SP1


RAM adresses
============

- 00586764 and 00586774 (floats): x position of Tim when on the ground
- 0058B270 and 0058B278 (floats): x position of the camera
- 0058B274 and 0058B27C (floats): y position of the camera

Current progress
================

- Main hub and World 2 hub: 17.62 s (1057 frames).


Physics
=======

speed are expressed in units/frame

- capped speed on flat surface: 4
- going up or down is slower (i.e. stairs on the hub: 3.464)
- landing on a leaning ground gives a small boost (i.e. staires on the hub: ~4.5-4.8)
- acceleration on the ground: 0.2/frame
- acceleration on the air: 0.2133/frame
- change direction on the ground: -0.485/frame
- change direction on the air: -0.2133/frame

Links
=====

- [Official Braid website](http://braid-game.com/)
- [Hourglass](http://code.google.com/p/hourglass-win32/)
- [Current speedrun WR in 27:02](http://www.youtube.com/watch?v=GEmYz33KcPg)
- Previous speedrun WR in 27:29. [Part 1](http://www.youtube.com/watch?v=dELboJ9Miio) and [part 2]{http://www.youtube.com/watch?v=8aYiLcwOxUM}
- [Speedrun route in about 25 min](http://www.youtube.com/watch?v=wFRN2aF8Wfo)
- Some other tricks: [3-8](http://www.youtube.com/watch?v=Vk1kjS9lG3I), [4-7](http://www.youtube.com/watch?v=EC-xO7G73b8)