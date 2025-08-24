idf_component_register(SRCS "SillyFilly-Hardware-Attack-Tool.c"
                    PRIV_REQUIRES console esp_driver_uart fatfs esp_driver_usb_serial_jtag
                                     nvs_flash cmd_system cmd_wifi cmd_nvs
                    INCLUDE_DIRS "." "includes")
