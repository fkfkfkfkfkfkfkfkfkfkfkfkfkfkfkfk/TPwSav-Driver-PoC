CMAKE_MINIMUM_REQUIRED(VERSION 3.19)

PROJECT(TPwSav
    LANGUAGES C
    )

SET( CMAKE_C_STANDARD            11 )
SET( CMAKE_C_STANDARD_REQUIRED   ON )
SET( CMAKE_C_EXTENSIONS          OFF )

SET_PROPERTY(GLOBAL
    PROPERTY USE_FOLDERS         ON
)

SET( CMAKE_RUNTIME_OUTPUT_DIRECTORY "${CMAKE_SOURCE_DIR}/bin" )

ADD_SUBDIRECTORY( src )