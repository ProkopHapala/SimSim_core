
add_library( Noise    OBJECT Noise.cpp )
add_library( Lingebra OBJECT Lingebra.cpp )

file(GLOB numerics_HEADERS_ *.h )
add_custom_target( numerics_headers SOURCES ${numerics_HEADERS_} )
