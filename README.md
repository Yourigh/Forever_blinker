# Forever_blinker
Electronics design that blinks a LED for months on AA battery

# Current state
Blinker esign is tested and works well. 
ATTINY variant was not verified.

# Power supply
Boost converter is used to create 3.3 V (handles about 30mA load) and has low Iq. (<20uA)

# Two options
Primary assembly option is an op-amp oscillator. Tested and working.

Another option is to use ATTINY85 and program it to do the same job. (not elaborated in this repository yet)