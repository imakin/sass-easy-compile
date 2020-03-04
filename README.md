# sass-easy-compile
sass easy compile using only Makefile. simply generate css in the same folder of the .scss file


many IDE(VSCode, Atom.io, Bracket, etc) plugins require you to write config file, for each project folder!

not to mention you have to specify the sass source directory path and compiled path. 

what if you want to focus on something else? why not just simply compile your sass files in the same path they are in?

Check out this simple Makefile, that simply compile them without any configuration. Though, compile configuration can still be made in the Makefile itself when needed.

Install
- on mac os you might need to install Makefile by `brew install make`
- on windows install mingw https://en.wikipedia.org/wiki/MinGW


Features:
- simply Makefile
- as nature of gnu-make, it watches changes and only compile if any changes are made on your source file
