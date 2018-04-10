# C++ code snippet template 

* Designed to be used with VS Code under Windows
* The C++ code is compiled with cl (if needed modify the content of tasks.json file in the .vscode directory)

* **HOW TO : start ** : 
  * Open a Microsoft Developper Console
  * Change to the directory where you want to clone this template project : cd %userprofile%/temp
  * Type : git clone https://github.com/40tude/Template-Snippet.git MyApplication
  * cd MyApplication
  * Remove the hidden .git subdirectory : rmdir /S .git
  * From the MyApplication directory, launch VS Code with : code .
  * Start by editing the readme.md file for example

* **HOW TO : push to a new Git repository** :
  * You made some changes in the source code and you made some commits locally on your hard disk. 
  * Now you want to push your changes on a remote repos on GitHub.
  * Go to GitHub and create a new repository (let's say MyCode)
  * Open a console in VSCode and type : git remote add origin https://github.com/40tude/MyCode.git
  * Push your changes to the remote directory using VS Code menus and options

* **HOW TO : Determine the URL that a local Git repository was originally cloned from** :
  * You cloned the snippet template project, you made some modifications. 
  * You don't remember if the local .git is pointing to the snippet template or a new repository 
  * Open a console in VSCode and type : git remote show origin

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
