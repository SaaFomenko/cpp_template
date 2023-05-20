cmake_minimum_required(VERSION 3.18)

project(project_name
	VERSION 1.0.0
	DESCRIPTION "."
	LANGUAGES CXX)

file(GLOB
	source "*.cpp")

add_library(${PROJECT_NAME}_lib ${source})
