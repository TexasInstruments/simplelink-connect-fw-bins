Flash images for chosen board to the following memory adresses.
Board's bootloaders were specified in brackets.

Tool: Uniflash (https://www.ti.com/tool/UNIFLASH) version min. 8.8.0.4946.

Before flashing, ensure that chip on the board was erased.

CC1354P10-6 (MCUBoot):
	Onchip OAD:
		AUTO(0x00)    -> mcuboot_onchip_LP_EM_CC1354P10_6_nortos_ticlang.hex
		0x6000        -> ble5_basic_persistent_cc1354p10_6_ticlang_FlashOnly_Release_persistent.bin
		0x30000       -> ble5_basic_ble_oad_onchip_peripheral_cc1354p10_6_ticlang_FlashOnly_Release_v1.bin
	Offchip OAD:
		AUTO(0x00)    -> mcuboot_offchip_LP_EM_CC1354P10_6_nortos_ticlang.hex
		0x6000        -> ble5_basic_ble_oad_offchip_peripheral_public_address_cc1354p10_6_ticlang_FlashOnly_Release_v1.bin

After the board has been flashed, reboot it to start running images.