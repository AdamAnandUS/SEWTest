Hello, I was able to find answers for the following questions.
1.	The longest word in the file that can be constructed by concatenating copies of shorter words also found in the file.  

ethylenediaminetetraacetate – 27 characters

electroencephalographically – 27 characters

2.	The program should then go on to report the 2nd longest word found  

immunoelectrophoretically – 25 characters

3.	Total count of how many of the words in the list can be constructed of other words in the list.

Totally 50429 words in the list are constructed using other words in the list.

This is the approach I used.

Step 1: 
First identify all the possible substrings in the given string.

Step 2:
Analyze each string by replacing the substrings found in that string starting from the maximum length substring. In this step only those strings which are genuinely constructed by the other substrings will be identified.

Step 3:
Simply sort the identified string based on their length in descending order.
 

Thanks
Adam
