# The Flutter tooling requires that developers have CMake 3.10 or later
# installed. You should not increase this version, as doing so will cause
# the plugin to fail to compile for some customers of the plugin.
cmake_minimum_required(VERSION 3.10)

project(google_messaging_toolkit_library VERSION 0.0.1 LANGUAGES C)

add_library(google_messaging_toolkit SHARED
  "google_messaging_toolkit.c"
)

set_target_properties(google_messaging_toolkit PROPERTIES
  PUBLIC_HEADER google_messaging_toolkit.h
  OUTPUT_NAME "google_messaging_toolkit"
)

target_compile_definitions(google_messaging_toolkit PUBLIC DART_SHARED_LIB)
