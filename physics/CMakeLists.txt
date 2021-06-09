
add_library( Body   OBJECT Body.cpp   )
add_library( Body2D OBJECT Body2D.cpp )
add_library( Truss  OBJECT Truss.cpp  )

file(GLOB physics_HEADERS_ *.h )
add_custom_target( phytsics_headers SOURCES ${physics_HEADERS_} )
