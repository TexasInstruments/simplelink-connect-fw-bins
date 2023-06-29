Flash images for chosen board to the following memory adresses.
Board's bootloaders were specified in brackets.

Tool: Uniflash (https://www.ti.com/tool/UNIFLASH) version min. 8.3.0.4307.

Before flashing, ensure that chip on the board was erased.

CC2651P3 (TI BIM):
	Offchip OAD:
		0x00          -> simple_peripheral_oad_offchip_LP_CC2651P3_tirtos7_ticlang_oad-v1.0.0.bin
		AUTO(0x56000) -> bim_offchip_LP_CC2651P3_nortos_ticlang.hex

After the board has been flashed, reboot it to start running images.