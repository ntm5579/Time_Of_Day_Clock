# Time_Of_Day_Clock

A 12h Clock that displays the time of day on a Basys3 FPGA made using SystemVerilog.

Uses the switches to preset the time with 4 binary decimals. 
*  Switches 0 to 3 (```sw[3:0]```) set the 0's digit of the minutes
*  Switches 4 to 7 (```sw[7:4]```) set the 10's digit of the minutes
*  Switches 8 to 11 (```sw[11:8]```) set the hours
*  pressing button C (```btnC```) loads these values


The Final Working Bitstream file top.bit is all you need to run on a Basys3.
