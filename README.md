# HidrateSpark PRO Qi charging retrofit

- [HidrateSpark PRO Qi charging retrofit](#hidratespark-pro-qi-charging-retrofit)
  - [Prep](#prep)
    - [BOM](#bom)
      - [micro qi charge coil](#micro-qi-charge-coil)
      - [AWG 30 or similar wire](#awg-30-or-similar-wire)
      - [4x m2x4mm screws](#4x-m2x4mm-screws)
    - [Tools](#tools)
      - [Note on adhesives](#note-on-adhesives)
    - [Parts](#parts)
  - [Assemble](#assemble)
  - [Finish](#finish)

This document is concerned with the products in the HidrateSpark family that have a 3 inch / 7.6 cm diameter.
There is a '32oz Stainless Steel' version of the bottle which does appear to have a larger diameter (3.8 inch / 9.6 cm) which likely means a different shape of sensor puck so the guide below likely won't work without some modifications.

I have only tested this with the 620ml / 21oz version of the hidrate spark bottle as that's the bottle I have.

## Prep

Several of the steps below involve adhesives with limited setup/cure time.
Take the time to prepare your work piece and have the necessary tools ready.

Read the full document before starting to get an idea of the process.

### BOM

- [ ] [micro qi charge coil](https://www.aliexpress.com/item/3256802090851265.html)
- [ ] AWG 30 or similar wire
- [ ] 4x m2x4mm screws

#### micro qi charge coil

Depending on which site you search, you can find many many different Qi compatible wireless chargers.
It took me a while to find a supplier for incredibly small.

Specifically the `Yellow` version with the 14mm² PCB, not the 10.5mm² pcb.
The smaller PCB was not in stock when I was beginning to source parts but it should work with this design.
The entire design likely could have been simplified if the smaller PCB version was in stock as the 14mm² version is _almost_ small enough to fit **inside** the sensor puck.

#### AWG 30 or similar wire

The sensor puck does not need a lot of current and free space through which to route cables is at a minimum so the smaller the wire the better.

You will need at least 8 inches but longer lengths will make some assembly and test steps _much_ easier.

#### 4x m2x4mm screws

The ones I used came from a "universal" kit. The CAD files assume a screw with these dimensions

//TODO - get dimensions from cad

However, this McMaster part ([91292A004](https://www.mcmaster.com/91292A004/)) is virtually identical so it should work.

### Tools

- [ ] A driver for the m2 screws
  - Required.
- [ ] Super glue
  - **Optional** but highly recommended. See [note](#note-on-adhesives) below.
- [ ] Hot glue
  - Required.
- [ ] 2mm drill bit
  - Required. The diameter does not have to be super precise so long as you can make a hole through which two strands of wire can pass through
- [ ] soldering iron + solder
  - Required. Required to clean up some solder joints on the wireless charge receiver and sensor puck PCB
- [ ] clamp
  - Required. A vice or similar would also work; anything that can securely hold the 3d printed parts to the bottom of the sensor puck for a few hours while the glue sets up will work.
- [ ] bubble level
  - Optional. Use this to check for even/level alignment at a few points in assembly.
- [ ] basic multimeter
  - optional but highly recommended for testing.

#### Note on adhesives

You might be able to get away with just hot glue but I have had poor results with silicone rubber material like the material coating the outside of the sensor puck. Hotglue is _fine_ for everywhere else in this build but I don't think it's the right adhesive to secure the components to the water bottle.

### Parts

Two 3d printed parts. Tolerances are tight and the shapes/dimensions need to be as precise as possible so print as slow as you need to in order to achieve this.

I had good results with my 'stock' prusa mk3s with .4mm nozzle using .15mm layer heights.

Print with at least 3 perimeters
Ironing is a very good idea. This resulted in a NOTICEABLE improvement in surface finish.

## Assemble

This is going to take a while to document :P

## Finish

You will absolutely need to re-calibrate your water bottle after doing this modification.
