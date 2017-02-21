---
layout:     page
title:      "RACECAR reference guide"
subtitle:   ""
---

* TOC
{:toc}

# Connecting to the Car
1. connect to wifi router 192.168.0.[carnumber]
2. wifi password is `g0fast!`
3. ssh into car 
    * `ssh racecar@192.168.0.[carnumber]`
    * password: `racecar@mit`



# Launching the racecar
Our racecar bringup is located in on single launch file.  This file will launch the laser scan data, teloperation, and wheel controls.  You can launch the file with the following:

`roslaunch racecar teleop.launch`



# FAQ

### Failed to connect to the VESC
**Error message:**

`Failed to connect to the VESC, SerialException Failed to open the serial port to the VESC. IO Exception (16): Device or resource busy, file /tmp/binarydeb/ros-kinetic-serial-1.2.1/src/impl/unix.cc, line 151. failed..`

**Solution:**
* make sure traxxus chargers are plugged in


