cmake_minimum_required(VERSION 3.0)
project(HelloWorld)

# Spécifie le standard C
set(CMAKE_C_STANDARD 99)

# Ajoute le fichier source
add_executable(hello main.c)
