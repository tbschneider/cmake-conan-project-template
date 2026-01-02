# cmake-conan-project-template

A sample project to use cmake and conan for a c++ project.

## Initialize the project

If the file `~/.conan2/profiles/default` doesn't exist, use `conan profile detect` to generate one.

### Windows

`.\init_project.bat`

### Linux/MacOS

`./init_project.sh`

## Build the project

### Windows

`.\build_project.bat`

### Linux/MacOS

`./build_project.sh`

## Example created and tested with

- Windows 11 Pro 25H2
- Visual Studio Community 2026 (18.1.1)
- Conan2 2.24.0
- CMake 4.2.1
