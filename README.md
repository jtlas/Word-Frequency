Word-Frequency
==============

Java Program 7

For this assignment you are to write a program that handles text files. The assignment requires three classes (plus library classes); we've given you two - FreqStudy, the driver, and another class, WordCount. 

/JavaCS1/src/freqstudy/FreqStudy.java
/JavaCS1/src/freqstudy/WordCount.java

Your job is to write WordFreq, the heart of the application. It MUST extend the Echo class (from Ch 9 of text):

Echo.java

Here is an example of a FreqStudy run, using the file HeartOfDarkness.txt (the text of the Joseph Conrad novel by that name).



As demonstrated in the example run above, an external text file name is entered first. Then any number of individual words are entered, all lower case, and separated by spaces. After doing its analysis, the program then displays a chart that gives the frequencies in the text of the indicated words, to four decimal places. Thus 2.42% of all of the words in the Heart of Darkness text file are "I", 1.33% are "he", and so forth. Pretty clearly Heart of Darkness is narrated in the first person, and is mostly about men. 

Further requirements and tips: 

* you MUST use an array of WordCount objects to keep track of the occurrences of the indicated words. 

* Use printf from Chapter 5 to format your output.

* If s is a String, then this String class method call:
s.split(" "); // this is a single space surrounded by quote marks

returns an array of strings that consists of the tokens (separated by white space) in s. For example, given
String s = "i he his she hers";
String[] words = s.split(" ");


Then words is this five element array of strings: {i, he, his, she, hers}

At the course website we've provided some tips for solving this problem, and in addition we've provided some text files that you might want to experiment with. Thus we urge you to check the ProgramNotes link at the course website for further information about the assignment.

In the box below, enter your WordFreq code. Be sure to comment your code. (As usual, do not add/use additional import statements)


import java.io.IOException;
import java.util.*;