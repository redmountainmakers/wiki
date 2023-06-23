# 3d Printing

So you want to learn about 3D printing? We have quite a few printers at RMM in many stages of repair. A list of many of them can be found at the bottom of this page. There are usually a few that are able to print attractive plastic objects at any given moment.

<p align="center">
  <a href="images/3d_Printing_Process.png" target="_blank">
    <img src="images/3d_Printing_Process.png" alt="3D Printing Process" width="80%" height="80%">
  </a>
</p>

## Process Overview

3D printers use G-code, a sort of standardized language for CNC machines of all sorts. You start with a 3d design, export a mesh (aka a .3MF or .STL file), and run it through a program called a slicer. The slicer needs to know about the design, the printer, and the material you're going to use in order to do its job. The slicer cuts the mesh into thin slices called layers, figures out how to coordinate all the moving parts of the printer to produce the object you desire, and stores the printer instructions in a gcode file. Getting the best results from a 3D printer depends on knowing about the process in general, the specific printer you're going to use, and how to apply different slicer options to the design you're going to print. Expect to have some failures along the way- it takes some experience to get good at it, but you'll figure it all out with a little practice, and there are experts at the Makerspace who can help you.

## Find a Model

## Make a Model

## Slicer

Slicing software cuts your 3D object into layers that can be stacked to create your object. They can convert solid areas into 3D grids and create extra material to support upper layers with nothing underneath them (like an outstretched arm in a model.) The Slicer outputs a file unique to the 3D printer that you will use. In the case of an FDM Printer, it controls the 3D printer's movement and the speed that it squirts out plastic. Tuning a slicer for a specific printer can take many hours and failed prints. We recommend using PrusaSlicer for machines at RMM, the defaults that come pre-packaged with PrusaSlicer, generally give ok results. Many printers use the G-Code language. You can use a tool like http://gcode.ws to visualize the g-code that a Slicer creates. Here is a reference for writing/debugging G-Code. http://reprap.org/wiki/G-code

Here are a few Slicer packages:

| Name | Cost | Docs | Notes |
| --- | --- | --- | --- |
| [PrusaSlicer](https://www.prusa3d.com/page/prusaslicer_424/) | Free, Open Source | [Documentation](https://help.prusa3d.com/article/general-info_1910#_ga=2.158641402.174293328.1671403790-30271253.1669246106) | Based off Slic3r, highly configurable and very well tuned. A favorite at MMS |
| [Cura](https://ultimaker.com/en/products/cura-software) | Free, Open Source | [Web Help](https://ultimaker.com/en/resources/20406-installation-cura-2-1) | Great for Ultimaker printers, more versatile but lower print quality than PrusaSlicer |
| [Simplify3D](https://www.simplify3d.com/) | About $150 | [Web Help](https://www.simplify3d.com/support/) | Haven't tried it |
| [ChituBox](https://www.chitubox.com/en/index) | Free/Premium license, closed | [Web Help](https://manual.chitubox.com/) | Required slicer for Chitu ecosystem resin printers |


## Upload and Print

## Machines at the space

### Functioning Machines:
* Voron V2.4 350mm with Revo Nozzle (http://voron-350.local/)
* Ender 3 (SD card)

### Non-Functioning Machines:
* Voron V0 (http://3dp-v0-450.local/)
* 2x Ender 3's
* Custom delta





