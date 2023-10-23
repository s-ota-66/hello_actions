cmake_minimum_required(VERSION 3.5)

project(HelloWorld)

# C++バージョンを指定
set(CMAKE_CXX_STANDARD 11)

# ソースファイルを指定
set(SOURCES main.cpp)

# 実行ファイルをビルド
add_executable(HelloWorld ${SOURCES})
