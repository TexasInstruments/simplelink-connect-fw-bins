Flash images for chosen board to the following memory adresses.
Board's bootloaders were specified in brackets.

Tool: Uniflash (https://www.ti.com/tool/UNIFLASH) version min. 8.8.0.4946.

Before flashing, ensure that chip on the board was erased.

CC2651P3 (TI BIM):
	Offchip OAD:
		0x00          -> ble5_simple_peripheral_oad_offchip_public_address_cc26x1p3_iar_FlashOnly_Release_oad.bin
		AUTO(0x56000) -> ble5_bim_offchip_cc26x1p3_iar_Release_bim.hex

After the board has been flashed, reboot it to start running images.