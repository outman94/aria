add_library(aria_media STATIC
    MediaDecoder.h
    MediaDecoder.cc
    AsyncDecodeQueue.h
    AsyncDecodeQueue.cc
    DecoderThread.h
    DecoderThread.cc
)

target_include_directories(aria_media PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
