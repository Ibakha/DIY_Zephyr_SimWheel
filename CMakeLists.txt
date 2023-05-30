# SPDX-License-Identifier: Apache-2.0

cmake_minimum_required(VERSION 3.20.0)

# Setting target board
set(BOARD_ROOT ${CMAKE_CURRENT_SOURCE_DIR})
set(BOARD "sim_wheel_nrf52840")

find_package(Zephyr)
project(nrf52840_simwheel)

target_sources(app PRIVATE src/main.c)