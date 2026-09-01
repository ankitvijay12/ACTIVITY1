# Activity 1: C/C++ Development Environment Setup

During this activity, I set up a complete C/C++ development environment on macOS by installing Visual Studio Code along with the official Microsoft C/C++ extension for IntelliSense, code navigation, and debugging support.

Because the extension does not include an embedded compiler, I configured the Apple Clang toolchain provided by Xcode Command Line Tools. Initially, the terminal did not recognize compiler commands; I resolved this by running xcode-select --install in the terminal to complete the Command Line Tools installation.

I verified the setup using clang --version, which confirmed the compiler was active and accessible. Finally, I wrote hello.c, compiled it via the integrated terminal using clang hello.c -o hello, and executed the binary to print "Hello, World!", confirming the toolchain is fully operational for upcoming course activities.
