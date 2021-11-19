set(CMAKE_CXX_STANDARD 11)

add_executable(test.cpp ${CMAKE_SOURCE_DIR}/main.h ${CMAKE_SOURCE_DIR}/main.cpp)

enable_testing()
add_test(NAME helloWorld test.cpp)