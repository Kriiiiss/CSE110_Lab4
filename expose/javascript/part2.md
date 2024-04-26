# Part 2

### Question 1:
Line 12 will print `3`. The reason is the type of `i` is `var` and there's 3 numbers in an array. The `for loop` will run 3 times since `prices.length = 3` and `i < prices.length` and `i` will increase 1 each time. Finally, `i` will equal to 3 at the end and line 12 will print `3` since type `var` can be used within the function. 

### Question 2:
Line 13 will print `150`. The reason is that `discountedPrice` will equal to `price[2] * (1-discount);` at the end. `price[2] = 300` and `discountedPrice` will equal to `150` after calculation. Thus, it will print `150`.

### Question 3:
Line 14 will print `150`. The reason is that `discountedPrice = 150` at the end. `finalPrice` will equal to `150` after Math calculation. Thus, it will print `150`.

### Question 4:
This function will return `[50, 100, 150]`. The reason is `discounted` is an empty array at first. After calculating the `finalPrice`, it will be pushed to `discounted`. All value will be stored in `discounted`. Thus, `discounted = [50, 100, 150]` at the end. Thus, the function will return `[50, 100, 150]`.

### Question 5:
This code will return an error: `ReferenceError: i is not defined`. The reason is the type of `i` is `let` and it can only be used within the `for loop`. The `console.log(i)` is called outside the `for loop`, and `i` is not defined outside. Thus, it will cause error. 

### Question 6:
This code will return an error: `ReferenceError: discountedPrices is not defined`. The reason is the type of `discountedPrices` is `let` and it can only be used within the `for loop`. The `console.log(discountedPrices)` is called outside the `for loop`, and `discountedPrices` is not defined outside. Thus, it will cause error. 

### Question 7:
It will print `150`. The reason is that `finalPrice` is defined outside the `for loop`. The value of `finalPrice` is changed after calculating. Thus, it will print `150`.

### Question 8:
This function will return an array `[50, 100, 150]`. The `discounted` is defined within the function outside the `for loop`. Value will be pushed into `discounted`. At the end, `discounted = [50, 100, 150]`. Thus, `return discounted` will return `[50, 100, 150]`.

### Question 9:
This code will return an error: `ReferenceError: i is not defined`. The reason is the type of `i` is `let` and it can only be used within the `for loop`. The `console.log(i)` is called outside the `for loop`, and `i` is not defined outside. Thus, it will cause error. 

### Question 10:
Line 12 will print `3`. The reason is the type of `length` is `const` and there's 3 numbers in an array. So `length = 3` and it will not be change. There is no re-assign value to `length`, so it will not cause any error. Thus, it will print `3`.

### Question 11:
This function will return an array `[50, 100, 150]`. The `discounted` is defined within the function outside the `for loop`. Value will be pushed into `discounted`. `const discountedPrice` will change address for each loop. `const` can also be used to push value. At the end, `discounted = [50, 100, 150]`. Thus, `return discounted` will return `[50, 100, 150]`.

### Question 12:
A: student.name
B: student['Grad Year']
C: student.greeting()
D: student['Favorite Teacher'].name
E: student.courseLoad[0]


### Question 11:

### Question 11:

### Question 11:

### Question 11:

### Question 11:

### Question 11:

### Question 11:

### Question 11:


