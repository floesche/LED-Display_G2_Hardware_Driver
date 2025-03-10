---
title: LED matrix
parent: Generation 2
nav_order: 5
---

# Custom LED matrix boards

Different pre-fabricated LED matrices are available, but their emitted light spectrum is not always well specified, might differ between production batches, and don't always align well with the sensitivity of a drosophila visual system. Around 2013 there was an effort to produce custom LED matrices for [Generation 2]({{site.baseurl}}/G2/) and [Generation 3]({{site.baseurl}}/G3/) display systems. The different versions listed below are plug-in replacements for pre-fabricated LED matrices and designed to be used with the [panel boards]({{site.baseurl}}/Generation%202/Panels/docs/).

1. TOC
{:toc}

## LED array TH 3mm

![LED array through hole 3mm](assets/led_array_th3mm_front.png){:.ifr .pop}
![LED array through hole 3mm](assets/led_array_th3mm_back.png){:.ifr .pop .clear}

The LED array TH 3mm is a LED matrix for through hole (TH) 3mm LEDs (have a [look at the schematics](assets/led_array_th3mm_schematic.pdf)). LEDs from many different manufacturers are available in this packages size.

Historic production ready files are archived at `led_array_th3mm/production_v1/`, yet it is unclear if there was ever a PCB produced.

The folder `led_array_th3mm/objects/` contains a vector graphic file, presumably used to laser cut a spacer to be used on top of the PCB (see [preview pdf](assets/led_array_th3mm_spacer.pdf)).

## LED array TH 5mm

![LED array through hole 5mm](assets/led_array_th5mm_front.png){:.ifr .pop}
![LED array through hole 5mm](assets/led_array_th5mm_back.png){:.ifr .pop .clear}

The LED array TH 3mm is a LED matrix for through hole (TH) 5mm LEDs (have a [look at the schematics](assets/led_array_th5mm_schematic.pdf)). LEDs from many different manufacturers are available in this packages size. Because of the size constraints, only 4×4 LEDs fit on one of these matrices.

Historic production ready files are archived at `led_array_th5mm/production_v1/`, yet it is unclear if there was ever a PCB produced.

The folder `led_array_th5mm/objects/` contains different vector graphic file, presumably used to laser cut masks for the LEDs (see [preview pdf](assets/mask_inner_5mm.pdf)).

## LED array SMD 0805

![LED array SMD 0805](assets/led_array_smd0805_front.png){:.ifr .pop}
![LED array SMD 0805](assets/led_array_smd0805_back.png){:.ifr .pop .clear}

The LED array SMD 0805 is a LED matrix for surface mount devices with a package size of 0805 (have a [look at the schematics](assets/led_array_smd0805_schematic.pdf)). LEDs from many different manufacturers are available in this packages size.

Historic production ready files are archived at `led_array_smd0805/production_v1/`, yet it is unclear if there was ever a PCB produced.

## LED array SMD 1411-0805

![LED array SMD 1411-0805](assets/led_array_smd1411-0805_front.png){:.ifr .pop}
![LED array SMD 1411-0805](assets/led_array_smd1411-0805_back.png){:.ifr .pop .clear}

The LED array SMD 1411-0805 is a LED matrix for surface mount devices with alternating between packages size of 1411 and 0805 (have a [look at the schematics](assets/led_array_smd1411-0805_schematic.pdf)). This LED matrix was designer to use UV and green LEDs in the same matrix. The chosen UV LED by Yuli Tech with a spectrum peak at 365nm and product number __YLUV-365SMD__ has a SMD 1411 package size. There is a wide range of green LEDs in an 0805 package available, such as the Rohm __SML-210MTT86__ with a spectrum peak at 570nm.

Historic production ready files are archived at `led_array_smd0805/production_v0`. The most recently produced version was `led_array_smd1411-0805_v0p2.zip`.

## LED array template

The project folder `led_array_template` contains a 8×8 schematic that can be used as a template to produce different types of PCBs.

## Panel Adaptor

![Panel Adaptor Front](assets/panel_adaptor_front.png){:.ifr .pop}
![Panel Adaptor Back](assets/panel_adaptor_back.png){:.ifr .pop .clear}

The `panel_adaptor` is a small PCB that allows an adaptation between different matrix sized and the [panel board]({{site.baseurl}}/Generation%202/Panels/docs/).

## Panel pass-thru

![Panel pass-thru Front](assets/panel_pass-thru_front.png){:.ifr .pop}
![Panel pass-thru Back](assets/panel_pass-thru_back.png){:.ifr .pop .clear}

The `panel_pass-thru` is a drop in replacement for a single display module. It carries the electrical signal to the next module, but does not display anything. This is similar to the [Generation 4 Window]({{site.baseurl}}/Generation%204/Hardware/docs/comm.html#window), but without the cutout in the center.
