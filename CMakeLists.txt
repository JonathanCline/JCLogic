cmake_minimum_required(VERSION 3.8)

project(JCLogic VERSION 0.0.1)

add_executable(${PROJECT_NAME} "${PROJECT_NAME}.cpp")

target_include_directories(${PROJECT_NAME}
	PRIVATE "source")

target_link_libraries(${PROJECT_NAME}
	PRIVATE RapidGFX)
