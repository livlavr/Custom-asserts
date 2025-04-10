add_executable(CustomAsserts
    ${CMAKE_CURRENT_SOURCE_DIR}/Color-printf/color_printf.cpp
)

target_include_directories(CustomAsserts
    ${CMAKE_CURRENT_SOURCE_DIR}/Color-printf
)


