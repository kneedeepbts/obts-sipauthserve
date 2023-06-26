cmake_minimum_required(VERSION 3.20)
project(obts_sipauthserve)

set(CMAKE_CXX_STANDARD 20)

include_directories(include)

add_subdirectory(apps)
add_executable(obts_sipauthserve apps/sipauthserve.cpp apps/SubscriberRegistry.cpp apps/rijndael.cpp apps/milenage.cpp apps/servershare.cpp apps/sqlite3util.cpp apps/Threads.cpp apps/Timeval.cpp apps/Utils.cpp)


target_link_libraries(obts_sipauthserve osipparser2)
target_link_libraries(obts_sipauthserve osip2)
target_link_libraries(obts_sipauthserve pthread)
target_link_libraries(obts_sipauthserve sqlite3)
