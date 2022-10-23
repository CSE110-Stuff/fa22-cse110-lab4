# Expose Part 2

1. Console will log 3 since the var `i` is incremented 3 times in the for loop.
2. Console will log 150 since the for loop will calculate `100*0.5`, `200*05`, and `300*0.5.`The last data recorded by `discountedPrice` is 150.
3. Console will log 150 since the for loop will calculate `100*0.5*100/100`, `200*05*100/100`, and `300*0.5*100/100.`The last data recorded by `finalPrice` is 150.
4. The function would return the list [50,100,150], since the for loop calculates the variables in lines 7 and 8 and pushes them into the list on line 9.
5. The function returns an error since the variable `i` is only accessible in the scope of the for loop because it was declared as `let`.
6. The function returns an error since the variable `discountedPrice` is only accessible in the scope of the for loop because it was declared as `let`.
7. Console will log 150. Since `finalPrice` is declared outside the for loop, its value is accesible when called in line 14.
8. The function would return the list [50,100,150], since the for loop calculates the variables in lines 7 and 8 and pushes them into the list on line 9. Even with `let` each individual element is saved and pushed into `dicounted`.
9. The function returns an error since the variable `i` is only accessible in the scope of the for loop because it was declared as `let`. Same as Question 5.
10. The console would log 3 since that is the length of the list of prices. `length` is a `const` and is declared outside the for loop so it is accessible within the function.
11. The function would return the list [50,100,150], since the list would contain elements with half of their value since each element is `prices[i] * (0.5)`.
12. A. student.name B. student['Grad Year'] C. student.greeting() D. student['Favorite Teacher'].name E. student.courseLoad[0]
13. A.'3' + 2 = '32' because the string takes precedence and `+` is the concatenation of strings. B. '3' - 2 = 1 because the subtraction sign shows that we are subtracting so '3' is converted to a number. C. 3 + null = 3 because null is mapped to 0. D. '3' + null = '3null' because `+` is the concatenation of strings and null is converted to 'null'. E. true + 3 = 4 since true is mapped to 1. F. false + null = 0 since false and null are both mapped to 0. G. '3' + undefined = '3undefined' since `+` is the concatenation of strings and undefined is converted to 'undefined.' H. '3' - undefined = NaN because since we are subtracting '3' -> 3 and undefined -> NaN.
14. A.'2'> 1 = true since 2 >1. B. '2' < '12' = false since the string 2 > string 1. C. 2 =='2' = true since 2 = 2. E. true ==2 = false since true =1 and 1 != 2.F. true ===Boolean(2) = true since Boolean(2) is just true.
15. `==` is an operator that checks if two values are equal. This means the types of the two values can be different and still be compared. `===` is a stricter comparison operator that checks if the two types are the same befroe comparing if the values are equal.
16. 
