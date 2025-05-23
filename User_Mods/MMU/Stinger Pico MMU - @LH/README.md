[:arrow_double_down: Download Folder](https://download-directory.github.io/?url=https%3A%2F%2Fgithub.com%2Flhndo%2FLH-Stinger%2Ftree%2Fmain%2FUser_Mods%2FMMU%2FStinger%2520Pico%2520MMU%2520-%2520%2540LH)

# LH Stinger - Pico MMU


![](Assets/lhs_pico_mmu.png)



<br>

## Guide

**Wiki:** https://github.com/lhndo/LH-Stinger/wiki/Pico-MMU

<br>

## CAD

[**Online CAD Viewer**](http://tiny.cc/lhs-pico-mu)

<br>

## Print

![](Assets/2.png)


Filament: PLA, PETG ,ASA etc.  
*The 4 lane version uses 113g of filament in total*

* 0.4mm nozzle, 0.4mm line width, 0.2mm layer height (idler arms at 0.12mm if you can print well)
* 3 perimeters, 95% infill   
  *  It is highly recommended to use the print settings included in the Orca files, and change your speeds and acceleration (includes per object settings and painted seams)
* Make sure your extrusion multiplier is spot on. The tolerances are very small so print some parts and check for fitting. 
* Some slight post processing might be needed.
* The Idler arms have to be printed top face down on a smooth sheet (not textured PEI) 
    - You can improvise by taping a temporary piece of glass, fr4, etc. over your printbed 



<br>


## BOM

Item | Quantity
-|- 
[EMAX ES3004 Servo](https://s.click.aliexpress.com/e/_oDr5to3) [(EMAX)](https://emaxmodel.com/products/emax-es3004-17g-3-5kg-0-13sec-23t-metal-gear-analog-servo-for-rc-airplane-es3104-upgrade)  | 1
[Nema 17](https://s.click.aliexpress.com/e/_DDhtjPj) (max 40mm length) | 1
[Steel D-Shaft 5mm x 90mm](https://s.click.aliexpress.com/e/_ooVBpL1) ** | 2
[Bearing MR115](https://s.click.aliexpress.com/e/_DeqGPvP)  | 4
[Bearing MR83](https://s.click.aliexpress.com/e/_DDpZxF7)  | 4 
[BMG Hardened Drive Gears](https://s.click.aliexpress.com/e/_DErKaQz) (with grub screw) | 4 pairs!
[PTFE Tube 4mm OD, 3mm ID](https://s.click.aliexpress.com/e/_DCqpjY5)  | 1
[ECAS 4 Collet](https://s.click.aliexpress.com/e/_DBXcy4h)  | 8
[Belt GT2 * ](https://s.click.aliexpress.com/e/_okGVowl)  | 25cm 
[Heat Insert M3 5mm (D) x 4mm (L)](https://s.click.aliexpress.com/e/_Dci6SvT)  | 23
Screw Cap Head M3 10mm  | 3
Screw Cap Head M3 22mm  | 2
Screw Cap Head M3 30mm  | 2
Screw Cap Head M3 8mm  | 2
Screw Countersunk M3 10mm  | 12
Screw Countersunk M3 16mm  | 4
Screw Countersunk M3 8mm  | 1
Screw Grub M3 6mm (optional)  | 2

*The belt width used is non-standard ~4mm, which can be easily cut with scissors from a 6mm one  
** Alternatively, you can use round shafts with the following [MOD](https://github.com/lhndo/LH-Stinger/tree/main/User_Mods/MMU/PICO%20MMU%20MODS/Cam%20Shafts%20-%20Round%20ID%20-%20%40LH)
<br>


**Note:**  
 * You will need a free stepper driver on your mainboard, or an [ERCF EASY BRD](https://s.click.aliexpress.com/e/_DB2wsgZ) or [EBB 42](https://s.click.aliexpress.com/e/_DlhszCV) board (connected though USB, Max31865 not required)    
  *Any board that can be flashed with klipper should also work, such as a spare Ender 3 board.*


* [A filament hub and a toolhead filament sensor are also required](https://github.com/lhndo/LH-Stinger/tree/main/User_Mods/MMU/Filament%20Hub%20-%20%40LH)   
  *If you can't find a [built-in solution](https://www.printables.com/search/models?ctx=models&q=pico+mmu+hub), then you can use the [Floating Hub Variant with ECAS connector](https://github.com/lhndo/LH-Stinger/tree/main/User_Mods/MMU/Filament%20Hub%20-%20%40LH) which is universal*


* A toolhead filament cutter (below the extruder) is ***highly recommended*** for reliability.  
  You can find an example [here](https://github.com/lhndo/LH-Stinger/wiki/Pico-MMU#filament-cutters), or other variations on [Printables](https://www.printables.com/search/models?ctx=models&q=filament+cutter+for).

*Feel free to ask in the* [LH Stinger Discord | multi-material](https://discord.gg/EzssCfnEDS) *if there's an existing solution or mod for your extruder or toolhead of choice.*  


![](Assets/4.png)

<br>

## Support


For support please join the [LH Stinger Discord](https://discord.gg/EzssCfnEDS)
