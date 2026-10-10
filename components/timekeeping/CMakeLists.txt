idf_component_register(
    SRCS "timekeeping.c"
    INCLUDE_DIRS "include"
    REQUIRES esp_netif ds3231
)
