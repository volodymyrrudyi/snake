cmake_minimum_required (VERSION 2.6) 
project (snake) 

set(CMAKE_C_FLAGS "-Wall -g -pg -Werror")

add_subdirectory (snaked) 
add_subdirectory (snakec)
