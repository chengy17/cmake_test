if (NOT PROJ)
    message(FATAL_ERROR "PROJ not set, e.g: -DPROJ=testfun1")
else ()
    message("PROJ = ${PROJ}")
endif ()

cmake_minimum_required (VERSION 3.0)

project (${PROJ})

add_subdirectory (lib)

add_subdirectory (src)
