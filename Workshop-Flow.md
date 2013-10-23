  - Quick description of Python 5 mins
  - Intro to python command line, start hands on - 45 mins
         - Numbers : integer, long, float. Show usage of Python as a calculator
         - Arithmetic operations. Logical operations. Boolean: True/False
         - Print function
         - Command line history, exit
         - Strings : single line, multi line. Single & double quotes. String functions: strip, split. Concept of "immutable"
         - Everything in Python is an object. 
         - Understanding basic exceptions - avoiding basic syntax errors  
         - Interesting python trick : swapping numbers a,b = b,a
         - Python assigns object references by default
         - Variables can change type
         - Built-ins : type, int, hex, bin, 
         - Using "help" & "dir"
         - eval()

 - Collections : Lists - 10 mins
         - Basic list usage : creation, can freely mix data types 
         - List addressing using [] : a[-1], a[x:y], a[x:y:z]
         - Using the swap trick to move around list elements, e.g. a[0:2], a[2:4] = a[2:4], a[0:2]
         - Adding & deleting elements from the list
         - searching, Sorting. l.sort() versus sorted()
           Note: python implements these in an efficient fashion
         - Nested lists for 2D, 3D, etc
         - List membership : "in", "not in"
         - Tuple : same as list, but immutable
         - range()

  - Control constructs : If, While, for | 15 mins
         If
         - Single line if
         - Multi-line if. We introduce python indentation here! "suite"
         - else, elif
         While
         - break
         For : for var in ...:
         - break

[[ Break ]] - 15 mins. Time consumed : 1:15 out of 2:30 available. Now come the interesting things...
 
  - Collections : Dictionary - 5 mins
         - Basic dictionary creation d = { "1" : 10, 10 : 20, 5.0: "hello" } etc
         - Basic dictionary usage: keys
         - Conceptual : keys need to be immutable - e.g. lists won't do

  - Simple file I/O - 5 mins
         - open
         - read
         - readlines

  - Significant example 1: counting word frequency in a file (uses file IO + dictionary) - 10 mins
         - read the whole file
         - split into words
         - maintain a dictionary of counts, one per word

  - lambda functions - 5 mins

  - filter, map, reduce - 10 mins

  - functions - 10 mins
         - basic usage - definition, return
         - docstring
         - default arguments

  - generators - 10 mins
         - yield
         - StopIteration
         - fibonacci example

----- Need to fit till here in 2:15. So we have 30 mins more :D

  - Modules
         - Basic usage. Modules are also objects!
         - Modules provide the power
         - Standard modules bundled into python
         - Third-party modules
         - Examples: PyAudio, Powerpoint, Webserver, Facebook/twitter
         - Extend python with modules
