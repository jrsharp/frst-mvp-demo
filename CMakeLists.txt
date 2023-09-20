#-------------------------------------------------------------------------------
# FRST Minimum Viable Product Demo for FRST Models 1 and 2

cmake_minimum_required(VERSION 3.13.1)
find_package(Zephyr REQUIRED HINTS $ENV{ZEPHYR_BASE})

set(EXTRA_ZEPHYR_MODULES hal espressif)

project(app LANGUAGES C)

target_sources(app PRIVATE src/main.c)
