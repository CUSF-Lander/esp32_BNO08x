idf_component_register(SRC_DIRS "source"  "source/report" "SH2"
                    INCLUDE_DIRS "." "include" "include/report" "include/callback" "SH2"
                    REQUIRES esp_driver_gpio esp_driver_spi esp_driver_i2c esp_timer cmock)
