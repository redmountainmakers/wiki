# 3d Printing

So you want to learn about 3D printing? We have quite a few printers at RMM in many stages of repair. A list of many of them can be found at the bottom of this page. There are usually a few that are able to print attractive plastic objects at any given moment.

## Contents
1. [Process Overview](#process-overview)
2. [3d Printer Types](#3d-printer-types)
3. [Find a Model](#find-a-model)
4. [Make a Model](#make-a-model)
5. [Slicer](#slicer)
6. [Upload and Print](#upload-and-print)
7. [Machines at RMM](#machines-at-rmm)

<p align="center">
  <a href="images/3d_Printing_Process.png" target="_blank">
    <img src="images/3d_Printing_Process.png" alt="3D Printing Process" width="80%" height="80%">
  </a>
</p>

## Process Overview

3D printers use G-code, a sort of standardized language for CNC machines of all sorts. You start with a 3d design, export a mesh (aka a .3MF or .STL file), and run it through a program called a slicer. The slicer needs to know about the design, the printer, and the material you're going to use in order to do its job. The slicer cuts the mesh into thin slices called layers, figures out how to coordinate all the moving parts of the printer to produce the object you desire, and stores the printer instructions in a gcode file. Getting the best results from a 3D printer depends on knowing about the process in general, the specific printer you're going to use, and how to apply different slicer options to the design you're going to print. Expect to have some failures along the way- it takes some experience to get good at it, but you'll figure it all out with a little practice, and there are experts at the Makerspace who can help you.

## 3d Printer Types

There are many different kinds of 3D printers. RMM primarily uses two types of additive manufacturing: filament-based printers using FDM (Fused Deposition Modeling) or FFF (Fused Filament Fabrication) technology, and resin printers using MSLA (Masked Stereolithography) technology.

Both types of technology have quirks that make them nothing like traditional 2D printers where you can simply press “print” and expect a finished product in seconds with little to no complication. Objects can take several hours or even days to print depending on their size and complexity. Settings in your slicer, the model you are printing, the material used, and your preparation can make the difference between success and failure. While 3D printing has gotten substantially more accessible in the past few years you will still need to experiment and troubleshoot to achieve the best results.

### FDM/FFF
FDM/FFF printers operate like hot glue guns that apply a thin layer of melted plastic on top of the print bed and previously deposited layers. The melted plastic is quickly cooled by a fan to solidify in place. This is by far the most accessible and common method of 3D printing on the market today. It is great for rapid prototyping and larger decorative items and is very versatile because of the variety of possible materials that can be used. This technology is also relatively easy to scale into larger format machines allowing for large build volumes. Due to the nature of melted plastic, this method suffers when encountering steep overhangs so support material is often required to achieve optimal results of complex geometries. This technology also struggles with very fine details and produces noticeable layer lines in completed parts.

### MSLA
MSLA printers use a photopolymer resin which cures with exposure to UV light. A high-power UV LED shines through an LCD screen which masks off the light to only cure very precise parts of the liquid resin. The very fine control of light allows for incredible detail comparable to injection-molded plastic parts. This technology is very difficult to scale up in size which limits the build volume far more than on FDM printers. Additionally, while the cured resin is completely safe to handle, the liquid resin is very toxic and can be quite damaging to the environment so care is required both during and after printing to limit exposure to uncured resin.

## Find a Model

There is a vast array of 3d models available on the internet. www.thangs.com does a decent job of aggregating files from multiple sources, but sites such as www.thingiverse.com, www.printables.com are very popular as well. 

Be forewarned that some of the models at those sites are unprintable on FFF printers like those at the Makerspace. When a model is printable, its author usually posts a photo of the printed object. If you don't see a photo, it may require adjustments to make the object printable. Unprintable models can often serve as inspiration for you to design a better, printable version of the object. Ultimaker has a nice list of model sources here https://ultimaker.com/learn/how-to-find-free-stl-files/

## Make a Model

Todo - Add information on different options for creating a 3d model

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

We are working to migrate all of our printers onto the RMM network. See the Machines list below to check how to access them via the network.

Network connected machines use Mainsail OS as the primary printer interface.

## Machines at RMM

### Functioning Machines:
* Voron V2.4 350mm with Revo Nozzle (http://voron-350.local/) - Side panels need weather stripping and re-attached, bowden for the filter box
* Ender 3 (SD card)

### Non-Functioning Machines:
* Voron V0 (http://3dp-v0-450.local/) - Raspberry pi problems? Door un-attached itself
* 2x Ender 3's
* Custom delta





