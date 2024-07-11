idf_component_register(SRCS "htool_api.c"
                    INCLUDE_DIRS "include"
                    REQUIRES htool_wifi esp_http_server console htool_uart htool_ble
        )
