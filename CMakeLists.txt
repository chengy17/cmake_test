cmake_minimum_required (VERSION 3.0)

project (demo)

include_directories (fun1 fun2)

aux_source_directory (fun1 SRC_LIST1)
aux_source_directory (fun2 SRC_LIST2)

add_executable (main main.c ${SRC_LIST1} ${SRC_LIST2})
