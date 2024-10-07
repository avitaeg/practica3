cmake_minimum_required(VERSION 3.16)

project(Practica3F LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(Practica3F main.cpp)

include(GNUInstallDirs)
install(TARGETS Practica3F
    LIBRARY DESTINATION ${CMAKE_INSTALL_LIBDIR}
    RUNTIME DESTINATION ${CMAKE_INSTALL_BINDIR}
)
