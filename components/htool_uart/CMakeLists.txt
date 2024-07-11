idf_component_register(SRCS "htool_uart.c"
                    INCLUDE_DIRS "include"
                    REQUIRES driver console htool_nvsm htool_api htool_netman)
