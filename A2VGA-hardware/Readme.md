This project is a hardware implementation of the work done by Mark Aikens and David kuder on the VGA analog card for Apple2.

The card is based on RPI Pico, 4x 74LVC245 chips and a PLD. The improvement is that an ATF22V10 is used which has sufficient I/O pins to allow that 11 bits of the address are decoded for correct switching off of the ExtROM, in case the RPI firmware is using this memory.

### Acknowledgements
This is a fork of David Kuder [∀2 Retro Computing](https://www.v2retrocomputing.com/) project with a new board design intended to fully support his software.
The original design was posted by Mark Aikens 
