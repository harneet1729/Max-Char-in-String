# Max-Char-in-String
A basic DSA Question to find Maximum Occurring Character in a string

Here we need to find the Character with maximum frequency. If more than 1 character has maximum frequency then we will return the character that occurs first in lexicographical ordering. Upper and Lower Case are considered the same character.

eg input - "abhdkhkbdk"
output - k

eg input - "ahbdhbdk"
output - b
explaination - all b,d,h occurtwice but b occurs the first in lexicographical (alphabetical) order.


This was a question for Practice in Geeksforgeeks website and I made the code for the function "getMaxOccuringChar(string str)" in the class "solution"

In this Question too, I got an Segmentation (SIGSEGV) error initially. Well, now i looked into my code to debug it. 
I saw that i had write >='z' in line 23. It needed to be <= there, so i changed it an the code ran smoothly and passed all the 50 test cases :)

if you are running this code know that - 
*input output*
it takes an int "t"- this is the number of test cases.
then it takes a string and gives the output char acc to Q
then it taken another string and gives output and it continues till "t" times
