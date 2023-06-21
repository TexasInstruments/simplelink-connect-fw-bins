Flash images for chosen board to the following memory adresses.
Board's bootloaders were specified in brackets.

Tool: Uniflash (https://www.ti.com/tool/UNIFLASH) version min. 8.3.0.4307.

Before flashing, ensure that chip on the board was erased.

CC2652R7 (TI BIM):
	Onchip OAD:
		0x00 	      -> simple_peripheral_oad_onchip_LP_CC2652R7_tirtos7_ticlang_oad.bin
		0x86000       -> persistent_app_LP_CC2652R7_tirtos7_ticlang_oad.bin
		AUTO(0xae000) -> bim_onchip_LP_CC2652R7_nortos_ticlang.hex
	Offchip OAD:
		0x00 	      -> simple_peripheral_oad_offchip_LP_CC2652R7_tirtos7_ticlang_oad.bin
		AUTO(0xae000) -> bim_offchip_LP_CC2652R7_nortos_ticlang.hex

After the board has been flashed, reboot it to start running images.