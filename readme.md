# Single cpp file project template (for Windows)

This project is meant to be used for c++ skills practice or to quickly test some c++ features.
It was originally created for hackerrank problem solving.
The project can be build with MSBuild and debugged in Visual Studio Code.

## Prerequisities
- Windows OS.
- Visual Studio with MSBuild and MSVC build tools installed. (`msbuild.exe` should be in PATH)
- Visual Studio Code installed.

## How to use it.
1. Run Developer Powershell for Visual Studio.
1. In the command line, navigate to the project folder.
1. Open the project folder in Visual Studio Code with `code cpp-template-linux`.
1. Fill `input.txt` with test case input.
1. Fill `expected.txt` with expected output for the test case.
1. Solve the problem in `main.cpp`.
1. Run `msbuild /t:test` (or select 'Test' from VSCode build tasks `Ctrl+Shift+B`) to compile and test the program.
1. If needed, start debuging in Visual Studio Code by pressing `F5`.