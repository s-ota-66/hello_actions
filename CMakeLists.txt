cmake_minimum_required(VERSION 3.19.4)

project(HelloWorld)

# C++バージョンを指定
set(CMAKE_OSX_ARCHITECTURES "arm64;x86_64")
set(CMAKE_CXX_STANDARD 17)

# ソースファイルを指定
set(SOURCES main.cpp)

# 実行ファイルをビルド
add_executable(HelloWorld ${SOURCES})
