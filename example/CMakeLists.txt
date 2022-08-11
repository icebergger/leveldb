include_directories(${LEVELDB_PUBLIC_INCLUDE_DIR})

add_executable(simple_example simple_example.cpp)
target_link_libraries(simple_example ${PROJECT_BINARY_DIR}/libleveldb.a)