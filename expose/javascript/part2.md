1. Line 12 prints 3, which is the value of i. prices.length = 3, and i is a var type variable in a for loop, which means that its scope is the function. i increments until it reaches 3, and that's what's printed by line 12.
2. Line 13 will print 150 to the console, as discount price is a var type variable, meaning that its scope is the whole function, and for the last iteration of the for loop (at i = 2), discountedPrice's value is set to prices[2] * (1 - discount), or 300 * 0.5, which is 150. (discountedPrice gets rewritten with every iteration of the for loop)
3. Line 14 printed 150 to the console. finalPrice is set to rounded discountedprice, which was 150 for the last iteration of the for loop (question 2). 
4. The function will return the array:
   [ 50, 100, 150 ]
   as it multiplies each price by the discount for each iteration and pushes it into discounted. for i = 1, it takes 100 and multiplies it by 1-0.5 to get the discounted price 50, which it pushes into the array.
5. Line 12 will result in a code error as the variable i is declared using 'let', which means its scope is only in the for loop block.
6. Line 13 will result in a code error (discountPrice not defined), as the variable's scope only extends to the for loop block it was initialized in ('let' keyword).
7. Line 15 will print 150. The last iteration of the loop selects the last price, which is 300, and final price is the discount price, or 300 * (1-0.5) = 150. finalprice's scope extends to the whole function as it was declared in the function block.
8. The function will return the array:
   [ 50, 100, 150 ]
   or, the discounted prices, as the block in the for loop pushes each discounted price into the array. The variable discounted's scope is the function.
9. Line 11 will cause the error 'i is not defined', as the variable i's scope is only the for loop block.
10. Line 12 will print 3 to the console, as the const variable length is initialized to the length of the prices array (3) in line 3.
11. The function will return what it has been returning, the array:
    [ 50, 100, 150 ]
    the discounted prices. discounted is declared with the const keyword, but that doesn't mean items can't be pushed onto the array - it just can't be reassigned.
12. A. student.name
    B. student["Grad Year"]
    C. student.greeting.call()
    D. student["Favorite Teacher"].name
    E. student.courseLoad[0]
13. A. '32' because 2 maps to the string '2' and is concatenated with '3'
    B. 1 , '3' is numerically converted to 3 as - is a numeric operation
    C. 3, as null is numerically converted to 0
    D. '3null', null is converted to a string as '3' is a string and + can concatenate strings
    E. 4, true is numerically converted to 1 as it maps to 1
    F. 0, both false and null map to 0, and are numerically converted to 0
    G. '3undefined', as undefined in converted into a string due to the + operator and '3' being a string
    H. NaN, '3' is numerically converted to 3, and 3 - undefined is not a number
14. A. true, '2' is numerically converted to 1, and 2 > 1
    B. false, the string '2' maps to is greater than '12' as the first char '2' is greater than the first char '1'
    C. true, '2' is numerically converted to 2 and 2 is equal to 2
    D. false, they are of different types
    E. false, true maps to 1 and 1 is not equal to 2
    F. true, as Boolean(2) is true and true === true is true
15. '===' operator checks to see if the two values are equal before type converstion, whereas '==' does this after type conversion (if necessary).
17. The result will be [ 2,4,6 ] as the array and the function go into modifyArray as parameters, and in the for loop, the input array's element at index i is sent in as a parameter for the doSomething function, which doubles the number. this happens for each element of the input array, resulting in an output array that contains each value of the input array doubled.
19. 1
    4
    3
    2