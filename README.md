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

## To compile it in Visual Studio 16 2019
install visual studio 2019 community
install git
install cmake

Install boost 1.59 binaries  (MSVC 14.0)
https://sourceforge.net/projects/boost/files/boost-binaries/1.59.0/


Install OpenSSL binaries
https://slproweb.com/products/Win32OpenSSL.html (no longer up, try https://web.archive.org/web/20180904051951/http://slproweb.com/download/Win32OpenSSL-1_0_2p.exe)

Win64 OpenSSL v1.0.2p
Make sure it installs to C:\OpenSSL-Win32
