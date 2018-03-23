cmake_minimum_required(VERSION 3.8)

enable_language(CSharp)

add_library(utils Utils.cs)

add_executable(client Client.cs)

target_link_libraries(client utils)

