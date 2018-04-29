

This tutorial was contributed by Kapil Singh Rawat

Python is a great general-purpose programming language created by [Guido van Rossum](https://en.wikipedia.org/wiki/Guido_van_Rossum) and first released in 1991 but later with the help of a few popular libraries (numpy, scipy, matplotlib) it becomes a powerful environment for scientific computing.

- Python
  - Basic data type 
  - Containers
    - Lists
    - Dictionaries
    - Sets
    - Tuples
  - Functions
  - Classes
- Numpy
  - Array
  - Array Indexing 
  - Data types
  - Array math
  - Broadcasting
- SciPy
  - Image operations 
  - MATLAB files
  - Distance between points
- Matpltlib
  - Ploting 
  - Subplots
  - Images

### Python versions

- Implementation started - December, 1989
- Internal releases at [Centrum Wiskunde & Informatica](https://en.wikipedia.org/wiki/Centrum_Wiskunde_%26_Informatica) - 1990
- Python 0.9.0 - February 20, 1991
  - Python 0.9.1 - February, 1991
  - Python 0.9.2 - Autumn, 1991
  - Python 0.9.4 - December 24, 1991
  - Python 0.9.5 - January 2, 1992
  - Python 0.9.6 - April 6, 1992
  - Python 0.9.8 - January 9, 1993
  - Python 0.9.9 - July 29, 1993


- Python 1.0 - January 1994
  - Python 1.2 - April 10, 1995
  - Python 1.3 - October 12, 1995
  - Python 1.4 - October 25, 1996
  - Python 1.5 - December 31, 1997
  - Python 1.6 - September 5, 2000
- Python 2.0 - October 16, 2000
  - Python 2.1 - April 17, 2001
  - Python 2.2 - December 21, 2001
  - Python 2.3 - July 29, 2003
  - Python 2.4 - November 30, 2004
  - Python 2.5 - September 19, 2006
  - Python 2.6 - October 1, 2008
  - Python 2.7 - July 3, 2010
- Python 3.0 - December 3, 2008
  - Python 3.1 - June 27, 2009
  - Python 3.2 - February 20, 2011
  - Python 3.3 - September 29, 2012
  - Python 3.4 - March 16, 2014
  - Python 3.5 - September 13, 2015
  - Python 3.6 - December 23, 2016

### Python Setup and Usage

Look at [general information on the setup of the Python environment](https://docs.python.org/3/using/index.html) on different platforms. 



### Basic data types

Python has numbers of data type that include integers, floats, booleans and strings.

lets have a quick look how to use these data types in below examples.



1. Number : this include integers and floats

   ```
      # Integer data type  
      eip = 3
      print (type (eip)) #print data type
      print (eip)        #print eip value
      print (eip+1)      #Add 1 in eip value
      print (eip-1)      #Subtract 1 in eip value 
      print (eip*2)      #Multiple 2 in eip value
      print (eip**2)     #Exponantiation 2 in eip value 

      eip +=2
      print (eip)
      eip *=2
      print (eip)

      # Float data type
      mlblr = 2.5
      print(type (y))

      print (y, (y+2), (y*2), (y/2), (y**2))


   ```

   Note: Python does not support unary increment and decrement operators (x++, ++x, x-- etc)

2. Boolean: Python uses English words (or, and, not) rather than symbols for Boolean logic (||, &&, !)

   ```
   EIP = True
   MLBLR = False

   print (type(EIP))

   print (EIP or MLBLR)
   print (not MLBLR)
   print (EIP and MLBLR) 
   print (EIP != MLBLR)
   ```

   ​