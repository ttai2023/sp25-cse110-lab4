1. The bug was that num1 and num2 are read as strings, so when the + operator is
   called within calculateSum, num1 and num2 are concatenated as strings instead 
   of being added together as integers.
2. I would fix it by converting num1 and num2 to integers using Number() before
   using + operator so they can be added together.