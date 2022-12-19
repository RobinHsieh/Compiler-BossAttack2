cmake_minimum_required(VERSION 3.23)
project(Boss_Attack_2 C)

set(CMAKE_C_STANDARD 99)

add_executable(Boss_Attack_2 "Code_Transformation/lex.yy.c" Code_Transformation/test.c)
