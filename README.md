# Four-digit-number-equivalent-of-each-digit
##
## Project Summary:
A simple program which prompts the user to enter a four-digit number and outputs the word equivalent of each digit.
##
## Running the Program:
Download Visual C++ 2017 Community: A free Windows C++ compiler by Microsoft.
Download DEV-C++ 5.11
##
### Installing:
**Say what the step will be**
-Download Dev-C++
##
-Get Dev-C++ 5.0 beta 9.2 (4.9.9.2) (9.0 MB) with Mingw/GCC 3.4.2 Although this is a "beta" version, it works perfectly fine.
##
-Click on SourceForge to go to a list of download sites and pick one. The file will be something like devcpp4.9.9.2_setup.exe. Save this file in a place like C:\Temp.
##
-When the download is complete, click on the "open" button to start the installation process. (Or go to C:\Temp andDouble click on devcpp4.9.9.2_setup.exe). You will see a few screens that ask you to pick a language (English) and to agree to the license terms. Choose a "typical" installation.
##
-Accept the suggested destination for the installation:
##
-Many subdirectories and files are extracted to the destintion:
##
-Answer "yes" when it asks if you wish to install Dev-cpp for all users. Note: if the installation fails, re-install and try "no" for this.
##
-A screen says the installation is complete:
##
-Keep the check mark in the box. Click on "Finish". A first-time configuration screen appears:
##
-Pick "English" and "New Look". In the next several screens, hit "Yes" for its suggestions.
##
-Eventually you are done. Click "OK".
##
finished
##
### How to run the program:
**Step 1**: Configure Dev-C++.
We need to modify one of the default settings to allow you to use the debugger with your programs.
##
**Step 2**: Create a new project. 
A "project" can be considered as a container that is used to store all the elements that are required to compile a program.
##
**Step 3**: Create/add source file(s). 
##
**Step 4**: Compile.
Once you have entered all of your source code, you are ready to compile.
##
**Step 5**: Execute.
You can now run your program.
**Step 6**: Debug.
##
When things aren't happening the way you planned, a source-level debugger can be a great tool in determining what really is going on. Dev-C++'s basic debugger functions are controlled via the "Debug" tab at the bottom of the screen; more advanced functions are available in the "Debug" menu.
##
## Break down into end to end tests:
**Explain what these program**
#include <iostream>
#include <string>
##
using namespace std;
#include is known as a preprocessor directive, which is used to load files
##
<> indicate the start and end of file name to be loaded
##
iostream is the header file which contains all the functions of program like cout, cin etc. and #include tells the preprocessor to include these header file in the program.
##
include using namespace std; to make the short name string visible instead of requiring the cumbersome std::string
##
std is a C++ namespace for many pieces of functionality that are provided in standard C++ libraries
##
int main()
This line initiates the declaration of a function
{
	char digit;
##	
	cout << "Enter a four digit number: " << endl;
the standard console output device
  while ( cin >> digit) {
  	switch (digit)
  	{
  		case '0': cout << " ZERO "; break;
  		case '1': cout << " ONE "; break;
  		case '2': cout << " TWO "; break;
  		case '3': cout << " THREE "; break;
  		case '4': cout << " FOUR "; break;
  		case '5': cout << " FIVE "; break;
  		case '6': cout << " SIX "; break;
  		case '7': cout << " SEVEN "; break;
  		case '8': cout << " EIGHT "; break;
  		case '9': cout << " NINE "; break;
  		default: cout << "UNKNOWN!"; break;
  ##	
  	}
  }
##  
}
a variable to be tested for equality against a list of values. Each value is called a case, and the variable being switched on is checked for each case. When the variable being switched on is equal to a case, the statements following that case will execute until a break statement is reached. When a break statement is reached, the switch terminates, and the flow of control jumps to the next line following the switch statement.
##
## Versioning:
Use Dev-C++ 5.0 beta 9.2 (4.9.9.2) (9.0 MB) with Mingw/GCC 3.4.2 Although this is a "beta" version
