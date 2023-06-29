Flash images for chosen board to the following memory adresses.
Board's bootloaders were specified in brackets.

Tool: Uniflash (https://www.ti.com/tool/UNIFLASH) version min. 8.3.0.4307.

Before flashing, ensure that chip on the board was erased.

CC2652R1 (TI BIM):
	Onchip OAD:
		0x00 	      -> simple_peripheral_oad_onchip_CC26X2R1_LAUNCHXL_tirtos7_ticlang_oad-v1.0.0.bin
		0x38000       -> persistent_app_CC26X2R1_LAUNCHXL_tirtos7_ticlang_oad-v1.0.0.bin
		AUTO(0x56000) -> bim_onchip_CC26X2R1_LAUNCHXL_nortos_ticlang.hex
	Offchip OAD:
		0x00 	      -> simple_peripheral_oad_offchip_CC26X2R1_LAUNCHXL_tirtos7_ticlang_oad-v1.0.0.bin
		AUTO(0x56000) -> bim_offchip_CC26X2R1_LAUNCHXL_nortos_ticlang.hex

After the board has been flashed, reboot it to start running images.