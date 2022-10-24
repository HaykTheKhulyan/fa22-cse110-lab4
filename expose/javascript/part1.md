1. 20
2. 20
   
3. 20
4. There is an error, variable `result` is not defined in this scope. This is because, while we define the variable `result` on line 5, it is defined with the `let` keyword, which means it is only within scope for the block within which it was defined
   
5. There is an error, because we are trying to modify a variable defined with the `const` keyword
6. There is an error, because `result` is not defined in this scope since `const` gives the variable the same scope as the `let` keyword (within the block it is defined)