---
layout: project
resources:
  - icon: ti-youtube
    name: YouTube
    content: Time-lapse of the machine in action
    url: https://www.youtube.com/watch?v=4Yg3GeWl18o
  - icon: ti-book
    name: PDF
    content: Project paper
    url: https://pdfhost.io/v/2NcSCyIzB_PickandPlaceMachineBasedona3DPrinterPaper
  - icon: ti-github
    name: GitHub
    content: Project repository
    url: https://github.com/Attrup/PNP42
---

**Pick-and-place technology (PNP) is centered around the goal of autonomously placing electrical components on a printed circuit boards (PCB) with high precision and speed. But the technology is quite expensive and thus many students and maker-spaces has no access to it. To combat this [Jonas Attrup](https://github.com/Attrup), [Mikkel Berrig](https://github.com/mikkelBerrig) and I set out construct a more affordable solution by turning an old 3D printer into a fully functional PNP Machine.**
    
We used an old decommissioned 3D Printer which we stripped down to its mechanical axes leaving only the stepper motors and limit switches in place. We then installed a Juki 503 nozzle, a generic vacuum pump, two 720p cameras, two LED ring-lights, and arduino Mega R3 with a Ramps 1.6 Shield and four DRV8255 stepper drivers and a metal sheet on the build plate (some of the parts were mounted using custom 3D printed pieces). Everything was then connected to a laptop running the open source software [OpenPNP](https://openpnp.org/). For more details about the build process and configuration of the machine, we have written [a short paper](https://pdfhost.io/v/2NcSCyIzB_PickandPlaceMachineBasedona3DPrinterPaper) about it.

### Results
To test the machine we manufactured our own test PCB featuring components ranging from 0603 to SOIC-8 packages. the image below is from a test with double-sided tape on the PCB that shows very satisfactory results. The following tests we did with solder paste turned out very similarly. When reflowed all the diodes was blinking as expected, except for D18 even though the diode was placed correctly – maybe you can see why?

<img src="{{ site.baseurl }}/assets/images/projects/pnp_pcb.jpg" class="img-fluid w-100 rounded">
