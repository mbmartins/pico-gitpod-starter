cmake_minimum_required(VERSION 3.13)
include(/home/gitpod/pico/pico-sdk/pico_sdk_init.cmake)

project(pico_project)

pico_sdk_init()

add_executable(main
    main.c
)

pico_enable_stdio_usb(main 1)
pico_enable_stdio_uart(main 0)

pico_add_extra_outputs(main)
