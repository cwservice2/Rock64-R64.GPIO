# Rock64-PythonUtilities
A collection of Python libraries, utilities, and scripts for the Rock64 single-board computer

## Python Libraries and Scripts
### R64.GPIO
A re-implementation of the RPi.GPIO library for the Rock64. Currently under development.

Function                   | Arguments                                                        | Status
:------------------------- | :----------------------------------------------------------------| :---
`VERSION`                  |                                                                  | Not yet implemented
`RPI_INFO`                 |                                                                  | Not yet implemented
`setmode`                  |                                                                  | Not yet implemented
`GPIO.setwarnings`         |                                                                  | Not yet implemented
`GPIO.setup`               | GPIO #, Direction (IN/OUT), Initial (HIGH/LOW), Pullup (UP/DOWN) | Implemented
`GPIO.output`              | GPIO #, State (HIGH/LOW)                                         | Implemented
`GPIO.input`               | GPIO #                                                           | Implemented
`GPIO.PWM`                 |                                                                  | Not yet implemented
`GPIO.wait_for_edge`       |                                                                  | Not yet implemented
`GPIO.event_detected`      |                                                                  | Not yet implemented
`GPIO.add_event_detect`    |                                                                  | Not yet implemented
`GPIO.add_event_callback`  |                                                                  | Not yet implemented
`GPIO.remove_event_detect` |                                                                  | Not yet implemented
`GPIO.cleanup`             | GPIO #                                                           | Implemented

# Resources
List of resources used while building the scripts and libraries in this repository
* [Kernel.org - GPIO/SYSFS Documentation](https://www.kernel.org/doc/Documentation/gpio/sysfs.txt)
* [Pine64 Forum - GPIO LED blinker using SYSFS on the Rock64](https://forum.pine64.org/showthread.php?tid=4695)
