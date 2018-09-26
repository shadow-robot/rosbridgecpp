## Usage
See examples in rosbridge_ws_client.cpp

## To include in your project
Add these lines to your CMakeLists.txt
```cmake
include_directories(<rosbridgecpp source_dir>)
add_subdirectory(<rosbridgecpp source_dir> rosbridgecpp)
target_link_libraries(<target> rosbridgecpp)
```
Example:
```cmake
include_directories(${CMAKE_CURRENT_SOURCE_DIR}/../../rosbridgecpp)
add_subdirectory(${CMAKE_CURRENT_SOURCE_DIR}/../../rosbridgecpp rosbridgecpp)
target_link_libraries(${PROJECT_NAME} rosbridgecpp)
```

## To compile it in Visual Studio 15 2017
install visual studio 2017 community
install git
install cmake

Install boost 1.59 binaries  (MSVC 14.0)
https://sourceforge.net/projects/boost/files/boost-binaries/1.59.0/


Install OpenSSL binaries
https://slproweb.com/products/Win32OpenSSL.html
Win64 OpenSSL v1.0.2p
