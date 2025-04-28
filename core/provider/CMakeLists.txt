add_library(aria_provider STATIC
    FrameProvider.h
    FrameProvider.cc
    VideoFileProvider.h
    VideoFileProvider.cc
    CameraStreamProvider.h
    CameraStreamProvider.cc
    ProtocolDrivenProvider.h
    ProtocolDrivenProvider.cc
    AudioProvider.h
    AudioProvider.cc
)

target_include_directories(aria_provider PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
