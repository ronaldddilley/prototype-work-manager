cmake_minimum_required ( VERSION 3.6 )


include ( InstallExecutable.cmake )


project ( prototype NONE )


set ( ${PROJECT_NAME}_VERSION_MAJOR 0 )
set ( ${PROJECT_NAME}_VERSION_MINOR 0 )
set ( ${PROJECT_NAME}_VERSION_PATCH 1 )
set ( ${PROJECT_NAME}_VERSION_TWEAK 0 )
set ( VERSION ${${PROJECT_NAME}_VERSION_MAJOR}.${${PROJECT_NAME}_VERSION_MINOR}.${${PROJECT_NAME}_VERSION_PATCH}.${${PROJECT_NAME}_VERSION_TWEAK} )


add_subdirectory ( src )
