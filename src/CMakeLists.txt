aux_source_directory (${PROJECT_NAME} SRC_LIST)

include_directories (../lib)

link_directories (${PROJECT_SOURCE_DIR}/lib)

add_executable (${PROJECT_NAME} ${SRC_LIST})

target_link_libraries (${PROJECT_NAME} fun)

set (EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/build)
