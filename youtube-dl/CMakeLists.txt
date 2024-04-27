# CMakeList.txt : CMake project for youtube-dl, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (youtube-dl "youtube-dl.cpp" "youtube-dl.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET youtube-dl PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
