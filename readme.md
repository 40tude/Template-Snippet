# C++ code snippet template 

* Designed to be used with VS Code under Windows
* The C++ code is compiled with cl (see the content of tasks.json file in the .vscode directory)

* **HOW TO** : 
  * Open a Microsoft Developper Console
  * Change to the directory where you want to clone this template project : cd %userprofile%/temp
  * Type : git clone https://github.com/40tude/Template-Snippet.git MyApplication
  * cd MyApplication
  * Remove the hidden .git subdirectory : rmdir /S .git
  * From the MyApplication directory, launch VS Code with : code .

* **HOW TO PUSH TO A NEW GIT REPOSITORY ** :
  * I suppose you already had local commit on your hard disk
  * Go to Github and create a new repository (let's say MyCode)
  * Open a console in VSCode and type : git remote add origin https://github.com/40tude/MyCode.git
  * Push your changes
  
* You can read this page if needed : https://www.40tude.fr/blog/how-to-compile-cpp-code-with-vscode-cl/ 

<!-- 
## Sub title
**Bold** rest of the paragraph


### Sample code
```cpp
#include <iostream>

// ----------------------------------------------------------------------------
int main() {
  std::cout << "Grettings Pr Falken\n";  
  getchar();
  return 0;
}
``` 
-->
