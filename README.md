# Unit4_CPP_Code_Book
Files and Streams
The programs demonstrate how to create, open, read, write, and manage files in C++. They also cover file pointers, navigation, different types of files, streams, header files, and basic error handling.

📚 Topics Covered
1. Introduction to File Handling
Concept of File Handling
Need for File Handling
Advantages of storing data in files
File input and output operations
2. Types of Files
Text Files
Binary Files
Difference between Text and Binary Files
3. Streams
Concept of Streams
Input Stream
Output Stream
File Streams
4. Header Files

Important C++ file-handling classes and functions from:

#include <fstream>

Main stream classes:

ifstream – Used for reading from files
ofstream – Used for writing to files
fstream – Used for both reading and writing
📂 File Operations
5. Opening Files
Opening a file using open()
Opening files using constructors
Different file opening modes

Common modes:

ios::in      → Open for reading
ios::out     → Open for writing
ios::app     → Append data to the end
ios::binary  → Open in binary mode
ios::trunc   → Delete existing contents
6. Reading from a File
Reading data using ifstream
Reading character by character
Reading line by line
Reading using stream operators
7. Writing to a File
Writing data using ofstream
Writing strings and values
Appending data to an existing file
8. File Pointers and Navigation
File pointer concept
Input pointer
Output pointer
seekg()
seekp()
tellg()
tellp()

These functions are used to navigate through different positions in a file.

⚠️ Error Handling

This repository also covers basic file error handling, including:

Checking whether a file opened successfully
Handling missing files
Checking end-of-file conditions
Using stream state functions

Common functions:

is_open()
eof()
fail()
good()
bad()
🔄 File Handling Flow
       Start
         |
         ↓
    Open File
         |
         ↓
   Check File Status
         |
    ┌────┴────┐
    ↓         ↓
 Success     Error
    |         |
    ↓         ↓
 Read/Write  Handle Error
    |
    ↓
 Navigate File
    |
    ↓
 Close File
    |
    ↓
    End
🛠️ Programming Language

C++

💻 Tools Used
C++
VS Code / Code::Blocks
Git
GitHub
