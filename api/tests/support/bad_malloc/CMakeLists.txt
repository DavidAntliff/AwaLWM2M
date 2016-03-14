add_library (bad_malloc SHARED bad_malloc.c)
set_property (TARGET bad_malloc PROPERTY POSITION_INDEPENDENT_CODE ON)
target_link_libraries (bad_malloc dl)
