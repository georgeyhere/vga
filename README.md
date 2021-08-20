# vga
 Verilog VGA module w/ parameterized VTC

__Description__

This is a basic VGA module with a parameterized video timing controller that allows a user to adjust timings for any resolution.


__Status__

Tested on Artix-7 FPGA (xc7a50t) @640x480 60Hz. I plan to add a bus interface to vga_top such that the module is capable of requesting data from a FIFO.