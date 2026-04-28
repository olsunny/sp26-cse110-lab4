1. It will print 3 since i is declared as a var, and var can not be block or loop 
local. 
2.  It will print 150 since discountedPrice is declared as a var, and var can 
not be block or loop local, and the last assignment to discountedPrice was 150 from 
doing 300 * (1 - 0.5). 
3. It will print 150 since finalPrice is declared as a var, and var can 
not be block or loop local, and the last assignment to finalPrice was 150 from 
doing (150*100)/100. 
4. This function will return [50,100,150] because discounted is declared as a var, 
and var can not be block or loop local, and was pushed to 3 times in the loop.
5. The code will give an error because the let variable i is declared in the for 
loop and is only visible within the for loop code block. 
6. The code will give an error because the let variable discountedPrice is declared in the for 
loop and is only visible within the for loop code block.
7. The code will output 150 because the let variable finalPrice is declared outside 
of the for loop.
8. This function will return [50,100,150] because discounted is declared outside of 
the for loop and modified within it.
9. The code will give an error because the let variable i is declared in the for 
loop and is only visible within the for loop code block. 
10. The code will print 3.
11. This function will return [50,100,150] because discounted is declared outside of 
the for loop and modified within it.
12a. student.name
12b. student['Grad Year']
12c. student.greeting()
12d. student['Favorite Teacher'].name
12e. student.courseLoad[0]
13a. 32 because 2 is type converted into a string
13b. 1 because 3 is type converted into an int
13c. 3 because null is converted to 0
13d. 3null because null is converted to a string
13e. 4 because true is converted to 1
13f. 0 because both false and null map to 0
13g. 3undefined because undefined is converted into a string
13h. NaN because undefined can not be converted into an int while '3' can be (and 
the operation is - so both values have to be integers)
14a. true because '2' is converted into 2
14b. false because '2' and '12' are compared by lexicographic order and '2' is greater than '1', so the comparison stops immediately
14c. true because '2' is converted into 2
14d. false because === is a strict equality operator
14e. false because true converts to 1
14f. true because Boolean(2) converts 2 into true (all values except 0, -0, NaN convert to true)
15. == is a loose equality that allows for type conversion to find a common type before comparison while === is a strict equality that does not allow for type conversion and only allow true if sides are of same type and value
17. It returns [2,4,6] because in the for loop, callback is called with the elements in array, and in this case, callback is the function doSomething, which doubles the indexed element and pushes it into the new array.
19. Prints in the order of 1, 4, 3, 2, since setTimeout waits for console to run all synchronous lines of code first before addressing its own functions. 