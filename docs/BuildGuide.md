# Build Steps for Mini-V

> [!CAUTION]
> This build guide is a work-in-progress

## General Tips

* Use an ultra flat surface for assembly of frame
* Take a file or flattening stone to all mating surfaces, including all clips
* Panel clips should be snapped in diagonally towards the extrusion

## Gather Hardware
See [BOM](./docs/BOM) for Bill of Materials

## Print Parts
See [Printing Parts](./docs/PrintingParts)

## Heat Sets
* Grab some coffee, I hope you like putting in heat sets as there are many

> [!Tip]  
> You can build the left side of the printer, then the right side, or build them in parallel

## 🔁 Build left side
* Assemble 2 uprights and the bottom extrusion using blind joints M5x16 (2)  
  * (optional) Bottom of bottom extrusion will need (2) T-nuts
  * You should have a U shape

<p align="center">
  <img width="600" src="../images/00_Uframe.jpg">
</p>

### Building Z0 axis
* Add the Z0 motor mount using a M3x30 (1) side and M3x8 (1) screw on top
  * Note: leave these screws slightly loose until the final frame tighten
* Loosly mount Z-rail clips using M3x10 (4)
  * Order from bottom up
    * bed_Front_Z_Rail_Mount, M3x10
    * panels_Clip
    * bed_Front_Z_Rail_Mount_B_Mount (lower), M3x10
    * panels_Clip
    * bed_Front_Z_Rail_Mount, M3x10
    * panels_Clip_Door_Hinge_Latch_Left, M3x8
    * bed_Front_Z_Rail_Mount_A_Mount (upper), M3x10
    
<p align="center">
  <img width="600" src="../images/01_Z0_clips.jpg">
</p>

* Add the z-rail to clips using M3x6 (8)
  * Note: don't tighten down until all screws are in
  * Note: add your clip so carriage doesn't fall out when flipping upside down
* Tighten down Z-rail clips using ball end hex
  * Note: the top clip should line-up or you may need to adjust the clips

<p align="center">
  <img width="600" src="../images/02_Z0_rail.jpg">
</p>

### Rear E-bay mount (low voltage)
* Note: leave these screws for the Ebay mount loose until later, otherwise it might tweak the frame
* Add T-nuts to high-voltage ebay part using M3x10 (1) side middle and M3x6 (1) side top

<p align="center">
  <img width="600" src="../images/03_ebay_tnuts.jpg">
</p>

* Roll-in a bottom T-nut in position then slide on ebay part and fasten bottom with M3x8 (1)


### Y Rail mount
* Slide 269mm (2) steel rods into Y-rail mount (2)
  * Note: check the length is not longer than 270

<p align="center">
  <img width="600" src="../images/04_y_rail_check.jpg">
</p>

* Fasten the Y-rail using M3x6 (10) to get proper spacing
  * Note: your Y-rail needs to be cut precisely for this design
* Add T-nuts to each using M3x10 (2) then slide-in between extrusions

> [!CAUTION]
> The following steps requires precise measurements, so take your time

* Use calipers and set to 140mm from very top to top of mount
  * Note: you should see 245mm from lower extrustion to bottom of mount
  * TODO: Add diagram
* Tighten down Y-rail mount on both sides

<p align="center">
  <img width="600" src="../images/05_y_rail_install.jpg">
</p>

### Front and rear idlers
* Flatten mating surfaces and screw together front idler using M3x20 (1)
  * Screw front idler to front using M3x8 (4)

<p align="center">
  <img width="600" src="../images/06_front_idler.jpg">
</p>

* Flatten mating surfaces and screw together the motor idler using M3x20 (2)
  * Screw motor idler to rear using M3x8 (4)
  
<p align="center">
  <img width="600" src="../images/07_rear_idler.jpg">
</p>

> [!IMPORTANT]  
> The front and rear idlers add rigidity by clamping around the extrusion

<p align="center">
  <img width="600" src="../images/08_single_double_stack.jpg">
</p>

* Build a single stack bearing using F695 (2) and the plastic washer/clip should pop on the top
  * Add the single stack bearing using M3x30 (1) to the front idler

* Build a double stack bearing using F695 (4), M5 washers (2) and the plastic washer clip will pop on top keeping everything together
  * Add the double stack bearing using M3x30 to the rear motor idler back corner

* Assemble the guilder with the F623-RS (2) bearings in place and use M3x30 (1) screw
* Note: there is a mini plastic washer for the guilder

<p align="center">
  <img width="600" src="../images/09_bearings.jpg">
</p>

### XY Joint
* Flatten mating surfaces and screw together the XY Joint using M3x20 (1)
* Screw XY Joint onto Y Rail using M3x6 (4) FHCS
  * Note: you'll need a 2mm ball-end hex driver for the front two screws
* Build a single stack bearing using F695 (2) and the plastic washer/clip should pop on the top
  * Add the single stack bearing using M3x30 (1) to the front idler
  * Note: it should be in opposite orientation of other single stacks

<p align="center">
  <img width="600" src="../images/10_xy_joint.jpg">
</p>

### Add top extrusion
* Add the top extrusion using the blind joints M5x16 (2)
  * (optional) Top extrusion will need (2) T-nuts

<p align="center">
  <img width="600" src="../images/11_left_side_done.jpg">
</p>

## 🔁 Build right side
* Repeat all left side steps but mirror everything (Z2 motor mount)

<p align="center">
  <img width="600" src="../images/12_both_sides_done.jpg">
</p>


> [!CAUTION]
> There is a small error in the image above where right side has guilder in wrong spot


## Join sides and finish frame
* Slide motor mounts onto rear 279mm steel rods (2)
* Bring the two sides together by sliding rods into motor idler and on each side

<p align="center">
  <img width="600" src="../images/13_join_sides.jpg">
</p>

* Finish the frame on a flat surface using blind joints and M5x16 (8)
  * Note: ensure frame is square
  * Tighten all the screws you left loose
  * Congrats, it is starting to look like a printer

<p align="center">
  <img width="400" src="../images/14_frame_done.jpg">
  <img width="400" src="../images/14_frame_done2.jpg">
</p>

## Feet


* Add all four foot mounts using M3x6 (8) for LDO or M3x8 for taller foot mounts
* Each foot requires a M4 thumbscrew (4) and M3x16 (4) for LDO or M3x20 for taller foot mounts

<p align="center">
  <img width="600" src="../images/14_foot.jpg">
</p>

* There is an arc feature on the part to help you align each foot into the correct spot

<p align="center">
  <img width="600" src="../images/14_foot_feature.jpg">
</p>

## X-Rail
* Build the X-Rail backer using 280mm carbon rods (2)
* Mount the X-Rail (choose your best rail) using M3x8 (8)
  * Note: make sure you center things before screwing to the XY Joints

<p align="center">
  <img width="600" src="../images/15_x_rail.jpg">
</p>

* Screw X-Rail Backer to XY-Joints using M3x8 (4)

<p align="center">
  <img width="600" src="../images/15_x_rail_installed.jpg">
</p>

> [!Tip]  
> You can now test the gantry motion by hand and ensure it feels smooth

## Rear Z Motor Mount
* Note: Depending on printer tolerance, use a 5mm reamer on all the parts prior to joining them together
* Start with the Z1 motor mount and add the metal 280mm rods
  * Note: For the following rail mounts:
    * Consider sanding the mating edges
    * The parts should
* Here is the order top to bottom, you'll put bottom in first:
  * bed_Z1_Rail_Mount_top
  * bed_Z1_Rail_Mount
  * bed_Z1_Rail_Mount_Wire_Manage
  * bed_Z1_Rail_Mount
  * bed_Z1_Rail_Mount

<p align="center">
  <img width="600" src="../images/16_z1_stackup.jpg">
</p>

* Add the Z1 rail using M3x6 (11)

> [!Tip]
> Don't insert the top screw so you can leave the carriage saftey clip in place

<p align="center">
  <img width="600" src="../images/16_z1_rail.jpg">
</p>

* Use M3x20 (2) for lower screws, leave loose
* Measure 135mm to center of rear screw from both side extrusions
* Use M3x6 (1) and leave it loose too, you need to slide side to side to finalize the fit
* Install the E3EZ mount to the low voltage ebay mount using M3x8 (2)

<p align="center">
  <img width="600" src="../images/17_main_board_mount.jpg">
</p>


* Install the mid panels now help get the alignment of Z1
  * Except for the very bottom, the Z Rail Mounts should flex to allow you to pop in the mid panel
  * Note: this assumes your mid panels are accurately cut, otherwise use calipers to get it center

<p align="center">
  <img width="600" src="../images/18_mid_panels.jpg">
</p>

### Rear Z Motor Mount Clamp
* Add the tensioner knobs from behind into the back clamp using M5 nuts (2)
* Add your hex head M4x40 (2) into the back clamp to install the knobs
  * Note: orient the knob so the plastic side is on the outside


<p align="center">
  <img width="600" src="../images/19_clamp_knobs.jpg">
</p>

* Slide the clamp down over the vertical rods while passing the horizontal rods
  * Note: this part is tricky as you also need to line the hex head screws into motor mounts
* It should seat onto the horizontal rods

<p align="center">
  <img width="600" src="../images/20_clamp_slide.jpg">
</p>

* Add the front of the clamp using M3x8 (4)
* Before you completely tighten the clamp, check Z1 is centered and square with the frame
* Tighten down the clamp and the Z1 Motor Mount

> [!NOTE]  
> At this point the Z1 rail should feel very rigid

## Belts
* Install the pulleys on the A and B motors, use a single bearing stack to help set the proper height
* Add the A and B motors to the rear moto mounts using M3x35 (4) and M3x10 (4)
  * Note: the motor wires should exit towards the side extrusion


<p align="center">
  <img width="400" src="../images/21_b_motor.jpg">
  <img width="400" src="../images/21_a_motor.jpg">
</p>

* At this point you are still missing some bearings in the rear and the XY joints, this will make routing easier
* Route the belts like any standard Core-XY machine (link to youtube here)
  * Summary: route one side, leaving some slack (try to account for missing bearings)
  * Pull belt out and cut second belt to exact length
  * Put both belts back in

<p align="center">
  <img width="600" src="../images/22_belt_clips.jpg">
</p>

* Add the belts to clips using the M4x3x15 hollow tubes (2)
* Fasten the belts in the clips using M3x10 BHCS (2)

<p align="center">
  <img width="600" src="../images/23_belts.jpg">
</p>





## Add Z Motors
* Turn the printer upside down
* Mount all three integrated lead-screw motors using M3x6 (9)

















## Bottom Panel
* Panel should fit in under front motor connectors
* Add clips
* 

## Front Bed Rail Mounts
* Add M5x80mm (2) steel rods to mounts
* Attach to rail using M3x8 (4)
* Next add POM nut, twist on and screw down using M3x8 (2)
* Note: top may tighter than bottom, that is normal it should square up
* Test the up and down movement has no binding
* Add the 5x10x20 strong magnets to carriers
* Screw on the cover to keep magnets from sliding out
* Add on to the 80mm steel rods

## Bed Kinematics
* Use M4x10 (3) to screw on 10mm balls using 2 washers for spacing
* Test fit bed, should fit firmly in place with very little movement

## PSU
* For each PSU mount, add some 3mm thick foam between bracket and deck panel
* Add the PSU mounts using M3x8 for both brackets, tighten after a test fit
* Make sure the PSU is snug against the high voltage side front Z motor bracket









 