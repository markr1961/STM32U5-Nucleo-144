### STM32U5-Nucleo-144
A generic STM32U5 project using Nucleo-144 board.

The initial CPU is an early production STM32U575ZIT6Q which has a problem with start-up of the external 32KHz Osc.
The plan is to replace it with a STM32U599ZIT6Q (2MB) or STM32U599ZJT6Q (4MB).
The replacement device must be 'Z' for 144 pin 'T' for LQFP & 'Q' for internal SMPS step down converter.

### board notes
no HSE.
3 LEDs: red, green blue.
1 user button
Virtual serial port thru debugger.
USB-C (not used)
