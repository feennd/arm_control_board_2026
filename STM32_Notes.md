STM32 Notes



**BOOT0 Pin** - Determines if MCU bootloader will be enabled

IF BOOT0 = LOW : Bootloader is not enabled (Runs whatever code was previously on it)

IF BOOT0 = HIGH : Bootloader is enabled (Ready to be flashed via USB, UART, etc.)



**VBAT Pin** - Backup Power Domain

Powers -> real-time clock, backup registers, backup SRAM, external crystal oscillator (HSE)



**VDDA Pin** - Powers Analog circuitry (ADC, DAC, etc.)



VCAP1\&2 Pins - Outputs of the STM's internal LDO (Low-Dropout regulator 3.3V -> 1.2V). 

External caps stabilize the LDO

