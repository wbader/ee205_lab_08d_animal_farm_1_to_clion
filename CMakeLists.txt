cmake_minimum_required(VERSION 3.16)
project(ee205_lab_08d_animal_farm_1_to_clion)

set(CMAKE_CXX_STANDARD 14)

add_executable(ee205_lab_08d_animal_farm_1_to_clion main.cpp addCats.cpp addCats.h catDatabase.cpp catDatabase.h config.h deleteCats.cpp deleteCats.h main.h validateData.cpp validateData.h updateCats.cpp updateCats.h reportCats.cpp reportCats.h)
