cmake_minimum_required(VERSION 3.26.4)
project(Projeto2)

set(CMAKE_CXX_STANDARD 14)

include_directories(Classes)

add_executable(Projeto2
        Classes/Airport.cpp
        Classes/Airport.h
        Classes/Airline.cpp
        Classes/Airline.h
        Classes/Data.cpp
        Classes/Data.h
        Classes/FlightManagementSystem.cpp
        Classes/FlightManagementSystem.h
        Classes/Menu.cpp
        Classes/Menu.h
        Classes/Position.h
        Classes/Position.cpp
        Classes/Graph.cpp
        main.cpp
)
