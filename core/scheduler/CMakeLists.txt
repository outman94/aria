add_library(aria_scheduler STATIC
    FrameScheduler.h
    FrameScheduler.cc
    FrameContext.h
    FrameContext.cc
    Ticker.h
    Ticker.cc
    PlaybackController.h
    PlaybackController.cc
)

target_include_directories(aria_scheduler PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
