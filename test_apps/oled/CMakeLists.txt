cmake_minimum_required(VERSION 3.16)

# Reuse the firmware's board component (pins + shared I2C bus).
set(EXTRA_COMPONENT_DIRS "../../components/board")

include($ENV{IDF_PATH}/tools/cmake/project.cmake)
project(oled-test)
