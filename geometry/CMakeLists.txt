
add_library( Convex2d OBJECT Convex2d.cpp )

file(GLOB geometry_HEADERS_ *.h )
add_custom_target(geometry_headers SOURCES ${geometry_HEADERS_} )
