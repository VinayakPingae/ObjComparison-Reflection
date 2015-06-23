CS542 Design Patterns

Spring 2015

PROJECT ASSIGNMENT NUMBER 05 README FILE



Due Date: Friday, May 4th.

Submission Date: Friday, May 4th.

Grace Period Used This Project: 0 Days

Grace Period Remaining: 0 Days

Author   : Vinayak Subhash Pingale

e-mail   : vpingal1@binghamton.edu



PURPOSE:
Project requirements:
Design a Java class, First, in the following way:
2 private data members
int IntValue;
String StringValue;
empty constructor
define the public method void setIntValue(int iIn) {... }
define the public method void setStringValue(String sIn) {... }
Design a Java class, Second, in the following way:
2 private data members
double DoubleValue;
int IntValue;
empty constructor
define the public method void setIntValue(int iIn) {... }
define the public method void setDoubleValue(double dIn) {... }
Define a class PopulateObjects that has data structures (as data members) to store instances of First and Second. Choose the data structure(s) that are efficient to determine the total number of non-duplicate object instances, and the total number of object instances (includes duplicates).
PopulateObjects should have a method deserObjects(...) to read data member values from an inputFile and accordingly create instances of First and Second. Decide the appropriate return value and parameters for the Populate the data structures with instances of First and Second.
Read the following link about boxed primitives, Integer.TYPE, and Integer.class in the context of Java reflection.
Generalize the above code so it works for both First and Second objects. For example, you need to set signature[0] value by looking up a map that returns "Integer.TYPE" for the key "int".
Populate the data structure in PopulateObjects class withe instances of First and Second that are read from the file.
Design and implement methods in the PopulateObjects class to return the number of non-duplicate instances of First and Second.
Design and implement methods in the PopulateObjects class to return the total number of instances of First and Second.
The Driver code should call the PopulateObjects class to populate the data structures and print output on the number of objects.

PERCENT COMPLETE:

I believe I have completed 100% of this project.



PARTS THAT ARE NOT COMPLETE:



None



BUGS:



None



FILES:


Description - This is the File wordInfo data strucutre which works for performing the file operations and consist of tree data structure to be performed.
Description - This is the Fileword info support interface which is used to perform the operations related to the data structure.
Description - This class has been used for performing operations related to the node data that has been inserted into the tree


 README, the text file you are presently reading


JUSTIFICATION


SAMPLE OUTPUT:
Takes 35 seconds on an average.

TO COMPILE:



Assuming you are in the directory containing this README:



## To clean:

ant -buildfile src/build.xml clean



## To compile: 

ant -buildfile src/build.xml all



TO RUN:



## To run



EXTRA CREDIT:



N/A



BIBLIOGRAPHY:



http://docs.oracle.com/javase/7/docs/api/

http://www.oracle.com/technetwork/articles/java/index-137868.html