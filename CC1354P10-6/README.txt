Flash images for chosen board to the following memory adresses.
Board's bootloaders were specified in brackets.

Tool: Uniflash (https://www.ti.com/tool/UNIFLASH) version min. 8.3.0.4307.

Before flashing, ensure that chip on the board was erased.

CC1354P10-6 (MCUBoot):
	Onchip OAD:
		AUTO(0x00)    -> mcuboot_onchip_LP_EM_CC1354P10_6_nortos_ticlang.hex
		0x6000        -> basic_persistent_LP_EM_CC1354P10_6_freertos_ticlang.bin
		0x30000       -> basic_ble_oad_onchip_LP_EM_CC1354P10_6_freertos_ticlang.bin
	Offchip OAD:
		AUTO(0x00)    -> mcuboot_offchip_LP_EM_CC1354P10_6_nortos_ticlang.hex
		0x6000        -> basic_ble_oad_offchip_LP_EM_CC1354P10_6_freertos_ticlang.bin

After the board has been flashed, reboot it to start running images.