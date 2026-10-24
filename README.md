# AutomatedOverlayTKA

A minimal C++ console program that prints `Hello, World!`.

## Build and run in Visual Studio Community 2026

1. In Visual Studio Installer, install the **Desktop development with C++** workload, including **C++ CMake tools for Windows** and a Windows SDK.
2. Clone this repository to your computer using Visual Studio or Git.
3. In Visual Studio, choose **File > Open > Folder** and select the repository folder containing `CMakeLists.txt`.
4. Wait for CMake configuration to finish.
5. Select **AutomatedOverlayTKA.exe** as the startup item in the toolbar if it is not already selected.
6. Choose **Build > Build All**.
7. Press **Ctrl+F5** to run without debugging and see the console output.

Expected output:

```text
Hello, World!
```

Edit `main.cpp` to start writing your own C++ code. No Qt, OpenCV, or other external libraries are required.

## Build from a terminal with CMake

```sh
cmake -S . -B build
cmake --build build --config Debug
```

With a Visual Studio generator, run `build\Debug\AutomatedOverlayTKA.exe` on Windows. With a single-configuration generator on Linux or macOS, run `./build/AutomatedOverlayTKA`.
