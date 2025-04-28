add_library(aria_audio STATIC
    AudioMixer.h
    AudioMixer.cc
    AudioSynchronizer.h
    AudioSynchronizer.cc
    AudioDecoder.h
    AudioDecoder.cc
    AudioRenderNode.h
    AudioRenderNode.cc
)

target_include_directories(aria_audio PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
