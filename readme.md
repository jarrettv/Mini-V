# Mini-V

Mini-V is a compact core-xy printer with a build volume of 180mm³ using 2020 extrusions. The printer is designed to maximize print volume with a minimal footprint. The build is simple compared to other small printers and all parts are easy to source.

- Easy to build 2020 box design ✅
- Super light carbon fiber rod backed X rail ✅
- Sleek flush panels enclosure ✅
- Quick access electronics and host ports ✅
- Fold-down door and easy to remove top panel ✅
- Consistently perfect first layers with Boop ✅
- Automatic bed leveling ✅
- Easy belt tensioning knobs ✅
- Hi-temp dual-mag tri-mount stay-put kinematic bed 😅 ✅
- CAN Toolhead with dual 4010 part cooling ✅
- Extra headroom for umbilical/PTFE tube ✅
- Dedicated high-voltage and low-voltage areas ✅
- No drag chains ✅
- Mostly M3 SHCS and easy to source hardware ✅

Prototype build log here: #"jv's Mini-V a custom compact 180³ build using 2020 and CF rods"

## Major BOM Components

- 4x Misumi HFSB5-2020-430-LCP-RCP corner extrusions
- 7x Misumi HFSB5-2020-270-TPW top and bottom extrusions
- 2x Carbon Fiber Rod 5mm Ø by 270mm long
- 4x Metal Rod 5mm Ø by 270mm long
- 4x Metal Rod 5mm Ø by 280mm long
- 6x Metal Rod 5mm Ø by 80mm long
- 6x Linear Rail MGN9H 220mm
- 180mm² or 185mm² MIC6 bed
- 180mm² PEI flex build plate
- 150mm² 300w AC heating pad and SSR
- Extruder of your choice (LGX-lite, Orbiter2, Galileo2)
- Hotend of your choice (Revo or Rapido2)
- 2x NEMA 17 XY stepper motor
- 3x Z Stepper motor with 200mm integrated lead screw (220mm preferred)
- 2x 150cm GATE 6mm GT2 open belt
- 3x Steel balls 10mm M4 threaded (must be magnetic)
- 6x Rectangular high-temp magnets 20x10x5mm (SaCo preferred)
- 4x F623-RS Bearings (guidelers)
- 24x F695 Bearings
- 2x 4010 24V blower fan (part cooling)
- 1x 3010 24V axial fan (hotend)
- 1x 4010 24V axial fan (electronics)
- 4x Rubber feet (amplifier)
- BTT E3EZ 5 stepper control board
- BTT EBB36 CAN toolhead board

See [BOM](./docs/BOM.md) for full Bill of Materials

## Adopted Community Designs
Although Mini-V is almost a completely custom design, it does utilize the following community designs:

- [Boop](https://github.com/PrintersForAnts/Boop) by `MasterMynd` 
- [Peck](https://github.com/chirpy2605/voron/tree/main/general/Experimental/Peck) by `chirpy2605` 
- [DragonBurner](https://github.com/chirpy2605/voron/tree/main/V0/Dragon_Burner) by `chirpy2605`
- Inspiration from Voron Trident and is derived from Tiny-T frame dimensions
