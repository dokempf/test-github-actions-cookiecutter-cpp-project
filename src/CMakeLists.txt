add_library(test-github-actions-cookiecutter-cpp-project test-github-actions-cookiecutter-cpp-project.cpp)
target_include_directories(test-github-actions-cookiecutter-cpp-project PUBLIC
  $<BUILD_INTERFACE:${CMAKE_SOURCE_DIR}/include/>
  $<INSTALL_INTERFACE:${CMAKE_INSTALL_INCLUDEDIR}>
)

# Add an alias for use if this project is included as a subproject in another project
add_library(test-github-actions-cookiecutter-cpp-project::test-github-actions-cookiecutter-cpp-project ALIAS test-github-actions-cookiecutter-cpp-project)
