CMAKE_MINIMUM_REQUIRED(VERSION 3.10)
PROJECT(StreamStringLibraryTest)

SET(CMAKE_CXX_STANDARD 17)

ADD_SUBDIRECTORY(googletest/googletest)

ADD_SUBDIRECTORY(StreamStringLibrary)

ADD_SUBDIRECTORY(StreamPositionTest)
ADD_SUBDIRECTORY(StreamStringTest)
