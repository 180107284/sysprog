# sysprog
1st step is declaring variable (mainRes). Next row will help us to read the input file line by line.  
When while loop is starts, it will go through if and else conditions. 
If statement- if errors equal to 4, then mainres will be equal to mainres+1. 
Else it will be equal to 1.
If we finished to read all file it’s a ‘done’ row.
Next step is declaring result variable.  Total = 0.  Then we create ‘for’ loop.
It will equalize  maxkey to the empty string and maxval to the 1.  
In inner loop — for key in ${!mainRes[@]},
we take value from mainres variable , match its value and assigned to maxval variable.
Result and total will be equal go maxval.
We round it and print our output.
