add_library(aria_action STATIC
    Action.h
    Action.cc
    InsertSlotAction.h
    InsertSlotAction.cc
    MoveSlotAction.h
    MoveSlotAction.cc
    DeleteSlotAction.h
    DeleteSlotAction.cc
    ModifyEffectAction.h
    ModifyEffectAction.cc
    TimelineController.h
    TimelineController.cc
)

target_include_directories(aria_action PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
