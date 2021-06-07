# The bear and berries
A bear was hungry and came out to collect berries. There are some number of bushes with berries in a line formation. The bear would like to go from start to finish and collect everything (can only move forward). But there is a problem. When the bear starts collecting berries from one bush, the next bush sees it and hides all its berries. So there is no way to collect the berries of two adjacent bushes. 

Knowing the number of berries on each of the bushes, your task is to help the bear decide which bushes to collect from to maximize the total number, and output the maximum number.

Each test case contains space-separated integers representing the number of berries on the bushes. Calculate the maximum number of berries that can be collected. 

### Sample Test Cases
###### Test case 1
4 2 5 7
The optimal way is to collect from the 1st and 4th bushes, so the solution is 4 + 7 = 11.
 
###### Test case 2
4 9 6
Even though the 2nd bush contains the most berries, it is better to collect from the 1st and 3rd bushes to get the maximum number. The solution is 4 + 6 = 10.
 
###### Test case 3
3 5 -7
The test case is invalid as a bush cannot have a negative number of berries. So the result should be -1.
 
###### Sample Output
11
10
-1

 
## Please Note
You must use the standard I/O library from your chosen language to read/write the file. No third-party libraries are allowed to use. Currently, you should work with a .TXT file for reading and writing. But make sure that later it should be easy to add support for other input files (such as CSV, XLSX, XML etc.) to your code without much code refactoring. 

## Problem Input rules and structure
The test cases are given in the input.txt file. It is assured that the testing input file structure is the same as you see in your input.txt file.
4 2 5 7
4 9 6
3 5 -7
…
 
**NOTE**: Each line corresponds to a single test case. Make sure you are reading in the same order that is given in the .txt file.

For the input file, you should:
1) Read it by Standard Input/Output library of your chosen programming language.
2) Before feeding the inputs from the file to your algorithm, you should validate them. There might be cases when the input file contains non-numeric or negative values. In this case the result should be -1.

## Problem Output rules and structure
As described above, your program should be capable of reading a text file named“input.txt” that contains the test cases. After reading, validating the input and passing it to your algorithm you should save the results as ․txt file in the following format:
11
10
-1
…

NOTE: Each line should correspond to the result of a single test case.
Make sure that each line of output corresponds the right test case.
 
## Submission process
Submit the output txt file using the form.https://toffy.work/hackathon
Submit the project code using the github classroom: 
https://classroom.github.com/assignment-invitations/484f0651da4fade8e56ca6ba4645cc65/status 
OR If you do not have any github account you can send it via email to hadi.awad@EXALT.ps 
