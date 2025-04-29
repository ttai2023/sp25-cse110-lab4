1. 3 will be printed because that is what i was when exiting the for loop. Since 
   it is declared with var it is visible throughout the entire function.
2. 150 will be printed because that was the last assignment of discountedPrice. 
   Since it is declared with var it is visible throughout the entire function.
3. 150 will be printed because that was the last assignment of finalPrice. Since 
   it is declared with var it is visible throughout the entire function.
4. The function will return [50, 100, 150] because 50, 100, 150 were pushed into
   discounted in the for loop after calculating discountedPrice and finalPrice
   for each price in prices. 
5. The code will cause an error as console.log() won't see i. This is because i 
   was declared with let, so it is only visible within the for loop.
6. The code will cause an error as console.log() won't see discountedPrice. This 
   is because discountedPrice was declared with let, so it is only visible 
   within the for loop.
7. 150 will be printed as that is the last assignment of finalPrice. Since it 
   was declared outside of the for loop, it is visible throughout the function,
   hence able to be printed by console.log().
8. The function will return [50, 100, 150] because 50, 100, 150 were pushed into
   discounted in the for loop after calculating discountedPrice and finalPrice
   for each price in prices. Since discounted was declared outside of the for 
   loop, it is visible throughout the function, therefore can be returned. 
9. The code will cause an error as console.log() won't see i. This is because i 
   was declared with let, so it is only visible within the for loop.
10. 3 will be printed because prices.length is 3, and it is declared with const
    outside of the for loop so it is visible to console.log().
11. The function will return [50, 100, 150] because 50, 100, 150 were pushed 
    into discounted in the for loop after calculating discountedPrice and 
    finalPrice for each price in prices. Since discounted was declared outside 
    of the for loop, it is visible throughout the function, therefore can be 
    returned. 
12. A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]
13. A. "32" since integers map to their exact string representation
    B. 1 because '3' maps to 3, 3 - 2 = 1
    C. 3 because null maps to 0, 3 + 0 = 3
    D. "3null" because string of null is "null"
    E. 4 because true maps to 1, 1 + 3 = 4
    F. 0 because false maps to 0 and null maps to 0, 0 + 0 = 0
    G. "3undefined" because undefined maps to "undefined"
    H. NaN because integer of undefined is NaN
14. A. true because string '2' becomes a number 2
    B. false because lexicographical order for strings, '2' > '12'
    C. true because '2' becomes number 2 and 2==2 is true
    D. false because their types are different
    E. false because true maps to 1 and 1 does not equal 2
    F. true because Boolean(2) is true
15. == is a regular equality operator, so different types can be evaluated
    to equal as operands of different types are converted to numbers. === is a
    strict equality operator, so it checks equality without the type conversion.
17. The result will be [2, 4, 6]. Once newArr was declared, the for loop is 
    entered. for each value in the original array, callback is called, which
    is the doSomething function. This function multiplies each element by 2, so
    1 -> 2, 2 -> 4, 3 -> 6. Then, each of these elements gets added to newArr.
    newArr is returned at the end, which contains [2, 4, 6].
19. 1
    4
    3
    2