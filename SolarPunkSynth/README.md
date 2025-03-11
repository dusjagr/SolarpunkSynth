# Original SolarpunkSynth

This is the original version of the SolarpunkSynth - a solar-powered synthesizer designed for workshops and DIY enthusiasts.

<img src="../photos/SolarpunkSynth_finished.jpg" width="400" alt="Original SolarpunkSynth">

## Features
- Simple and elegant PCB design
- Perfect for beginners and workshops
- Complete documentation and assembly instructions included
- Ultra-low power consumption (<0.5mA)
- Three interdependent oscillators

## Directory Contents
- `/002_SolarPunkSynth_footprints.pretty/` - Custom footprints for the PCB
- `/MASK/` - PCB mask files and design assets
- `/instructions/` - Detailed assembly guides and schematics
  - `SolderInstruction.pdf` - Step-by-step soldering guide
  - `SolderInstruction.svg` - Vector version of instructions
  - `SolarSynth_schema.jpg` - Circuit schematic
  - `DSSC_Synthminimal_schema.pdf` - Minimal schematic version
- `/svg2shenzhen/` - SVG files for PCB artwork

## Detailed Step-by-Step Assembly Instructions

Detailed soldering instructions are provided to help you build your own SolarpunkSynth:

<img src="./instructions/SolerInstructions_web.jpg" width="600" alt="Soldering Instructions">

### Bill of Materials
- 1x PCB board
- 1x IC socket (14-pin DIP)
- 1x 74HC14 hex Schmitt trigger IC
- 3x Piezo discs
- 1x 3.5mm audio jack
- 1x 9V battery clip or solar cell connector
- Resistors:
  - 1x 1M ohm
  - 1x 470K ohm
  - 1x 330K ohm
  - 2x 100K ohm
  - 1x 10K ohm
- Capacitors:
  - 3x 0.1μF (ceramic)
  - 2x 10μF (electrolytic)

### Tools Required
- Soldering iron
- Solder (lead-free recommended)
- Wire cutters
- Tweezers (optional but helpful)
- Multimeter (for troubleshooting)

### Assembly Steps

#### 1. Prepare Your Workspace
- Find a well-ventilated area with good lighting
- Have all components sorted and ready
- Make sure your soldering iron is heated and ready

#### 2. Begin with Resistors
- Start by soldering the resistors first, as they are the lowest-profile components
- The resistors go in the positions marked on the PCB silkscreen
- Bend the resistor leads at 90° angles to match the hole spacing
- Insert them flush against the board
- Solder each connection and clip excess leads

#### 3. Add Capacitors
- Next, add the ceramic capacitors (0.1μF)
- For the electrolytic capacitors (10μF), make sure to observe the correct polarity - the negative side is marked with a stripe and should match the marking on the PCB

#### 4. Install the IC Socket
- Orient the socket so the notch matches the silkscreen
- Solder two opposite corner pins first to secure it in place
- Then solder the remaining pins

#### 5. Add the Audio Jack
- Insert the 3.5mm audio jack into its designated position
- Ensure it's sitting flat against the board
- Solder all pins securely

#### 6. Attach Piezo Discs
- Each piezo disc should be connected to its marked position
- The discs can be connected directly to the PCB or with short wires for flexibility
- For direct mounting, solder the piezo disc connections directly to the board
- For flexible mounting, solder short wires to the piezos and then to the board

#### 7. Connect Power
- Attach the battery clip or solar cell connector
- Make sure to observe correct polarity (red wire to + and black wire to -)

#### 8. Insert the IC
- Only after all other components are soldered, insert the 74HC14 IC into the socket
- Make sure the notch on the IC aligns with the notch on the socket
- Press firmly but gently to seat the IC properly

#### 9. Testing
- Connect a 9V battery or solar cell
- Plug headphones or an amplifier into the audio jack
- Tap or apply pressure to the piezo discs to create sound variations
- The circuit should immediately start generating sound

#### 10. Troubleshooting
If the circuit doesn't work:
- Check all solder joints for cold solder or bridges
- Verify the IC is correctly oriented and seated properly
- Confirm proper polarity of electrolytic capacitors and power connection
- Test voltage at various points with a multimeter
- Ensure the piezo discs are properly connected

### Playing Your SolarpunkSynth
- The synthesizer creates sounds through the interaction of three oscillators
- Each piezo disc influences one oscillator
- Try tapping, pressing, or even breathing on the piezo discs to change the sounds
- Experiment with different light intensities on the solar cell to alter sound characteristics
- Try connecting different audio outputs (headphones, amplifiers, speakers)

## Workshop Tips
- Recommended for groups of 5-15 participants
- Workshop duration: 2-3 hours
- No prior electronics experience required
- Tools needed: Soldering iron, solder, wire cutters

## Workshop Experience

<img src="../photos/Workshop_collage.jpg" width="600" alt="SolarpunkSynth Workshop Experience">

The SolarpunkSynth has been successfully used in numerous workshops, helping participants learn about electronics, solar power, and sound synthesis in an engaging hands-on environment.

## License
This project is licensed under the CERN Open Hardware License Version 2 - Permissive (CERN-OHL-P v2).
