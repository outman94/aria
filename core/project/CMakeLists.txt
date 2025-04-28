add_library(aria_project STATIC
    Project.h
    Project.cc
    ProjectManager.h
    ProjectManager.cc
    ProjectSerializer.h
    ProjectSerializer.cc
    AutoSaveManager.h
    AutoSaveManager.cc
    OTIOAdapter.h
    OTIOAdapter.cc
    VersionControl.h
    VersionControl.cc
)

target_include_directories(aria_project PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
