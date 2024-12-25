Flash images for chosen board to the following memory adresses.
Board's bootloaders were specified in brackets.

Tool: Uniflash (https://www.ti.com/tool/UNIFLASH) version min. 8.8.0.4946.

Before flashing, ensure that chip on the board was erased.

CC2652R1 (TI BIM):
	Onchip OAD:
		0x00 	      -> ble5_simple_peripheral_oad_offchip_public_address_cc26x2r1_iar_FlashROM_Release_oad.bin
		0x38000       -> ble5_persistent_app_cc26x2r1_iar_FlashROM_Release_persistent_oad.bin
		AUTO(0x56000) -> ble5_bim_onchip_cc26x2r1_iar_Release_bim.hex
	Offchip OAD:
		0x00 	      -> ble5_simple_peripheral_oad_onchip_public_address_cc26x2r1_iar_FlashROM_Release_oad.bin
		AUTO(0x56000) -> ble5_bim_offchip_cc26x2r1_iar_Release_bim.hex

After the board has been flashed, reboot it to start running images.