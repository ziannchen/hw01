# message(FATAL_ERROR "请修改 stbiw/CMakeLists.txt！要求生成一个名为 stbiw 的库")

add_library(stbiw STATIC stbi_write_png.cpp)