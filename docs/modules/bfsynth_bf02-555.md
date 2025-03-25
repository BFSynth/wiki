# BF-02 555 Oscillator

[[img|modules/images/bfsynth_bf02-555.jpg|100]]

This module is a 555 oscillator based on the famous Thomas Henry schematic. It features 4 different waveform. It is available from BF Synth:

https://www.tindie.com/products/bfsynths/bf-02-analog-powerhouse-555vco-for-ae-modular/

* Power consumption:  mA
* Module width: 2U
* Quickswap compatibility : Mechanical compatibility for now, not fully compatible with the header.

## Inputs

* **Freq** - affects the pitch of the waveform
* **Sync** - reset the waveform each time it's going low, usually used with a external oscillator to introduce distortion
* **PWM** - change the square waveform PWM ratio
* **Lin** -  affect the pitch, reacting linear to the CV signal
* **Exp** -  affect the pitch, reacting exponentialy to the CV signal

## Outputs

Bottom left
* **Bus Gate** - this is actually the bus Gate derived from the midi input on the master module (NEED UPDATE on QS)
* **Bus CV** - this is actually the bus CV derived from the midi input on the master module (NEED UPDATE on QS)

Top Right
* **TRI** - triangle waveform output
* **SAW** - saw waveform output
* **SIN** - sinusiodal waveform output
* **SQR** - square waveform output

## Controls

* **Coarse** - sets the main pitch of the sound, affected by the CV Freq, Lin and Exp CV input
* **Fine** - affect the pitch, used to tune the oscillator more precisely
* **PWM** - Set the PWM ratio for the square waveform
* **PWM CV** - define the CV input impact on the PWM ratio fixed by PWM control
* **Lin FM** - define the Lin input impact on main pitch
* **Exp FM** - define the Exp input impact on main pitch

## Patch Suggestions

RSKT's Tutorial: 

%embed% https://www.youtube.com/watch?v=g1ed_4M4sXk %%

