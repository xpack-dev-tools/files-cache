
## sifive-arty-top.bit

A bitstream file used to reach the Quad SPI flash on the Arty board. Provided by SiFive.

Can be loaded with the `xc3sprog` utility.

## SiFive\_E[35]1\_Coreplex\_FPGA\_*.tar.gz

FPGA images for the E31/E51 Coreplex IP devices running on the Arty FPGA development board. Provided by SiFive.

After programming them in the Arty Quad SPI flash, the board becomes a fully functional RISC-V evaluation board.

Can be programmed with a JTAG probe with OpenOCD, but only after the `sifive-arty-top.bit` was loaded.

For the latest versions, please check:

- https://dev.sifive.com/dashboard/deliverables/sifive_e31_fpga_eval_kit_bitstream/
- https://dev.sifive.com/dashboard/deliverables/sifive_e51_fpga_eval_kit_bitstream/
