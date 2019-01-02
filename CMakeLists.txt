cmake_minimum_required(VERSION 2.8)
project(csvworker)

add_library(csvworker STATIC csvworker.cpp)
install(TARGETS csvworker DESTINATION lib/git_downloads)
install(FILES csvworker.h DESTINATION include/git_downloads)
