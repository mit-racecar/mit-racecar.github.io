---
layout:     page
title:      "RACECAR Reference Manual"
subtitle:   ""
---

## Table of Contents
* TOC
{:toc}

## Connecting to the Car
1. Connect to the wifi router that belongs to your car. The 5GHz band works best if it is available.
	* The wifi password is `g0_fast!` 
2. `ssh racecar@192.168.0.[carnumber]`
	* password: `racecar@mit`



## Launching the racecar
All racecar software can be launched from a single launch file.  This file will launch the laser scanner, telop, and wheel controls.  You can launch the file with the following:

`roslaunch racecar teleop.launch`



## Common errors and fixes

### `Failed to connect to the VESC`
**Error message:**

`Failed to connect to the VESC, SerialException Failed to open the serial port to the VESC. IO Exception (16): Device or resource busy, file /tmp/binarydeb/ros-kinetic-serial-1.2.1/src/impl/unix.cc, line 151. failed..`

**Solution:**
* Make sure Traxxas VESC battery is plugged in.
* Make sure that USB hub on bottom of robot has a blue (power) light lit.
* Make sure that the USB cable from the VESC is plugged into the VESC and the USB hub.


