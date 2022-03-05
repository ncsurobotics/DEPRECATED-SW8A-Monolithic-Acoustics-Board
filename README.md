# NCSU Underwater Robotics PCB Files

PCB design files for Seawolf's guts.  The boards are saved in Altium Designer file formats.

*Currently under construction*


**Info for Jan 2022 Acoustics revisions:**
Replaced old components relying on missing libraries. The Acoustics board now uses:
*   1206 components: `stackpole-res` library in acoustics-libs
*   0805 components: `capacitor_murata_0805` and `Panasonic_resistor_0805` in the [Seawolf-Libraries](https://github.com/ncsurobotics/Seawolf-Libraries) repo
*   libraries that are already installed with Altium
