idf_component_register(SRCS "sniffer.c" "ap_scanner.c" "wifi_controller.c"
                    INCLUDE_DIRS "interface"
                    PRIV_REQUIRES esp_wifi)
