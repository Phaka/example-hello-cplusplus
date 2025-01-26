# Hello World in C++

A simple Hello World implementation in C++.

## Installation

### macOS
```bash
brew install gcc
```

### Linux
For Debian/Ubuntu:
```bash
sudo apt-get update
sudo apt-get install build-essential
```

For Red Hat/Fedora:
```bash
sudo dnf groupinstall "Development Tools"
```

### Windows
Install Visual Studio with C++ support or MinGW.

## Running

Compile and run directly:
```bash
g++ main.cpp -o hello
./hello
```

## Code Explanation

The implementation uses the C++ Standard Library's iostream for console output. The program consists of a main function that prints "Hello, World!" to standard output and returns 0 to indicate successful execution.
