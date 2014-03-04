cmake_minimum_required(VERSION 2.6.0)

# pull in the pods macros. See cmake/pods.cmake for documentation
set(POD_NAME python-virtualenv-1.11.4)
include(cmake/pods.cmake)

#tell cmake to build these subdirectories
add_subdirectory(src)
add_subdirectory(src/test)
