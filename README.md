# C++ Course

Check regularly [C++ Compiler support](https://en.cppreference.com/w/cpp/compiler_support)

We follow [The-C-20-Masterclass-Source](https://www.youtube.com/watch?v=8jLOx1hD3_o) on YouTube.

## VSC and C++ Extension

Install and use vscode from [code.visualstudio.com](http://code.visualstudio.com/)

Also install C++ extension and other usefull extensions from the Extensions-tab on vscode:

- C/C++ (Microsoft) - C++ IntelliSense, debugging, and code browsing.
- Extension: Code Runner (Jun Han)




- C/C++ Clang Command Adapter (Microsoft) - Clang Command Adapter for C/C++.
- Extension: C/C++ GDB Debug (Microsoft)
- Extension: C/C++ Snippets (Tomasz Pęczek)
- Extension: C/C++ Themes (Microsoft)

## GCC & CLANG Compiler

### On Windows

#### GCC and CLANG Compiler Installation on Windows

Download from WinLibs.com the standalone build of GCC/CLANG for Windows

Unzip the downloaded file and move the whole folder mingw64 to root C:\

Be sure to [Add the compiler to your user or system PATH](https://code.visualstudio.com/docs/languages/cpp#_add-the-mingw-compiler-to-your-path) path environment variable C:\mingw64\bin

#### GCC and CLANG Compiler version check

Last but not least, check the version of both compilers with the following command:

```bash
    gcc --version
```

```bash
    clang --version
```

#### GCC Compiler Installation on Linux Mint (Ubuntu)

Good practice before installing any package on Linux is to update the package list with the following command:

```bash
    sudo apt update
```

Normally the GCC compiler is already installed on Linux Mint (Ubuntu) by default. If not, install it with the following command:

```bash
    sudo apt install gcc
```

#### GCC Compiler version check

Last but not least, check the version of GCC compiler with the following command:

```bash
    gcc --version
```

#### Clang Compiler Installation and version check

to install Clang compiler:

```bash
    sudo apt install clang
```

version check for Clang compiler:

```bash
    clang --version
```

Before starting to code, be sure you can check the version of GCC and/or CLANG in a terminal window.

### MinGW-w64

mingw-w64 is a collection of compilers, libraries, and other tools that support the execution of native Windows applications. It is a fork of the mingw.org project, created to support the GCC compiler on Windows systems. The mingw-w64 project is a continuation of the original mingw.org project, created in 2007 by Colin Peters to support the GCC compiler on Windows systems. The original mingw.org project was created in 2001 by H. J. Lu to support the GCC compiler on Windows systems. The original mingw.org project was created in 2001 by H. J. Lu to support the GCC compiler on Windows systems.

Check the page on [MinGW-w64](https://mingw-w64.org/) to get some overview of the compiler.
pacman -S mingw-w64-x86_64-gcc
