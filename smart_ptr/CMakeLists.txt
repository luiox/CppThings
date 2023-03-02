cmake_minimum_required (VERSION 3.8)

project (smart_ptr_test)

add_executable (smart_ptr_test
 "smart_ptr.h" 
 "test.cpp"
 )
 
 if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET smart_ptr_test PROPERTY CXX_STANDARD 20)
endif()
