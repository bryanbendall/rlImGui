add_library(rlImGui 
            imgui_impl_raylib.h
            rlImGui.cpp
            rlImGui.h
            rlImGuiColors.h
            ) 

target_include_directories(rlImGui PUBLIC
                           .
                           ${CMAKE_SOURCE_DIR}/vendor/raylib/src
                           ${CMAKE_SOURCE_DIR}/vendor/imgui/imgui
                           )
