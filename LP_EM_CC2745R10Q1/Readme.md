To flash images for CC2745R10Q1 :-

Tool: Uniflash (https://www.ti.com/tool/UNIFLASH) version min. 8.3.0.4307.

Program
    - Image 1 - [basic_persistent_LP_EM_CC2745R10_Q1_freertos_ticlang.hex]
    - Image 2 - [basic_persistent_LP_EM_CC2745R10_Q1_freertos_ticlang_sb.bin]
    - Image 3 - the app [basic_ble_oad_onchip_LP_EM_CC2745R10_Q1_freertos_ticlang_sb_v1.bin] as binary at location 0x30000

For dual-image OAD :-

Program
    - Image 1 - [basic_ble_oad_dual_image_LP_EM_CC2745R10_Q1_freertos_ticlang.hex]
    - Image 2 - the app [basic_ble_oad_dual_image_LP_EM_CC2745R10_Q1_freertos_ticlang_sb_v1.bin]