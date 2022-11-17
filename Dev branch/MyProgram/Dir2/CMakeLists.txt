file(GLOB Sources "main.cpp")
add_executable(MyProgram ${Sources})
target_link_libraries(MyProgram Dir1)