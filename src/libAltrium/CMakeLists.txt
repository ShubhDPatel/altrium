# Creates the library for libAltrium.
add_library(altrium_library 
    Altrium.cpp
    websites/Website.cpp
    websites/Google.cpp
    websites/StackOverflow.cpp
    )

# Includes the header in the library.
target_include_directories(altrium_library PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})

