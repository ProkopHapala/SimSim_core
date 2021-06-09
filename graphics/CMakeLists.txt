
add_library( Voronoi OBJECT Voronoi.cpp )

file(GLOB graphics_HEADERS_ *.h )
add_custom_target( graphics_headers SOURCES ${graphics_HEADERS_} )
