﻿add_executable (authkeygen "authkeygen.cpp" "authkeygen.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET authkeygen PROPERTY CXX_STANDARD 20)
endif()

