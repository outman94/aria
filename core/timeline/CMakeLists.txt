add_library(aria_timeline STATIC
    Track.h
    Track.cc
    Slot.h
    Slot.cc
    Segment.h
    Segment.cc
    Timeline.h
    Timeline.cc
    TimelineCompiler.h
    TimelineCompiler.cc
    TimeMapping.h
    TimeMapping.cc
)

target_include_directories(aria_timeline PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
