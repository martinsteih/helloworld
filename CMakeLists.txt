cmake_minimum_required(VERSION 3.18.4)

project(helloworld CXX)

add_executable(${PROJECT_NAME} main.cpp)

install(TARGETS ${PROJECT_NAME}
    RUNTIME DESTINATION bin
        COMPONENT Runtime)