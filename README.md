# KEYPAD_DRIVER
Generic Keypad Driver - Ready to use for any microcontroller 

## Driver description
Our driver has only one main function for standard keypad:

- KEYPAD_getPressedKey()

Description :

- Gets the Keypad pressed button by scanning technique.

The Driver supports 4x4 and 4x3 keypads, it also has two additional functions for the purpose of simulation on protues simulator:

1- KEYPAD_4x3_adjustKeyNumber()

Description:

- Function responsible for mapping the switch number in the keypad to
- its corresponding functional number in the proteus for 4x3 keypad
 
2- KEYPAD_4x4_adjustKeyNumber()

Description: 

- Function responsible for mapping the switch number in the keypad to
- its corresponding functional number in the proteus for 4x4 keypad