# SPDX-License-Identifier: Apache-2.0

cmake_minimum_required(VERSION 3.20.0)

set(BOARD stm32f4_disco)

find_package(Zephyr HINTS $ENV{ZEPHYR_BASE})
project(ADC)

target_sources(app PRIVATE src/main.c)
