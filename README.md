<p align="center">
  <p align="center">
   <img width="128px" src="Images/Source/LH_Stinger_Logo_512px.png" />
  </p>
	<h1 align="center"><b>LH Stinger</b></h1>
	<p align="center"> <strong>
		A no-compromise cartesian 3D Printer designed for speed and precision, created as a long-lasting platform for those who like to push quality or speed to the extreme.  </strong>
    <br />
    <br />
    <i>~ This project intends to become a community-driven project, not a brand. ~
    <br /> 
    <br />
    Join us: 
    <br />
    </i>
      <a href="https://discord.gg/EzssCfnEDS"> <img  src="Images/disc.png" />  </a>
    <br />
</a>
  </p>
</p>

<br>

![Image of LH Stinger 3D Printer Front View](Images/New_Frame_v1024.png)  

<br>

![GitHub Release](https://img.shields.io/github/v/release/lhndo/LH-Stinger?style=for-the-badge&color=25C2A0)  
Status: **V1.0**  

<br>


[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa] [![DISCORD][s2]][l2] [![YOUTUBE][s5]][l5] [![KOFI][s1]][l1]  

[s1]: https://img.shields.io/badge/Buy%20Me%20a%20Coffeee-d3dsds?logo=ko-fi&logoColor=white&labelColor=red&color=red
[l1]: https://ko-fi.com/lh_eng
[s2]: https://img.shields.io/badge/Discord-asdsadsa?logo=discord&logoColor=white&color=5865F2
[l2]: https://discord.gg/EzssCfnEDS
[s5]: https://img.shields.io/badge/Youtube-8A2323443?logo=youtube&logoColor=red&color=white
[l5]: https://www.youtube.com/@LemurHaze



[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
  
## Contents

- [Features](#features)
- [Resources](#resources)
- [Assembly Instructions](#assembly-instructions)
- [Upcoming Projects](#future-projects)
- [Contact](#contact)
- [Credits](#credits)
- [Support](#support)
- [License](#license)

<br>


## Features
<br>

- Cross Frame design focused on stiffness and stability with a low center of gravity
- Streamlined frame assembly consisting of only six extrusions
- Lightweight bed carriage assembly with carbon fiber components
- AWD stepper configuration for the Y-axis
  - Optional conversion for X-axis AWD setup
- 235 mm^2 x 200mm maximum build volume (easily expandable to other sizes)
  - 200 mm^2 [Carbon Fiber Bed](/DXF) for high-speed setup
  - 235 mm^2 bed support for a larger volume
- Optimized for daily print speeds of 400-600 mm/s with 20.000 mm/s^2 acceleration ([Test A](https://www.youtube.com/watch?v=bxNQv3xVFXA&)) ([Test B](https://www.youtube.com/watch?v=mh0rmYptH-0)) ([Test C](https://www.youtube.com/watch?v=cDipS-Msi5c))
- Motion system capable of 1.000 mm/s speed with 100.000 mm/s^2 acceleration ([Test](https://www.youtube.com/watch?v=Xajs2mky6ZU))
- Maximum volumetric flow rate: ~55-60 mm^3/s ([Test A](https://www.youtube.com/watch?v=K3M1EXKJzKs)) ([Test B](https://www.youtube.com/shorts/JorOoNuft90))
- Built using 30 series T-slotted extrusions with parts up to 3090
- All bracket assembly
- Genuine high-quality motion system components ([BOM](https://docs.google.com/spreadsheets/d/1s8ulLfThmbuy1G_40MvkXXL2oVx9PZhvpAY9hMxqYbg/edit?usp=drive_link))
- Entire motion system based on high preload MGN12H linear guide rails
- Fully belt-driven with minimal belt paths
- 9mm 2GT belt in symmetrical configuration for the Y-axis
- 6mm 2GT belts for the rest of the axis
- Independent Z stepper motors with Z Tilt capability for the X-axis
- Lightweight dual plate [Carbon Fiber Bed Carriage](/DXF) with integrated tensioner and compatible with different bed sizes and carriage configurations
- Rigid carbon fiber bed mount
- Lightweight Polyimide flex PCB 200W [Bed Heater](/PCB/PI%20Bed%20Heater%20-%20200mm)
- Double shear shaft supports for Y and X axis steppers
- High torque LDO-42STH48-2504AC stepper motors supplied with 36V for the X and Y-axis
- Dual power supply supporting 24V and 36V power standards (easily configurable for 48V)
- Driven by the Octopus Pro 1.1 board with TMC2240 drivers
- Running [Klipper](https://github.com/Klipper3d/klipper) firmware
- Fully featured Klipper [Configuration](/Config/Klipper_Config) and [Slicer Profiles](/Config/Orca_Slicer) available
- Easily serviceable [External electronic box](https://github.com/lhndo/LH-Stinger/wiki/Build-Log#electronic-box-design) with good airflow, and support for multiple power supplies, SSRs, RPi and large controller boards.
- Good cable management with a quick disconnect [Breakout Board](/PCB/LHS%20Breakbeat) between the printer and ebox
- Toolhead based on the Dragon HF hotend and HF extender
  - Alternate hotends supported: Dragon UHF, Ace, Mellow NF-Crazy-Volcano HF, Rapido, Goliath ([User Mods](/User_Mods/Toolhead/))
- LDO Orbiter 2.0 direct drive extruder
  - Sherpa Mini supported ([User Mods](/User_Mods/Printer))
- Dual 5015 fan setup for part cooling
- Dual [AUX cooling modules](/CAD/Aux%20Fan) based on 9733 blower fans providing 64 CFM of auxiliary cooling
- Adopts the [Annex Engineering Quickdraw Probe](https://github.com/Annex-Engineering/Quickdraw_Probe)
	- Zero Y offset probe placement for no gantry twist deviation
	- Full bed probe coverage
- Minimalistic [printed part design](/STL) focused on strength and easy printability
- Printed in ASA, providing high temperature resistance
- Easily enclosed, with the main electronic components outside of the build chamber.
  - The 200 mm^2 bed configuration can be fully enclose up to the frame bounding box, with no extra space needed for the bed movement. ([Dimensions](https://github.com/lhndo/LH-Stinger/wiki/Dimensions))

<br>


**Resonance Tests:**<br>
![Resonance Test X](Images/X.png)<br>
![Resonance Test Y](Images/Y.png)<br>

<br>

## Resources
<br>

- [**Assembly Guide**](https://github.com/lhndo/LH-Stinger/wiki/)
- [**BOM/Kits**](https://docs.google.com/spreadsheets/d/1s8ulLfThmbuy1G_40MvkXXL2oVx9PZhvpAY9hMxqYbg/edit?usp=drive_link)  
- [STL Files and Printing Instructions](STL/)  
- [CAD Source Files ](CAD/)
- [Klipper Configuration ](Config/Klipper_Config) 
- [Build Log](https://github.com/lhndo/LH-Stinger/wiki/Build-Log)
- [Videos](https://www.youtube.com/channel/UCPD2Ai4b49gVoCFSGFWoSdw) 

<br>

## Assembly Instructions 

* The [LH Stinger Wiki](https://github.com/lhndo/LH-Stinger/wiki) is a regularly updated and intended to serve as your primary point of reference during the build  

* The main body of documentation can be found in the [**Assembly Guide**](https://github.com/lhndo/LH-Stinger/wiki/Assembly-Guide)  

<br>

*For additional support please join us on the [LH Stinger Discord](https://discord.gg/EzssCfnEDS)*


<br>


## Upcoming Projects

- [LHS Pico MMU](https://github.com/lhndo/LH-Stinger/wiki/Pico-MMU) *(In progress)*  

![LH Stinger - LHS - Pico MMU](https://github.com/lhndo/LH-Stinger/blob/main/User_Mods/MMU/Stinger%20Pico%20MMU%20-%20@LH/Assets/lhs_pico_mmu.png?raw=true)


- Enclosure *(In progress)*

<br>

![LH Stinger Enclosure](Images/lh_stinger_enclosure.png)  

<br>

## Contact

lemurshaze @ gmail.com  

@LH on [LH Stinger Discord](https://discord.gg/EzssCfnEDS)
<br>


## Credits

<br>

**Thanks to everyone in the LH Stinger community who supported the project, contributed in any form, or provided feedback! :purple_heart:**

<br>

_Inspired by the [Annex Engineering](https://github.com/Annex-Engineering) team and [community](https://discord.com/invite/MzTR3zE), along with the [Klipper community](https://discord.klipper3d.org), [RatRig](https://ratrig.com/) and all the crazy people that continue to push bed slingers to the limits. :purple_heart:_

-Toolhead evolved from an amazing design by [Dalegaard](https://github.com/dalegaard)<br>
-Silicon sock mold based on [Renátó Kulman](https://www.printables.com/@RenatoKulman)<br>
-Wago 221 mounts by [fns720](https://www.printables.com/@fns720)<br>
-SSR protection cover based on [Technoturk](https://www.printables.com/@Technoturk_377911)<br>
-3030 extrusion Cable clip based on [Arthur_C](https://www.printables.com/@Arthur_C_428094)<br>
-3030 t-nut clip based on [John_S](https://www.printables.com/@JohnS)<br>
<br>

## Support

<a href='https://ko-fi.com/P5P7PF0ED' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://storage.ko-fi.com/cdn/kofi6.png?v=6' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>


## License


This work is licensed under a [Creative Commons (4.0 International License)  ](https://creativecommons.org/licenses/by-nc-sa/4.0/)  
[**Attribution—Noncommercial—Share Alike**](LICENSE.md)  
<br>
<img src="Images/CC.jpg" width="100">  
<br>
