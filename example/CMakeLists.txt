find_package (Seastar REQUIRED)
add_executable(example main.cc)
target_link_libraries(example PRIVATE Seastar::seastar)