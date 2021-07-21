# LAB ASSIGNMENT

## Pattern - 
1*\
1 2 * *\
1 2 3 * * * \
1 2 3 4 * * * *\
1 2 3 4 5 * * * * * 

## Student Names
1. Ayushi jain(M.Sc,Roll no- 08)
2. Chandan sharma(M.Sc ,Roll no-10)

### Program Description

Logic :
we have use nested for loop to print this pattern

The first 'for' loop is used for the number of rows that starts from 1 and goes up to  the row number given by the user (row number represent the total number of lines we have to print for this pattern) 

The second 'for' loop is used for the column number(i.e how many columns we have in each row or basically how many elements we have to print in the current row i.e for each row, the number of elements we have to print is twice of the current  row number)\
i.e if row no is 1st -> prints 2 elements\
     if row number is 2nd ->prints 4 elements\
     and so on for the rest of rows)

so second "for" loop starts from the 1 and goes upto the twice of current row number (for each row)\
and in second for loop we are checking :\
if (j<=i) i.e if the  current cloumn number is less than or equal to the current row number we are printing that column number or that element

otherwise if current column number is greater than the current row number we are printing "*"

and after ending of second for loop(i.e after printing all elements for current row) we are providing new line and again it goes to first "for" loop ,and print all the elements for next row and repeat the same procedure for all the remaining rows. 


