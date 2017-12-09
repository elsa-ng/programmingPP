# Programming Principles and Practice Using C++

## Purpose
The purpose of this repository is to host C++ code used to practice the concepts and techniques learned from OOP345 and Stroustrup's [Programming Principles and Practice Using C++](http://www.stroustrup.com/Programming/).

## Getting Started
[Microsoft Visual Studio 2017 Community](https://www.visualstudio.com/) is the IDE used to produce all the C++ codes in this repository. 

### Tweaking Microsoft Visual Studio
If [Microsoft Visual Studio 2017 Community](https://www.visualstudio.com/) is your choice of IDE, you may have encountered an issue where the console window doesn't stay opened after running the code with `CTRL + F5`. Follow the steps below to offset this: 
* Right click on your project and select `Properties`
* At the left panel, expand the `Linker` section and select `System`
* At the right panel, find the `SubSystem` property
* To the right of the `SubSystem` property, enter `Console`
* Click ok at the bottom and re-run your code using `CTRL+F5`

### std_lib_facilities.h
This header file is created by [Stroustrup] to simplify the use of C++ standard library and to complement the drills and exercises used in his book, Programming Principles and Practice Using C++. If you choose not to use this custom library, you will have to `#include` the following libraries as necessary:
* `#include <iostream>`
* `#include <string>`
* `#include <vector>`
* `#include <algorithm>`
* `#include cmath>`
* `using namespace std;`

## Author
* [**Elsa (Wai Chi) Ng**](https://github.com/elsa-ng)

## Reference
Stroustrup, B. (2014). *Programming Principles and Practice Using C++* (2nd ed). Crawfordsville, IN: Addison-Wesley.

## License
This project is licensed under the [ISC License](https://www.isc.org/downloads/software-support-policy/isc-license/)

### A special note to current students:  
**Keep Calm, Code On and Don't Plagiarize!**  
It is okay to read someone's code and learn from it. If you find my code useful and would like to include it in your solution then please reference it.