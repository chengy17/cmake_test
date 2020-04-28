aux_source_directory (. LIB_SRC)

add_library (libFun_static STATIC ${LIB_SRC})

set_target_properties (libFun_static PROPERTIES OUTPUT_NAME "fun")

set (LIBRARY_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/build)
