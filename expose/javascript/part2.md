1. The program prints the value of `i`, which at line 12 is equal to 3. The variable `i` is still within scope for line 12 since it was defined with the `var` keyword, which makes the variable in-scope for the entire function within which it is defined. 
   
2. The program prints the value of `discountedPrice`, which at line 13 is equal to 150. The variable is still in-scope for the same reason as question 1. 

3. The program prints the value of `finalPrice`, which at line 14 is equal to 150. The variable is still in-scope for the same reason as question 1. 
   
4. The program returns a list with the prices from the original `prices` array, all discounted by the rate given by the `discount` paramter. In this case, it returns [50, 100, 150]



5. There is an error, since the variable `i` is not defined in the scope of line 12. It is defined within the scope of the for loop since the program used the `let` keyword.
   
6. There is an error, since the variable `discountedPrice` is not defined in the scope of line 12. It is defined within the scope of the for loop since the program used the `let` keyword.

7. The program prints the value of `finalPrice`, which at line 14 is equal to 150. The variable is still in-scope since the variable was defined using the `let` keyword earlier in the same block as line 14.
   
8. The program returns a list with the prices from the original `prices` array, all discounted by the rate given by the `discount` paramter. In this case, it returns [50, 100, 150]



9. There is an error, since the variable `i` is not defined in the scope of line 11. It is defined within the scope of the for loop since the program used the `let` keyword.

10. The program prints the variable `length`, which at line 12 is equal to the length of the `prices` parameter, which is 3.

11. The program returns a list with the prices from the original `prices` array, all discounted by the rate given by the `discount` paramter. In this case, it returns [50, 100, 150]



12. A - student.name
    B - student['Grad Year']
    C - 
    D - student['Favorite Teacher'].name
    E - student.courseLoad[0]