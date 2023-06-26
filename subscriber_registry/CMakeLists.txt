add_library(libsubreg SubscriberRegistry.cpp Timeval.cpp Threads.cpp Utils.cpp sqlite3util.cpp)

target_link_libraries(libsubreg pthread)
target_link_libraries(libsubreg sqlite3)

#target_link_libraries(test_liba5 liba5)