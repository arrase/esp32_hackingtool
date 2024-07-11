idf_component_register(SRCS "htool_ble.c"
                    INCLUDE_DIRS "include"
                    REQUIRES bt
                    PRIV_REQUIRES nvs_flash)
