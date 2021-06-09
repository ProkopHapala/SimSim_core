
add_library( DynamicOpt OBJECT DynamicOpt.cpp )

file(GLOB optimization_HEADERS_ *.h )
add_custom_target(optimization_headers SOURCES ${optimization_HEADERS_} )
