project(intensity_histogram)

#set the default path for built executables to the "bin" directory
set(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin)
#set the default path for built libraries to the "lib" directory
set(LIBRARY_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/lib)

include_directories(include)

#add_executable(intensity_histogram src/intensity_histogram.cc)
#target_link_libraries(intensity_histogram ${OpenCV_LIBS})
