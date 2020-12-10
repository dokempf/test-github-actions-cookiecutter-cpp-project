cmake_minimum_required(VERSION 3.9)

# Set a name and a version number for your project:
project(test-github-actions-cookiecutter-cpp-project VERSION 0.0.1 LANGUAGES CXX)

# Define the minimum C++ standard that is required
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# this needs to be in the top level CMakeLists.txt:
include(CTest)
set(CMAKE_POSITION_INDEPENDENT_CODE ON)
# compile the library
add_subdirectory(src)

# compile the application
add_subdirectory(app)

# compile the tests
add_subdirectory(ext/Catch2)
add_subdirectory(tests)

# Add the documentation
add_subdirectory(doc)
# Add Python bindings
add_subdirectory(ext/pybind11)
add_subdirectory(python)