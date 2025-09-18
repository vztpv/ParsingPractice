# ParsingPractice ( Using C or C++)

# Goal
       1. multi line comment
       2. delimiter size >= 1 

# Problem 1. ( print sum of integers, line by line )
       input.txt
         1 2 3 
         4 5 
         6 7 8 
       output.txt
         6
         9
         21
# Problem 2. ( Problem1 + # line comment )
       input.txt
         1 2 3  # sum is 6.
         4 5    # sum is 9.
         6 7 8  # sum is 21.
       output.txt
         6
         9
         21
# Problem 3. ( Problem 2 + , )
       input.txt
         1, 2, 3  # sum is 6.
         4, 5    # sum is 9.
         6, 7, 8  # sum is 21.
       output.txt
         6
         9
         21
# Problem 4. 
       input.txt
         x = 1, y = 2, z = 3  # x = 1 y = 2 z = 3 # also it is ok.  
         %%
         x? y? z?
       output.txt
         1 2 3 
         
