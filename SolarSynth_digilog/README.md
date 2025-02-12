# SolarpunkSynth Digilog Edition

This is the Digilog edition of the SolarpunkSynth, specially developed for the Digilog exhibition in Taipei, Taiwan. This version features an artistic PCB design while maintaining the core functionality of the original SolarpunkSynth.

<img src="../photos/SolarpunkSynth_digilog_3d.jpg" width="400" alt="SolarpunkSynth Digilog Edition">

## Features
- Enhanced PCB design with digital-inspired aesthetics
- Artistic circuit traces and visual elements
- Exhibition-ready presentation
- Improved audio output stage with op-amp buffer
- Ultra-low power consumption (<0.5mA)

## Technical Enhancements
- Added MCP6002 dual op-amp for better audio output buffering
- Enhanced signal conditioning with additional filtering
- Modified component values for improved stability
- Custom footprint library optimized for artistic PCB layout
- Polarized capacitors for better power filtering

## Directory Contents
- `/3d_models/` - 3D models of components for visualization
- `/gerber/` - Manufacturing files for PCB production
- `/svg2shenzhen/` - Custom PCB artwork files

## Exhibition History
- Digilog Exhibition, Taipei, Taiwan
- Part of the exploration of digital aesthetics in analog circuits
- Demonstrates the intersection of art and technology

## Technical Specifications
- Based on 74HC14 hex-inverter chip
- Three coupled oscillators using piezo discs
- MCP6002 dual op-amp for audio buffering
- Solar-powered operation
- 3.5mm audio output
- Artistic PCB design with custom traces

## Manufacturing Notes
- Gerber files are provided in the `/gerber/` directory
- PCB specifications:
  - 2-layer board
  - Custom silkscreen artwork
  - ENIG finish recommended for best aesthetic results

## Assembly
While the assembly process is similar to the original SolarpunkSynth, this version includes additional components:
1. MCP6002 dual op-amp in DFN-8 package
2. Additional filtering capacitors
3. Modified resistor values for the op-amp stage

Please refer to the schematic for detailed component values and connections.

## License
This project is licensed under the CERN Open Hardware License Version 2 - Permissive (CERN-OHL-P v2).
