# Build Steps for Mini-V

Warning: this guide is a work-in-progress

## Tips

* Use an ultra flat surface for assembly of frame
* Take a file or flattening stone to all mating surfaces, including all clips

## Gather Hardware
See [BOM](./docs/BOM) for Bill of Materials

## Print Parts
See [Printing Parts](./docs/PrintingParts)


## 🔁 Build left side
* Assemble 2 uprights and the bottom extrusion using blind joints M5x16 (2)  
  * (optional) Bottom of bottom extrusion will need (2) T-nuts
  * You should have a U shape
### Building Z1 axis
* Add the Z1 motor mount using a M3x35 (1) side and M3x8 (1) screw on top
* Loosly mount Z-rail clips using M3x10 (4)
* Check the panel screw clip, door mount clip M3x8 (1), and LED clips are in proper spots
* Add the z-rail to clips using M3x6 (8)
* Tighten down Z-rail clips using ball end hex
  * Note: the top clip should line-up or you may need to adjust the clips
### Rear E-bay mount
* Add T-nuts to high-voltage ebay part using M3x8 (2)
* Roll-in a bottom T-nut in position then slide on ebay part and fasten bottom with M3x10 (1)
### Y Rail mount
* Slide 269mm (2) steel rods into Y-rail mount
* Fasten the Y-rail to get proper spacing
  * Note: your Y-rail needs to be cut precisely for this design
* Add T-nuts to each each using M3x10 (2) then slide-in between extrusions
* Use calipers and set to 119.5mm from top extrusion to top of mount
  * Note: you should see 245mm from bottom
* Tighten down Y-rail mount on both sides
* 🔰 Add additional clips above, use a short clip if necessary to have exactly 20mm left on top
### Front and rear idlers
* Flatten mating surfaces and screw together the motor idler using M3x20 (1) and a M3x35 (1)
* Screw motor idler to rear using M3x8 (4)
* Flatten mating surfaces and screw together front idler using M3x20 (1)
* Screw front idler to front using M3x8 (4)
* Add additional clips as shown in diagram
### Finish clips and side frame
* Add the top extrusion using the blind joints M5x16 (2)
  * (optional) Top extrusion will need (2) T-nuts

## 🔁 Build right side
* Repeat all left side steps (mirror)

## Join sides and finish frame
* Add the motors to the motor mount using M3x35 (4) and M3x10 (4)
  * Note: wires should exit towards outside
* Slide motors onto rear steel rods (2)
* Slide rods into motor idler and join left and right side
* Finish the frame on a flat surface using blind joints and M5x16 (8)
  * Congrats, it is starting to look like a printer

## Rear Z Motor Mount
* Use a 5mm reamer on all the parts prior to joining them together
* Start with the Z1 motor mount and add the metal 280mm rods
*  and then hammer the parts together, they should have a tight fit

* Use M3x20 (2) for lower screws, leave loose
* Measure 135mm to center of rear screw from both side extrusions
* Use M3x6 (1) and leave it loose too, you need to slide side to side for the next few steps


<span style="color:tomato;font-weight:bold">🚩 The following steps may be out of order or for early prototype designs</span>

## Front Idlers
* Sand mating surfaces
* Build stackup, left side has bearing at top, right side at bottom
* Front idler uses normal bearings
* Behind guidler uses smaller bearing
* You can screw together prior to bolting on Y-Rail
* Consider using a clamp to make sure top and bottom flush with Y-Rail
* Screw down M3x6 (4) on each side

## Front Z Motor Mounts
* Fasten inside using M3X16 (2) each side
* Note: M3 holes could be bigger so screw falls into place better
* Add front motors using M3x6 (3) for each side
* Note: they sink a .75mm too much, add beef
* Note: Motors actually fit in after feet

## Front Z Rail Mounts
* Start at the bottom, should lay on top of motor mount
* Use M3x8 (4) for each mount on both sides
* Leave loose (except for bottom) until you get a rail to align holes
* Use M3x6 (8) to fasten rail


## Rear Z Rail Mount
* Stack up the rear "horseshoe" mount on the CF rods
* Bottom up order: 2 normal, 3rd is for wiring, 4th is normal and 5th is "throne" top
* Leave about 27mm at bottom for putting in Z motor mount
* Check orientation as you stack them up for mounting rail
* Add stack to Z motor mount, rods will stick below motor mount ~6mm
* Add rear Z rail, it should sit upon extrusion
* Use every screw hole except top, keep plastic clip in place until later
* Tighten them down in any order, we are mounting to plastic after all
* Add optional 2mm metal pins to lock all the stack together

## Bottom Panel
* Panel should fit in under front motor connectors
* Add clips
* 

## Feet
* Use M4 thumb screw and M3x16 (or M3x18 if you have them) to attach to tiny skirts
* Repeat for all 4 feet
* Attach feet to bottom of frame using M3x6 (2) per foot
* Note: if using roll-in nuts, make sure long side is towards corner
* Note: Need to beef up the M3x6 recessed screws

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

## XY Joints
* Note: you have the option to screw from bottom (preferred) or top (easier access)
* Use M3x8 FHCS (4) to mount both left and right XY joints
* Note: you'll need a ball end to tighten the back screws down
* Next, add the bearings and fasten using M3x30 (4)
* Finally, add M3x20 bolt top and bottom together

## X Rail Beam
* Align the parts on the M5x285 CF rods, use the rail as a guide
* Dry fit on the XY joints before tighting down
* Use M3x6 (8) to fasten rail to beam
* Use M3x6 (2) to fasten beam to XY joints

## Motor Mount Bearings
* Add the bearings in the motor mounts to match your front orientation
* Back corners should be your only double stacks
* ProTip: lube top of motor so belts are easier to tension later
* Mount motors using M3x8, just the back two screws for now
* Motors should be nearest the corners to allow tensioning later
* Adjust the motor pully so it aligns with bearings
* Note: there is very little clearance here and the pully will rub CF rod if you aren't careful 
* It is best to route the belts prior to putting top of motor mounts on

## Belts
* Route the belts like any standard Core-XY machine
* If you haven't put the motor tensioners in, put them in now
* ProTip: add some lube so the tensioners slide easier
* Once loosly routed, put the top motor mount cover on
* Note: be careful with your bearing stacks and the belts
* Note: this is pretty tricky so take your time

## Belt Tension
* Put M3x35 (2) into the motors but don't tighten yet
* You should be able to slide the motor back and forth by hand
* Add M3x12 tensioning screw to help dial-in the tension later
* Mount the boop X-rail to X carriage and sandwich the belts following boop directions
* You can now dail-in the tension so the gantry hits the front and back perfectly

## Rear Z Top Mount
* Put M3x8 (4) into the top clamp, leave loose for now
* Use a square to ensure the hole assembly is square to the frame
* Double check the top clamp is centered between the motor mounts
* Tighten the clamp

## Low-voltage E-Bay
* Mount top using M3x8 and bottom using M3x8 but leave bottom loose
* Squeeze mid panel between rear Z and side
* Tighten bottom screw then add E3EZ IO shield, it should snap into place
* Bolt E3EZ board to bracket using M3x6 (4)
* Bolt bracket into side mount using M3x8, you may need a small hex key here






 