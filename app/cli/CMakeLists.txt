add_executable(aria_cli
    main.cc
)

target_link_libraries(aria_cli
    aria_timeline
    aria_rendergraph
    aria_scheduler
    aria_provider
    aria_media
    aria_audio
    aria_export
    aria_scripting
    aria_project
    aria_action
    aria_common
)

target_include_directories(aria_cli PUBLIC ${CMAKE_SOURCE_DIR})
