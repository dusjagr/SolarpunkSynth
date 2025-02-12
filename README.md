# SolarpunkSynth 🌞🎹

A solar-powered synthesizer that creates experimental sounds, rhythmic patterns, and beats using minimal energy from the sun! This project embodies the spirit of solarpunk by combining sustainable energy with creative expression.

![Finished SolarpunkSynth](./photos/SolarpunkSynth_finished.jpg)

## Description

The SolarpunkSynth is an ultra-low power consumption synthesizer that can be powered by:
- Silicon solar cells
- DIY DSSC (Dye-sensitized solar cells)
- Alternative power sources (mud batteries, potato power, coconut energy)
- Nearly depleted batteries (due to extremely low power requirements)

## Project Variants

This repository contains two versions of the SolarpunkSynth:

### 1. Original SolarpunkSynth
Located in [`/SolarPunkSynth`](./SolarPunkSynth)
- The original version of the solar-powered synthesizer
- Simple and elegant design
- Perfect for beginners and workshops
- Includes complete documentation and assembly instructions

### 2. Digilog Edition
Located in [`/SolarSynth_digilog`](./SolarSynth_digilog)
- Enhanced version with digital-inspired aesthetics
- Developed for the Digilog exhibition in Taipei, Taiwan
- Features artistic PCB design with custom graphics
- Same core functionality with a unique visual style

![SolarpunkSynth Digilog Edition](./photos/SolarpunkSynth_digilog_3d.jpg)

## Technical Details

The synthesizer is built around these key features:
- Based on hex-inverter chip (74HC14)
- Three interdependent oscillators coupled through piezo discs
- Ultra-low energy consumption (<0.5mA)
- Audio output via 3.5mm jack
- Organic, variable rhythms through unstable circuit states
- KiCad PCB design files included

### Schematic
![SolarSynth Schema](./SolarPunkSynth/instructions/SolarSynth_schema.jpg)

You can also view the [minimal schematic as PDF](./SolarPunkSynth/instructions/DSSC_Synthminimal_schema.pdf).

## Assembly Instructions

Detailed soldering instructions are provided to help you build your own SolarpunkSynth:

![Soldering Instructions](./SolarPunkSynth/instructions/SolerInstructions_web.jpg)

For complete assembly instructions:
- [Detailed Soldering Guide (PDF)](./SolarPunkSynth/instructions/SolderInstruction.pdf)
- [Soldering Guide (SVG)](./SolarPunkSynth/instructions/SolderInstruction.svg)

## Repository Contents

- [`/SolarPunkSynth`](./SolarPunkSynth) - Original version KiCad files and documentation
  - [`/002_SolarPunkSynth_footprints.pretty`](./SolarPunkSynth/002_SolarPunkSynth_footprints.pretty) - Custom footprints for the PCB
  - [`/MASK`](./SolarPunkSynth/MASK) - PCB mask files and design assets
  - [`/instructions`](./SolarPunkSynth/instructions) - Assembly guides and schematics
  - [`/svg2shenzhen`](./SolarPunkSynth/svg2shenzhen) - SVG files for PCB artwork

- [`/SolarSynth_digilog`](./SolarSynth_digilog) - Digilog edition KiCad files
  - [`/3d_models`](./SolarSynth_digilog/3d_models) - 3D models of components
  - [`/gerber`](./SolarSynth_digilog/gerber) - Manufacturing files
  - [`/svg2shenzhen`](./SolarSynth_digilog/svg2shenzhen) - Custom PCB artwork files

- [`/photos`](./photos) - Project photos and workshop documentation

## Workshop Information

This project is designed to be beginner-friendly and has been successfully taught in workshops across various locations including:
- Taipei, Taiwan (Digilog)
- Chiang Mai, Thailand
- Tokyo, Japan (FabCafe)

No prior electronics knowledge is required - just enthusiasm for experimental sounds and solar-powered creativity!

![Workshop Collage](./photos/Workshop_collage.jpg)

## Credits

This circuit is a modified version of the StarvationSynth originally developed by Ralf Schreiber and Uwe Schüler. The current version was specifically developed by Marc Dusseiller (dusjagr) to support the exhibition "1,540,000nm DSSC" by Shih Wei-Chieh at FabCafe Tokyo.

## Links

- [Project Wiki](https://www.hackteria.org/wiki/SolarpunkSynth)
- [Hackteria Network](http://hackteria.org/)
- [SGMK](https://mechatronicart.ch/)
- [Bitwäscherei Hackerspace](https://bitwaescherei.ch/)

## License

This project is licensed under the CERN Open Hardware License Version 2 - Permissive (CERN-OHL-P v2). This means you are free to:
- Study
- Modify
- Make
- Distribute

without any obligation to share your changes or modifications.

For more details, see the [LICENSE](./LICENSE) file.
