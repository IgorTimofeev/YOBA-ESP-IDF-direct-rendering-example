set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

idf_component_register(
    SRCS main.cpp
    INCLUDE_DIRS "."
    REQUIRES YOBA
)