# Chapter 2 - Drill #1

## Purpose
The purpose of a drill is to establish or reinfore practical programming skills learned from the chapter and to provide experience with programming environment tools. A drill is a sequence of modifications to a single program, growing it from something completely trivia to something that might be a useful part of a real program.

## Objective
* Familiarize with [Microsofot Visual Studio](https://www.visualstudio.com/)
  * Create an Empty Project
  * Create a .h file
  * Create a .cpp file
* Use C++ standard and custom libraries
* Output a string to console
* Debug the code

## Instructions
1. Set up an Empty Project in [Microsofot Visual Studio](https://www.visualstudio.com/)
2. Create a .cpp file and name it `hello_world.cpp`
3. In the .cpp file, input one of the following code:
    ```C++
    #include "std_lib_facilities.h"
    
    int main() {
      cout << "Hello, World!\n";
      keep_window_open();
      return 0;
    }
    ```
4. Try using a standard C++ library instead of the custom library and modify the code to use the standard library
5. Fix errors, if any
6. Create errors and see how the compiler reacts

## Review
1. What is the purpose of the "Hello, World!" program?  
   The purpose of the "Hello, World!" program is to get programmers acquainted with the  basic tools of programming through building a trivial program. The basic tools can then be used to tackle complicated programs. 
   
2. Name the four parts of a function.  
   Every function has 4 parts:
    * a return type
    * a name
    * a parameter list
    * a function body
   
   Example:
   ```C++
    int main() {
        return 0;
    }
    ```
   The return type for the above function is `int` meaning integer with a name `main`. This `main()` function has an empty parameter list and a function body containing the code `return 0;`.
   
3. Name a function that must appear in every C++ program.  
   The function that must appear in every C++ program is the `main()` function.
   
4. In the "Hello, World!" program, what is the purpose of the line `return 0;`?  
   The purpose of the line `return 0;` is to inform the system that the program has executed and terminated successfully.
   
5. What is the purpose of the compiler?  
   The purpose of the compiler is to turn/translate the human-readable code that programmers wrote to a machine-readable version. 
   
6. What is the purpose of the `#include` directive?  
   The `#include` directive is used to tell the compiler that the program calls for the standard/custom libraries. 
   
7. What does a `.h` suffix at the end of a file name signify in C++?  
   The `.h` suffix at the end of a file name signifies that the file is a header file hosting C++ standard/custom libraries.
   
8. What does the linker do for your program?  
   The  linker links various parts (object code files) of the program together to produce an executable file.
   
9. What is the difference between a source file and an object file?  
   Source file containts source code which is written by programmers and is human-readable. The object file contains machine code which is translated from source code by the compiler into machine-readable code.
   
10. What is an IDE and what does it do for you?  
    IDE stands for Intergrated Development Environment. IDE usually provides a complete suite of tools such as a feature-rich text editor, compiler, linker, and debugger.
    
11. If you understand everything in the textbook, why is it necessary to practice?  
    Programming is a practical skill that requires repetitive practicing. 