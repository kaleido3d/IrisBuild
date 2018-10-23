include_directories(. common)
add_subdirectory(common)
add_subdirectory(vm)
add_subdirectory(generator)
add_subdirectory(tool)
add_subdirectory(standalone)
add_subdirectory(rpc)
add_subdirectory(reflector)
add_subdirectory(unittest)
add_subdirectory(igen)
if(WIN32)
	add_subdirectory(sandbox)
endif()