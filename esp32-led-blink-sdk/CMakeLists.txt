cmake_minimum_required(VERSION 3.29)
set(EXTRA_COMPONENT_DIRS ${CMAKE_CURRENT_LIST_DIR}/../components) # TODO: move to managed components
include($ENV{IDF_PATH}/tools/cmake/project.cmake)
project(main)
