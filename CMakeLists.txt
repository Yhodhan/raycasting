 cmake_minimum_required(VERSION 3.10)

 project(raycasting)

 file(GLOB SOURCE_FILES src/*.c src/*.cpp)

 add_executable(${PROJECT_NAME} ${SOURCE_FILES})

 target_link_libraries(${PROJECT_NAME} glfw)
