cmake_minimum_required(VERSION 3.15)
project(ECS40_Monopoly)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(ECS40_Monopoly
        Game.cpp
        Game.h
        main.cpp
        OtherClass.cpp
        OtherClass.h
        player.cpp
        player.h
        Property.cpp
        Property.h
        rules.cpp
        rules.h
        setGame.cpp
        setGame.h)
