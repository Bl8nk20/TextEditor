set(APP_NAME Kilo)
set(APP_SOURCE kilo.cpp)
set(APP_HEADER include/app/kilo.hpp)
set(APP_INCLUDES "./" "${CMAKE_CURRENT_SOURCE_DIR}/include/app")

add_executable(${APP_NAME} ${APP_SOURCE} ${APP_HEADER})