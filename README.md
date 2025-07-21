# PCLA

This is the code associated to all on chip Partially Coherent Light Analyser (PCLA) experiments.

## Controlling the chip
To controll the AMF chip we use several libraries made specifically for this usage: <br/>
-> *Phox*: Allows python to interact with different serial devices (camera, stage, lasers, photodetectors) and the DAC, which sets the voltage on each phase shifter of the chip.<br/>
-> *Interface MZI mesh*: User interface and python controller to set phase shifters voltage using a calibration file.

## Experiments
The different files show how to:<br/>
-> Do basic voltage set and first interferograms. <br/>
-> Obtain the calibration file needed for *Interface MZI mesh*.<br/>
-> Figure 2. Tomography and power optimization.<br/>
-> Figure 3. Power optimization on a distance sweep.
