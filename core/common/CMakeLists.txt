add_library(aria_common STATIC
    Frame.h
    Frame.cc
    Timecode.h
    Timecode.cc
    ClipDescriptor.h
    ClipDescriptor.cc
    Error.h
    Error.cc
    Logger.h
    Logger.cc
)

target_include_directories(aria_common PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
