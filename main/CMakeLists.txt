cmake_minimum_required(VERSION 3.16)
idf_component_register(
    SRCS "main.c"
    INCLUDE_DIRS "."
    REQUIRES
        nvs_flash
        esp_event
        board
        device_config
        rc522
        ds3231
        timekeeping
        event_queue
        dedup
        net
        api_client
        feedback
)
