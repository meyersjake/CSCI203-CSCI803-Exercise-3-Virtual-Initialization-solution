# CSCI203-CSCI803-Exercise-3-Virtual-Initialization-solution

Download Here: [CSCI203/CSCI803 Exercise 3 – Virtual Initialization solution](https://jarviscodinghub.com/assignment/exercise-3-virtual-initialization-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

This exercise is to be done during your week 4 laboratory class. When you complete the exercise
show your work to your lab tutor to have your work marked. The marking is based mainly on correct
implementation and code readability. You should implement your code in one file (e.g. ex3.cpp,
ex3.c, ex3.java). Make sure your program has a header comment block containing the name of the
exercise, your name and your student login (e.g. jfk01). You may implement your solution in C, C++,
java or Python.
For this exercise you are to implement a virtually initialized array and test it for correctness.
As usual, your program will prompt for the name of an input file and the read and process the data
contained in this file.
You will use three integer arrays, data[], forward[] and backward[] each containing 100 elements.
Your test data will consist of a file containing two parts:
1. A sequence of pairs: what, where. You are to store the value what in location where of the
data array using virtual initialization. I.e. data[where] = what.
2. This sequence is terminated by the pair ‐1 ‐1
3. This is followed by a sequence of single integer values, probe. For each such value you are to
test whether data[probe] has been initialized and print one of the following two messages:
Position probe has not been initialized.
Position probe has been initialized to value data[probe].
4. This sequence is terminated by the value ‐1
A sample input file might contain:
42 7
93 9
11 4
‐1 ‐1
7
8
9
‐1
For which the output would be:
Position 7 has been initialized to value 42.
Position 8 has not been initialized.
Position 9 has been initialized to value 93.
As usual, do not use classes or STL.
When you are finished, test your program using the provided text file named “Ex3.txt” and show
your code and the output to your lab tutor to receive your mark.

