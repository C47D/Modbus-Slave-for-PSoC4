Modbus-Slave-for-PSoC4
======================

Full modbus slave code for PSoC 4, working on Pioneer board PSoC 4245-AXI-483

It works very similarly to my PIC slave which has more documentation so maybe read that.

All is working fine except the line driver is toggling a little bit wrong. It is meant to go high just before the slave transmits
and then immediately go low, however it is going low a few mS after it should. Not a major problem but I imagine it might become
one at higher speeds than 9600.

Feel free to add to this code, just send me a pull request.
