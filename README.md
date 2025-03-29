# A collection of PCBs I have made

### rp2040-mini
A very small MCU board made around the Raspberry RP2040 ARM mcu

### tmc2208-breakout
A breakout board for the TMC2208 stepper motor driver

### hotplate
A hotplate for soldering  

### thermocouples
A small board with an instrumentation amplifier and support for two thermocouples



# Instructions for me
### Adding ibom
Generate ibom from KiCAD, change following settings:
* Directory: root of repo
* Name format: index
* Additional pcb data: all
* Html defaults: dark mode
* Fields: Datasheet, LCSC/MPN/etc.
  
Go to repo in browser, open settings tab, on the left click pages and select the correct branch

### Automating the creation of ibom and pdf
Use https://github.com/Gherkin/kicad-automation/tree/main   
follow the instructions there
