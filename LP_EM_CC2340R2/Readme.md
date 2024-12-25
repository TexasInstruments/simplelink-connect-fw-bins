To flash images for LP_EM_CC2340R5 :-

Using uniflash (minimum version v8.2.0.4220), (https://www.ti.com/tool/UNIFLASH)

For off-chip OAD :-

1.  Erase on-chip flash
2.  Program
    - Image 1 - [mcuboot_offchip_LP_EM_CC2340R2_nortos_ticlang.hex](mcuboot_offchip_LP_EM_CC2340R2_nortos_ticlang.hex) at location AUTO
    - Image 2 - the app [basic_ble_oad_offchip_LP_EM_CC2340R2_freertos_ticlang-v1.0.0.bin](basic_ble_oad_offchip_LP_EM_CC2340R2_freertos_ticlang-v1.0.0.bin) as binary at location 0x6000
