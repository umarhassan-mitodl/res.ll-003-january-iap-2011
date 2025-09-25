---
content_type: page
description: This page describes the radar design, presents instructions for a sequence
  of experiments, and links to final results from the student teams.
learning_resource_types:
- Projects
ocw_type: SupplementalResourceSection
title: Projects
uid: aa720747-bfe2-cb8b-c637-a22b7f6f4103
---

Students will work in teams of 3 to build their radar, and conduct a sequence of experiments as the radar kit is implemented. You will bring your radar kit into the field and perform additional experiments such as measuring the speed of passing cars or plotting the range of moving targets. A final SAR imaging contest will test your ability to form a SAR image of a target scene of your choice from around campus; the most detailed and most creative image wins.

Radar Features
--------------

*   Coherent FMCW architecture
*   S-band
*   Uses coffee cans for transmit and receive antennas
*   6 mini-circuits components
*   1 quad op-amp as video gain stage and anti-alias filter
*   Analog ramp generator with trigger output
*   Connects to audio input of your computer for digitization of video and triggering
*   Records a .wav file of your experiments
*   MATLAB® scripts read the .wav files and sort out triggered pulses and groups of pulses to process the 3 modes of operation
*   3 modes of operation include; doppler vs. time, range vs. time, Synthetic Aperture Radar imaging

Radar Design
------------

_NOTE_: the block diagram and parts lists below specify a MAX414CPD+ quad op-amp, which is no longer manufactured. Any quad op-amp will work, such as a TI LM324.

Radar System design slides: block diagram, schematics, bill of material, and fabrication instructions ({{% resource_link 12391162-c1f8-fe2b-3e28-44a8c5794fde "PDF - 4.6MB" %}})

Block diagram (high resolution image) ({{% resource_link 04ac574b-7f80-34ef-3832-511e2fbd69b9 "JPEG" %}})

Circuit schematics (high resolution image) ({{% resource_link 229c579d-666d-cb34-c908-92607f4e6809 "JPEG" %}})

MATLAB is presumed installed on your laptop. Some MATLAB code is supplied below for each experiment. (The utility dbv.m is a function which takes the 20\*log10(abs(your radar signal)) — used throughout the experiments.)

Experiments
-----------

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
EXPERIMENTS
{{< thclose >}}
{{< thopen >}}
SUPPORTING FILES
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}
Experiment 1: Doppler vs. time ({{% resource_link 7eb87430-d117-7b13-aa1e-109a17b6c279 "PDF" %}})
{{< tdclose >}}
{{< tdopen >}}
MATLAB and sample WAV ({{% resource_link d3af93ce-46ee-dd15-8733-5b1c62712346 "ZIP - 5.7MB" %}}) (This ZIP file contains: 2 .m files and 1 .wav file.)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Experiment 2: Ranging vs. time ({{% resource_link 79971a28-0ef1-714d-bff6-2f9cf104ee04 "PDF" %}})
{{< tdclose >}}
{{< tdopen >}}
MATLAB and sample WAV ({{% resource_link 9ef20c7d-60c4-335a-a045-292cc0520033 "ZIP - 12.5MB" %}}) (This ZIP file contains: 2 .m files, 1 .wav file and 1 .tif image.)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Experiment 3: SAR imaging ({{% resource_link c5e89e34-d0af-fe08-2075-ec25449777ff "PDF" %}})
{{< tdclose >}}
{{< tdopen >}}
MATLAB and sample WAV ({{% resource_link 22f9536b-6536-1a75-c261-6843cac27654 "ZIP - 44.7MB" %}}) (This ZIP file contains: 1 .jpeg image, 3 .m files, 1 .wav file and 2 .mat files.)
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Selected Final Results
----------------------

Presentation of student field experiment final results ({{% resource_link 38ec8828-ee8e-9ac4-edd6-67d919de8fb8 "PDF - 4.5MB" %}})

Selected student team websites

*   [Team 1](https://web.archive.org/web/20110417013040/http://web.mit.edu/kimt/www/radar/
    ) (winner of the class imaging contest)
*   [Team 2](http://goretkin.blogspot.com/)