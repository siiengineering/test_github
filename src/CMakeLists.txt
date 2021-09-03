add_executable("HelloWorld" "hello_world.cpp")

install(PROGRAMS ${CMAKE_CURRENT_BINARY_DIR}/HelloWorld DESTINATION bin RENAME ${CMAKE_PROJECT_NAME}-HelloWorld)
