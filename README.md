# C1_Blinky

The 'firmware' directory contains the firmware that gets flashed to the ATtiny85.  It can be re-built and re-flashed with a 'make clean' and 'make program'.

The 'commandline' directory contains the 'set-led' executable that sends R G B values to the 'C1_Blinky' connected to the USB port.  It can be re-built with a 'make clean' and 'make'.

Once compiled, you can execute 'set-led' using the format:  
  
	sudo ./set-led 255 0 0  
  
Where the 3 values following the 'set-led' command are the R(ed), G(reen), and B(lue) values respectively.  (The command above sets the C1 Blinky to full intensity red.)
