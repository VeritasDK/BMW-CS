cmake_minimum_required (VERSION 2.4)
project (queryProcessor)

include("${${PROJECT_NAME}_SOURCE_DIR}/globalVariables.cmake")

include_directories(${INCLUDES})

link_directories(${LIBS})

add_subdirectory(src)

#add_definitions(-O2)
add_definitions(-O2 )


