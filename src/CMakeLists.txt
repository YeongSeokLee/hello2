include_directories("${CMAKE_CURRENT_BINARY_DIR}")

add_executable(hello main.cc)
install(TARGETS hello
  RUNTIME DESTINATION bin
)
