add_library(aria_rendergraph STATIC
    RenderNode.h
    RenderNode.cc
    RenderGraph.h
    RenderGraph.cc
    CompositeNode.h
    CompositeNode.cc
    TransitionNode.h
    TransitionNode.cc
    RenderPass.h
    RenderPass.cc
    RenderContext.h
    RenderContext.cc
)

target_include_directories(aria_rendergraph PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
