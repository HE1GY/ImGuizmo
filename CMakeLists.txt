cmake_minimum_required(VERSION 3.23)

project(imguizmo)

add_library(imguizmo STATIC ImCurveEdit.cpp
        ImCurveEdit.h
        ImGradient.cpp
        ImGradient.h
        ImGuizmo.cpp
        ImGuizmo.h
        ImSequencer.cpp
        ImSequencer.h)
target_include_directories(imguizmo PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})