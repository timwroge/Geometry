find_package(manif PATHS ${CMAKE_SOURCE_DIR}/external/manif/install REQUIRED)

if(${manif_IS_FOUND})
    MESSAGE(Manif library found!)
endif()
