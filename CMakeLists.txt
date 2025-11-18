cmake_minimum_required(VERSION 3.10)

project(MatrixCalculator)

# C Standard
set(CMAKE_C_STANDARD 11)
set(CMAKE_C_STANDARD_REQUIRED ON)

# Include-Verzeichnis
include_directories(include)

# Executable erstellen
add_executable(mxc
    src/main.c
)
