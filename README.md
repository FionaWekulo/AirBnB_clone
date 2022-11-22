
0x00. AirBnB clone - The console

0x01 Introduction

Team project to build a clone of AirBnB.
The console is a command interpreter to manage objects abstraction between objects and how they are stored.

The console will perform the following tasks:

1. create a new object
2. retrive an object from a file
3. do operations on objects
4. destroy an object


Storage
All the classes are handled by the Storage engine in the FileStorage Class.


0x02 Environment
All the development and testing was runned over an operating system Ubuntu 20.04 LTS using programming language Python 3.8.3.


0x03 Installation
git clone https://github.com/FionaWekulo/AirBnB_clone.git

then change to the AirBnb directory and run the command:

 ./console.py


Execution
In interactive mode:

$ ./console.py

(hbnb) help

Documented commands (type help <topic>):
========================================

EOF  help  quit
(hbnb)
(hbnb) quit
$

In Non-interactive mode:

$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================

EOF  help  quit
(hbnb)
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)


Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
$


0x04 Testing
All the test are defined in the tests folder.

Documentation
Modules:
python3 -c 'print(__import__("my_module").__doc__)'

Classes:
python3 -c 'print(__import__("my_module").MyClass.__doc__)'

Functions (inside and outside a class):
python3 -c 'print(__import__("my_module").my_function.__doc__)'
and
python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'


Python Unit Tests
run test in interactive mode:
echo "python3 -m unittest discover tests" | bash

run test in non-interactive mode:
python3 -m unittest discover tests


0x05 Usage
Start the console in interactive mode:
$ ./console.py


Authors:
Fiona Wekulo

Joseph Lweya