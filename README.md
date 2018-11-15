# Homework Assignment 1

**Problem 1: Object Types (Weight 2)**. 
Consider the number 17. 
Construct multiple variables (`y1`, `y2`, `y3`, and `y4`) in Python that 
represent the number 17 in the various forms of objects
 (integer, float, string, and Boolean, respectively). 
 *Hint*: For creation of the Boolean, set a value for 17 to be compared against another number.
1.	Print the value of `y1`, `y2`, `y3`, and `y4` and their types 
(*Hint*: you can use function `type()` to get a type of an object or variable). 
2.	Use `y1`, `y2`, or `y3` to create a variable named `text` such 
that `print(text)` prints `The value of x is 17.`

**Problem 2: String Operations (Weight 1)**. 
Create a string that contains the following: 
“I”, “love”, “learning”, “how”, “to”, “code”, and “!”. 
Use string operators to create a syntactically correct sentence 
(stored in variable `text`) that yields 
`I love learning how to code!` when printed to the user. Print the content of `text`.

**Problem 3: Iterative and Recursive Operations (Weight 4).**
 Write an iterative function and a recursive function that computes 
 the sum of all numbers from `1` to `n`, where `n` is given as parameter. 
 Test both functions for `n = 100`.
 
**Problem 4: Lists and Mutability (Weight 2)**.  
Create a list, named `yours`, to store my favorite schools: 
‘Yale’, ‘MIT’, and ‘Berkeley’; 
and create a list, named `mine`, to store 3 of your favorite schools 
whatever they are. 
Use the `+` operator to create a new list, named `ours1`, 
to represent our favorite schools:

    ours1 = mine + yours

Now, create another list, name `ours2`, to again represent our favorite schools 
but this time use: 

    ours2 = []
    ours2.append(mine)
    ours2.append(yours)

Answer these questions: 
1.	Print `ours1` and `ours2`. Describe how `ours1` and `ours2` differ from 
each other.
2.	Change the second element of yours to something else and 
again print `ours1` and `ours2`. 
Explain why changing yours would changes `ours2` but not `ours1`. 
 
**Problem 5: Dictionaries (Weight 2).**
 Create a dictionary for the months of the year that can be called by 
 the number of months (i.e. 1, 2, ..., 12) or the name of months 
 (i.e. January, February, ..., December). 
 Write a statement that prints `The sixth month is June.` 
 and another statement that prints `February is month 2.`

