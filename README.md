# Internship Assignment-01

Problem Statement:Write a console Application in C++ where first line of input has an integer "n" and next line of input has "n-1" space separated integers having value between 1 to n and no number is repeating. Now you have to find which number is missing.

Logic: As "n" is given in the question,we will take sum of n terms by using formula (n*(n-1))/2 and subtract it with the sum of given n-1 terms and that will be the missing no

Implementation: First step- We will calculate sum of n terms by mathematics formula (n*(n-1))/2 
                Second step: We will create a variable and initialize it with 0.
                Third step: We will store sum of given n-1 terms in the declared variable.
                Fourth step: Then,we will print the difference of sum of n terms and the sum of n-1 stored in the variable.

Time Complexity:O(1) which is constant

Space complexity:O(1) which is constant
                          
                
