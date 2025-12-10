# HapticHomiesFT Sensor


We used the Capacitance Comb library to automatically generate various configurations of capacitive comb structures for our capacitive force-torque (FT) sensor. Using the library in double-sided mode allowed us to create identical electrode traces for the top and bottom layers, ensuring symmetry and consistency. This automated generation process streamlined our sensor bring-up and improved design repeatability across different PCB configurations.


## PCB Configurations
There are multiple PCB configurations that vary by trace width, trace spacing, and the overall diameter of the electrode array (the circle formed by the four quadrants of electrodes).

### Electrode Array Diameter: 35 mm

| Option | Trace Width (mm) | Trace Spacing (mm) |
|:-------:|:----------------:|:------------------:|
| 1 | 0.2 | 0.2 |
| 2 | 0.4 | 0.4 |
| 3 | 0.4 | 0.2 |

### Electrode Array Diameter: 52 mm

| Option | Trace Width (mm) | Trace Spacing (mm) |
|:-------:|:----------------:|:------------------:|
| 1 | 0.7 | 0.2 |
| 2 | 1.0 | 0.2 |
| 3 | 0.7 | 0.1 |

These configurations allow us to test how trace geometry and sensor diameter affect the sensor's response and sensitivity. 
Different trace configurations can be generated using the Capacitance Comb library parameters accordingly.