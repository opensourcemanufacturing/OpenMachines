# OpenMachines

We created this project in hopes that it becomes a seed for the collection and curation of good known open source solutions for DIY and Industrial Mods for Open Source Machines and Processes

The objective of this github organization is to challenge the industry status quo and establish crowdsourced standards based on the idea of [Citizen Science](https://en.wikipedia.org/wiki/Citizen_science)

We believe in free proven knowlage with proper source and respective [kudos](https://en.wikipedia.org/wiki/Kudos), design exploration by iteration, [serendipity](https://en.wikipedia.org/wiki/Serendipity), reuse promotion and propagation of great design ideas. 

MOTTO: ["Don't Reinvent The Wheel, Unless..."](https://blog.codinghorror.com/dont-reinvent-the-wheel-unless-you-plan-on-learning-more-about-wheels/)

------------------------------------------------------------

# 3D Printing

## SLA (Resin Printing)

#### RESIN EXPOSURE THEORY
- [What is and how to take a working curve Mesurement](https://www.instructables.com/id/How-to-Take-a-Working-Curve-Measurement-and-Create/)
- [Testing Resin Layer Heighs - Study (Moai)](https://forum.peopoly.net/t/in-search-for-the-perfect-layer-height/1956/19)
- [Anti-Aliasing AKA Subpixel Printing](https://hackaday.com/2016/07/26/get-subpixel-printing-with-a-dlp-3d-printer/)
- [Variable height layer printing](https://www.instructables.com/id/Variable-Slicing-for-3D-Printing-on-Autodesk-Ember/)
- [Microstructure Control in 3D Printing with Digital Light Processing](https://onlinelibrary.wiley.com/doi/full/10.1111/cgf.13807)


#### TYPES OF RESIN PRINTERS
- [Differences between: MSLA, LASERSLA, DLP](https://theorthocosmos.com/laser-sla-vs-dlp-vs-masked-sla-3d-printing-technology-compared/)

#### RESIN CALIBRATION TOOLS
- [GO-NOGO Resin tolerance Testing model](https://www.thingiverse.com/thing:3425486)
- [Resin Exposure Finder for CBDDLP based printers](https://github.com/altLab/photon-resin-calibration)

#### LCD / DLP Light Masking
- [The single point light falloff problem](http://robotsinthesun.org/dlp-printer-brightness-distribution/)
- [DLP 3D Printer Grayscale Mask compensation tool (OpenSource)](https://www.youtube.com/watch?v=YQwzc8kL0lE)

### Laser Printers

#### Formlabs Form1+

- [Form 1+ Guide (Forum Post)](https://forum.formlabs.com/t/retro-form-1-guide/16904)
- [The Unofficial Form1 wiki](http://form1printer.pbworks.com/w/page/73436192/The%20Unofficial%20Form1%20wiki)
- [Resin Curve Mesuring on the Form](https://www.instructables.com/id/Making-a-Working-Curve-Measurement-on-the-Form1/)
- Older Versions of Preform slicer: [[link_1]](http://form1printer.pbworks.com/w/page/73473032/PreForm%20Tips%2C%20Tricks%2C%20and%20Version%20History?fbclid=IwAR3Lqit8WW5Hi2pzdmGExpFBITcG-LmejZf46HYJqN-EKS-17r2-xSBpCXY) [[link_2]](https://forum.formlabs.com/t/preform-older-versions/9686)
- [Even More Versions of Preform Slicer](https://drive.google.com/drive/folders/1k1C6QDv6CbEVsz6t-EJ6ZldKd1dDOsOs?usp=sharing)
- [X3msnake's Form1+ Photo Album](https://photos.app.goo.gl/cRBBhAM5fRQmBn516)
- [Cleaning galvo mirrors(pdf)](https://drive.google.com/file/d/1OTlYEJEhUNQy2icWgix25pufBiY5hfss/view?usp=sharing)
- [bunnie studios: Formlabs Form1 Teardown](https://www.bunniestudios.com/blog/?p=3110)

*Vat Options*
- [Vat alternatives for Form1](https://forum.formlabs.com/t/peopoly-moai-fep-vat-in-form1-1-without-mechanical-levelling/22369?u=x3msnake) + Tweaking the plate offset to any value you want without mechanical releveling
- [Make your own resin Vat for SLA 3D printer Tutorial (YouTube)](https://www.youtube.com/watch?v=RHTgHzDQbSY)
- [Replace PDMS on SLA/DLP 3D Printer Resin Vat (YouTube)](https://www.youtube.com/watch?v=EGx6IRry8A4)
- [lavachemist's FDM Printable FEP Vat (for Moai or Form1/1+)](https://grabcad.com/library/peopoly-moai-fep-vat-fdm-printed-1)

*OpenFL*
- [OpenFL Community Fork](https://github.com/opensourcemanufacturing/OpenFL)
- [OpenFL Presentation Slides(pdf)](https://drive.google.com/file/d/103EEdEtRmRZBrON2qWw3zj79ZxmcAH9d/view?usp=sharing)
- [Form1+ MIDI (YouTube)](https://www.youtube.com/watch?v=B47mw2BhGRU)
- [Form1+ OpenFL Script Example (YouTube)](https://www.youtube.com/watch?v=y5U8yBGLMaA)

*Other Useful F1/1+ Hacking Links*
- [CTC Riverside (F1+ Clone) Hacking](https://groups.google.com/forum/#!topic/ctc3dprinters/PbFQm_7dXcs%5B1-25%5D)
- [CTC Riverside (F1+ Clone) F1+ Firmware](https://void.in.ua/ctc/)

![preform_diagnostics_mode](http://form1printer.pbworks.com/f/1393518844/laser_spot_test.jpg)

Preform has a "diagnostic" mode which can be accessed by adding  -diagnostic as a command line parameter, either running it from the command window, or by adding it into windows shortcut properties. This adds an extra menu to preform 


#### Peopoly Moai

- [CAD Source Files](https://wiki.peopoly.net/doku.php?id=moai-design) - Vats, Panels, Tilt System and structure
- [FEP Vat Fusion 360 File](https://a360.co/2EZiATj)
- [Testing Resin Layer Heighs - Study](https://forum.peopoly.net/t/in-search-for-the-perfect-layer-height/1956/19)

#### Pegasus Touch

- [JailBreak Firmware and potential source for open SLA Galvo controller](https://github.com/doobie42/OpenPegasus)
- [FSL Pegasus Touch Support videos - Youtube](https://www.youtube.com/playlist?list=PLRhV54_kAGWTsPdzRNcGqUWNiridHccYr)
- [Pegasus Calibration Sheet](https://github.com/doobie42/OpenPegasus/files/3299381/calibration_pattern.pdf)
- [X3msnake's Pegasus Touch Photo Album](https://photos.app.goo.gl/jAxs5vE5puoAWkZZ8)

### DIY Galvos

- [smoothieboard based galvo controller](https://www.reddit.com/r/3Dprinting/comments/fh69dk/i_modified_smoothieware_to_add_support_for_using/)
- [LASER GALVO CONTROL VIA MICROCONTROLLER’S DAC](https://hackaday.com/2018/02/15/laser-galvo-control-via-microcontrollers-dac/)

### LCD Pinters

#### DIY OpenSource Kits 

- [Makerbase MSLA (DLP)](https://github.com/makerbase-mks/Datasheet/blob/master/Chinese%20datasheet/MKS%20DLP%E4%B8%BB%E6%9D%BF%E4%BD%BF%E7%94%A8%E6%89%8B%E5%86%8C.pdf), [Github Project](https://github.com/makerbase-mks/MKS-DLP)

#### Anycubic Photon

- [Photon Community Hub](www.photonsters.org)
- [X3msnake's Photon Photo Album](https://photos.app.goo.gl/24FuZ97FUJk6An763)

#### Nova3D Elfin

- [Nova3D Elfin Knowledgebase](https://github.com/opensourcemanufacturing/Nova3D-Elfin)
- [Chitubox Plugin](https://github.com/opensourcemanufacturing/Nova3D-Elfin-Chitubox-Plugin)

#### Phrozen Sonic Mini

- [Printer Review & R&D Photo album](https://www.facebook.com/permalink.php?story_fbid=10158387611698680&id=651553679)*(x3msnake)*
- [3D printable Vat (thinguiverse)](https://www.thingiverse.com/thing:4269287)*(LilAtomicX10)*

#### SparkMaker

- https://github.com/bastirichter/Sparkmaker/blob/master/file_format.md
- https://www.thingiverse.com/groups/sparkmaker/forums/general/topic:27837
- https://github.com/bacintom/WowFileTools
- https://github.com/Godzil/WoWTools
- https://www.thingiverse.com/groups/sparkmaker
- https://n0sr3v.github.io/SLAcer.js/

#### Kelant S400
- https://github.com/loneacoustic/kelants400
- https://github.com/Kelant3D/Kelant-S400

### FDM Printers

- https://marlin3dprintertool.se/

------------------------------------------------------------
# 3D Scanning

ToDo: http://www.altlab.org/d/m/x3msnake/knowlagebase/digitizing

## Photogrametry

- [OpenScan Photogrametry Project by Thomas Samoht](https://www.openscan.eu/?lang=en) - [Facebook Group](https://www.facebook.com/groups/142108429832711/)

## Depth Mapping

## Laser Scanning

## Structured Light Scanning

------------------------------------------------------------
# CAD Software

> OS: Open Source | FW: Freeware | CM: Comercial

- OS - https://www.freecadweb.org/
- OS - http://www.openscad.org/
- OS - https://librecad.org/
- OS - http://solvespace.com/index.pl
- OS - https://www.qcad.org/en/
- OS - https://github.com/xibyte/jsketcher
- FW/CM - https://www.autodesk.com/campaigns/fusion-360-for-hobbyists
- FW/CM - https://www.onshape.com/products/free
- OS - [Open Multiformat 3D Model Viewer](http://www.open3mod.com/) - [full supported formats list here](http://assimp.sourceforge.net/main_features_formats.html)

------------------------------------------------------------
# MODELLING / ANIMATION Software

> OS: Open Source | FW: Freeware | CM: Comercial

- OS - https://www.blender.org/
- OS - https://www.bforartists.de/ (blender fork with better ui)
- OS - https://abau.org/dilay/ (Clay Modelling)
- OS - https://stephaneginier.com/sculptgl/ (Clay modelling online/offline)
- FW - http://pixologic.com/sculptris/ (Clay Modelling)


------------------------------------------------------------

# Surface Finish

- [Anodizing 720 calculator with metric by Kreutz on CNC Zone] (https://www.cnczone.com/forums/mass-finishing-equipment-media-stratigies/155745-software.html)
- [OpenMachines Backup > 720RuleCalculatorRev001.zip](https://github.com/opensourcemanufacturing/OpenMachines/files/3101791/720RuleCalculatorRev001.zip)


