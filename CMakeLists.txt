#
cmake_minimum_required(VERSION 3.20...3.26)

#
project(
  my-project 
  VERSION 0.1
  DESCRIPTION "My Project"
  LANGUAGES CXX)

#
set(SOURCES
  app/src/main.cpp
)

#
add_executable(my-project ${SOURCES})

