# AVR128DA48 LED Blink with PWM

This repository provides an Atmel Studio solution with a bare metal code example for an LED blink driven by a PWM signal. 

The example demonstrates the basic functionality of the PWM peripheral. The output waveform is connected to the on-board LED. The PWM duty cycle value is set at 50%. For half of the period the LED is turned ON, and for the other half the LED is turned OFF.

## Configurations

* PC6 - configured as digital output (the on-board user LED)
* TCA1:
  * Single-slope PWM Mode
  * Compare channel 2 enabled
  * Input clock 4Mhz divided by 16


## Required Tools 

Software: ATMEL Studio and AVR-DA Device Packs

Hardware: AVR128DA48 Curiosity Nano


## Compatibility
The source code is compatible with the following devices: AVR128DA28, AVR128DA32, AVR128DA48, AVR128DA64, ATmega4808, ATmega3208, ATmega1608, ATmega808, ATmega4809, ATmega3209, ATmega1609, ATmega809.
