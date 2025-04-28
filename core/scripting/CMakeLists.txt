add_library(aria_scripting STATIC
    ScriptEngine.h
    ScriptEngine.cc
    ScriptRenderNode.h
    ScriptRenderNode.cc
    ScriptBinding.h
    ScriptBinding.cc
)

target_include_directories(aria_scripting PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
