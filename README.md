
# 3dp_hotplug_tools

## hot-pluggable 3d printer tools
 - remix from ProperPrinting's tools 
 - https://www.thingiverse.com/thing:3369444
 - https://www.thingiverse.com/thing:3547740
 - female connector is built in the base and male connector is built in the tools
 **big current flows through VBB (24V for ender3) and extruder heater pins, so 4 pins for each are assigned**
 **required voltages can be driven through VBB and GND by using DC-DC converter**
 
## base
 - female connector is installed by 15 degree angle 

<img src="https://github.com/PingguSoft/3dp_hotplug_tools/blob/main/pics/3dp_hotplug_tools_base_1.png?raw=true" width="60%">
<img src="https://github.com/PingguSoft/3dp_hotplug_tools/blob/main/pics/3dp_hotplug_tools_base_2.png?raw=true" width="60%">

## head tool pin connection
<img src="https://github.com/PingguSoft/3dp_hotplug_tools/blob/main/pics/3dp_hotplug_tools_pinout.png?raw=true" width="70%">

## 3dp hotend tool
<img src="https://github.com/PingguSoft/3dp_hotplug_tools/blob/main/pics/3dp_hotplug_tools_pinout_hotend.png?raw=true" width="70%">
<img src="https://github.com/PingguSoft/3dp_hotplug_tools/blob/main/pics/3dp_hotplug_tools_hotend_1.png?raw=true" width="60%">
<img src="https://github.com/PingguSoft/3dp_hotplug_tools/blob/main/pics/3dp_hotplug_tools_hotend_2.png?raw=true" width="60%">
<img src="https://github.com/PingguSoft/3dp_hotplug_tools/blob/main/pics/3dp_hotplug_tools_hotend_3.png?raw=true" width="60%">


## plotter tool
 - pen is moved up and down by using fan signal to speed up
 - pen is moved by solenoid and gravity and move up when solenoid is on (=fan is on)
<img src="https://github.com/PingguSoft/3dp_hotplug_tools/blob/main/pics/3dp_hotplug_tools_pinout_plotter.png?raw=true" width="70%">
<img src="https://github.com/PingguSoft/3dp_hotplug_tools/blob/main/pics/3dp_hotplug_tools_plotter_1.png?raw=true" width="60%">
<img src="https://github.com/PingguSoft/3dp_hotplug_tools/blob/main/pics/3dp_hotplug_tools_plotter_2.png?raw=true" width="60%">
<img src="https://github.com/PingguSoft/3dp_hotplug_tools/blob/main/pics/3dp_hotplug_tools_plotter_3.png?raw=true" width="60%">

## laser tool
 - laser voltage is controlled by using fan signal for laser module without pwm signal
 - if laser module has pwm signal, 15A mosfet module is not required
<img src="https://github.com/PingguSoft/3dp_hotplug_tools/blob/main/pics/3dp_hotplug_tools_pinout_laser.png?raw=true" width="70%">
<img src="https://github.com/PingguSoft/3dp_hotplug_tools/blob/main/pics/3dp_hotplug_tools_laser_1.png?raw=true" width="60%">
<img src="https://github.com/PingguSoft/3dp_hotplug_tools/blob/main/pics/3dp_hotplug_tools_laser_2.png?raw=true" width="60%">
<img src="https://github.com/PingguSoft/3dp_hotplug_tools/blob/main/pics/3dp_hotplug_tools_laser_3.png?raw=true" width="60%">