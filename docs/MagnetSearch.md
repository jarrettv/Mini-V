# Magnets

Mini-V uses magnets in high-temperature areas which means ordinary magnets are not up to the task. I have over a years worth of print time using <abbr title="Samarium Cobalt">SmCo</abbr>  magnets and they hold up great even with repeated high bed/chamber temp cycles.

Normal neodymium magnets fail after the first couple heat cycles. However, there are high-temp classes:

## Neodymium Temp Classifications
- N	176°F (80°C)	590°F (310°C)
- NM	212°F (100°C)	644°F (340°C)
- NH	248°F (120°C)	644°F (340°C)
- NSH	302°F (150°C)	644°F (340°C) **➡️ These and below would work**
- NUH	356°F (180°C)	662°F (350°C)
- NEH	392°F (200°C)	662°F (350°C)
- NAH	428°F (220°C)	662°F (350°C)

## Bed Magnets

The bed magnets need to hold the bed firmly for the following activities:
* Heating bed to ~110°C for printing
* Pulling off the spring steel sheet
* Moving or turning the printer upside down

### Target dimensions
- 20 mm = .787 inches 3/4
- 10 mm = .4 inches 1/2
- 5 mm = .2 inches 1/8

### Candidates

* 20x10x5mm SmCo Magnets (Found on Ali)
  * No longer available
  * Great size and work fantastic
  * See [bed_Mag_Kinematic_Mount_x3.stl](../parts/bed_Mag_Kinematic_Mount_x3.stl)

* High Temp N42SH Neodymium Magnets 1 in x 1/2 in x 1/4 in Rare Earth Block
  * Oversized but very strong pull
  * See [bed_[a]_Kinematic_Bed_Mount_Neo_SH_Large_x3.stl](../parts/bed_[a]_Kinematic_Bed_Mount_Neo_SH_Large_x3.stl)

* SmCo Magnets 1/2 in x 1/2 in x 1/4 in Samarium Cobalt Block
  * Workable, but doesn't quite seem strong enough
  * See [bed_[a]_Kinematic_Bed_Mount_SmCo_Small_x3.stl](../parts/bed_[a]_Kinematic_Bed_Mount_SmCo_Small_x3.stl)

## Toolhead Magnets

The toolhead magnets need to hold the toolhead firmly for the following activities:
* Printing up to ~270°C and up to 70°C chamber temps
* Sensorless homing
* Fast acceleration printing

### Candidates

* 1/2" x 1/4" x 1/8" Blocks - SmCo - Samarium Cobalt
  * Must double-up for stronger hold
  * See [gantry_X_Carriage_Magnetic_x1.stl](../parts/gantry_X_Carriage_Magnetic_x1.stl)