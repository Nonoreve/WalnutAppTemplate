cmake_minimum_required(VERSION 3.16)

project(walnut_app)
set(CMAKE_CXX_STANDARD 17)

add_executable(${CMAKE_PROJECT_NAME}
	src/WalnutApp.cpp
)

target_link_libraries(${CMAKE_PROJECT_NAME} walnut)
