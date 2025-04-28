add_library(aria_export STATIC
    ExportManager.h
    ExportManager.cc
    ExportProfile.h
    ExportProfile.cc
    RenderGraphExporter.h
    RenderGraphExporter.cc
    VideoEncoder.h
    VideoEncoder.cc
    AudioEncoder.h
    AudioEncoder.cc
    Muxer.h
    Muxer.cc
)

target_include_directories(aria_export PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
