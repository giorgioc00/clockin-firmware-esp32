idf_component_register(
    SRCS "reader.c"
    INCLUDE_DIRS "include"
    REQUIRES board rc522 esp_event
)
