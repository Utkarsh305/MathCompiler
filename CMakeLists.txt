cmake_minimum_required(VERSION 3.0.0)

# Configurations

set(PROJECT_NAME
    URML
)

set(SOURCE_DIR
    src
)

set(SOURCE ${SOURCE_DIR}/main.cpp)

set(LIBRARIES_DIR
    libs
)

project(PROJECT_NAME)

# Executable
add_executable(${PROJECT_NAME} ${SOURCE})

foreach(LIBRARY ${_LIBRARIES})
    add_subdirectory("${FOO_LIBRARIES_DIR}/${LIBRARY}")
endforeach(LIBRARY)

target_link_libraries(${PROJECT_NAME} ${LIBRARIES})
