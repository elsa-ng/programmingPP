# Programming Principles and Practice Using C++

## Purpose
The purpose of this repository is to host C++ code used to practice the concepts and techniques learned from OOP345 and Stroustrup's [Programming Principles and Practice Using C++](http://www.stroustrup.com/Programming/).

## Getting Started
[Microsoft Visual Studio 2017 Community](https://www.visualstudio.com/) is the IDE used to produce all the C++ codes in this repository. 

### Using the Code
Assuming you are using Microsoft Visual Studio 2017 Community Version 15.5.1:
1. Run [Microsoft Visual Studio](https://www.visualstudio.com/)
2. Open the `File` menu
3. Point to `New` and click `Project`
4. At the left pane select `Visual C++`
5. Choose `Empty Project` from the middle pane
6. Give your project a name at the bottom of the window
7. Choose a directory for your project or use the default location
8. Click `OK`
9. Under `Solution Explorer`, right click on your project's name
10. Point to `Add` and select `Existing Item`
11. Navigate to where you stored the .cpp file and select that .cpp file
12. Click `OK` and you should see the .cpp file listed in the `Solution Explorer` section

### Tweaking Microsoft Visual Studio
If [Microsoft Visual Studio 2017 Community](https://www.visualstudio.com/) is your choice of IDE, you may have encountered an issue where the console window doesn't stay opened after running the code with `CTRL + F5`. Follow the steps below to offset this: 
* Right click on your project and select `Properties`
* At the left panel, expand the `Linker` section and select `System`
* At the right panel, find the `SubSystem` property
* To the right of the `SubSystem` property, enter `Console`
* Click ok at the bottom and re-run your code using `CTRL+F5`

### std_lib_facilities.h
This header file is created by Stroustrup to simplify the use of C++ standard library and to complement the drills and exercises used in his book, [Programming Principles and Practice Using C++](http://www.stroustrup.com/Programming/). If you choose not to use this custom library, you will have to `#include` the following libraries as necessary:
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