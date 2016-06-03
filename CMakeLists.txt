project( pystl )
cmake_minimum_required( VERSION 2.8 )

if ( WIN32 )
    message( WARNING "WIN32 IS NOT YET FULLY SUPPORTED")
endif()

add_subdirectory( string )
