cmake_minimum_required(VERSION 3.0)
project(libconsul-cpp VERSION 0.0.1)

set(CMAKE_C_STANDARD 11)

configure_file(lib/version.h.in version.h @ONLY)
