---
layout:     post
title:      "Getting Started"
subtitle:   "How to start your racecar"
class: "no_ridiculous_spacing"
author: "Ariel Anders"
---

## Connecting to the Car
1. Connect to the wifi router that belongs to your car. The 5GHz band works best if it is available.
	* The wifi password is `g0_fast!` 
2. `ssh racecar@192.168.0.[carnumber]`
	* password: `racecar@mit`



## Launching the racecar
All racecar software can be launched from a single launch file.  This file will launch the laser scanner, telop, and wheel controls.  You can launch the file with the following:

```
roslaunch racecar teleop.launch
```



