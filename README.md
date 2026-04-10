# 555 LED Badge

A flashing dual-LED badge circuit designed in KiCad 10 as a beginner PCB design project.

## How it works

The ICM7555 CMOS timer runs in astable mode, generating a continuous oscillating signal. The output drives a 2N3904 NPN transistor which switches two red LEDs on and off alternately. Timing is controlled by resistors and capacitors connected to the threshold and trigger pins. The control voltage pin (pin 5) doesn't need a decoupling capacitor with the ICM7555, so it has been marked X.

## Components

- ICM7555 CMOS timer IC (PDIP-8)
- 2N3904 NPN transistor
- 2x red LEDs
- 7x resistors
- 2x electrolytic capacitors
- Slide switch
- 3V battery

## Tools used

*KiCad 10*
