cmake_minimum_required(VERSION 3.16)

project(aria LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Core modules
add_subdirectory(core/timeline)
add_subdirectory(core/rendergraph)
add_subdirectory(core/scheduler)
add_subdirectory(core/provider)
add_subdirectory(core/media)
add_subdirectory(core/audio)
add_subdirectory(core/export)
add_subdirectory(core/scripting)
add_subdirectory(core/project)
add_subdirectory(core/action)
add_subdirectory(core/common)

# Application
add_subdirectory(app/cli)
