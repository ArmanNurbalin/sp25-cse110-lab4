1. It will print 3 since var is declared for i it prints the size of the array
2. The code will print 150 since var is used so it is function scoped and after the loop finishes it will print the last updated discountedPrice
3. The code will print 150 since var is used so it is function scoped and after the loop finishes it will print the last version of finalPrice
4. The code will print [50, 100, 150] which is the array of the prices after the discount applied in the loop
5. The code will produce an error since i is declared using let so it is outside the scope and is not accessed
6. The code will produce an error since discountedPrice is declared using let so it is outside the scope and is not accessed
7. The code will print 150 as finalPrice is declared outside the loop where it is updated and the final result is printed
8. The code will print [50, 100, 150] as discounted is declared outside the loop where it is updated and the final array with discounted prices is printed
9. The code will produce an error since i is declared using let so it is outside the scope and is not accessed
10. The code will print 3 which is the length of the array as length is defined in the block and can be accessed
11. The code will print [50, 100, 150] as discounted is declared outside the loop where it is updated and the final array with discounted prices is printed
12. A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]
13. A. '32' because 3 is a string so the + concatenates it with the 2 which maps to the exact string representation
    B. 1 as - makes both values treated as numbers
    C. 3 null is treated as 0
    D. '3null' null gets converted to string and concatenates under +
    E. 4 as true is converted to 1
    F. 0 as both false and 0 are seen as 0
    G. '3undefined' undefined gets converted to string and concatenates under +
    H. NaN because undefined is seen as NaN and - with NaN results in NaN
14. A. true as > makes the numeric comparison making 2 treated as a number
    B. false since both are strings it compares the first element where 2 < 1
    C. true as == converts '2' to its integer representation
    D. false as === is strict equality and since one is a string and the other an integer its false
    E. false as true represents 1
    F. true as Boolean(2) results in true
15. == is equal to so it allows for conversions such as string being seen as an integer and if the both are equal it returns true. === is strict equal meaning for it to return true the values of the elements and the type need to be the same
17. The code will print [2,4,6] as the function modifyArray takes in an array and some callback function as its inputs, where a new array is created. A for loop is created which goes over all the elements in the inputted array and performs the callback function on each element which is then pushed into the new array and then that array is returned. The function doSomething doubles the value its given. So for the final result each element in the original array is doubled.
19. The code outputs 1 4 3 2