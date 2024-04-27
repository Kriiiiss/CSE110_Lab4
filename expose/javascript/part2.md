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


### Question 13:
A: `32`. `32` is a string type. Number 2 will change to string and then combine them together using `+` sign.
B: `1`. `1` is a number type. String `3` will change to number type and `-` sign can only be used in number calculation.
C: `3`. `3` is a number type. `null` will change to number 0 and `3+0` is equal to 3.
D: `3null`. `3null` is a string type. string `3` and `null` will combine together and formed `3null`.
E: `4`. `4` is a number type. `true` will change to number 1 and `1+3 = 4`
F: `0`. `0` is a number type. Since both are not string type, and both can change to number `0`. `0+0=0`. 
G: `3undefined`. `3undefined` is a string type. `3` is a string and `undefined` will be change to string type. So they will form `3undefined`.
H: `NaN`. This is Not a Number. Since `-` sign cannot be used in string and it also cannot be changed to number. Thus, it will output `NaN`

### Question 14:
A: true. They are different type, so string `2` will change to number type. `2>1` is true.
B: false. Two string will compare from the first digit. `'2' < '1'` is false.
C: true. String `2` will change to number. `2=2`is true. 
D: false. `===` will not perform type change. There are two different types and it will output false.
E: false. `true` will convert to number `1` and `1==2` is false. 
F: true. `Boolean(2)` is true since non-zero number in boolean is true. Both are same type, so it is true. 

### Question 15:
`==` will attempt to conver the value into same type and then take a comparison. Different type can also be compared. However, `===` can only used to compare in same type. If the value are two different type, it will directly return false.

### Question 16:
```
for (let p in statistics) {
    if (p.startsWith('r') || statistics[p] % 2 === 1) {
        console.log(statistics[p]);
    }
}
```

### Question 17:
The result will be `[2, 4, 6]`. We pass an array and an function to `modifyArray` function. Within the function, it will run `for loop` and iterate each value in array. `callback(array[i])` will run `doSomething(array[i])` so it will return `num*2`. Then, the value will be pushed into `newArr`. After iterate all value in this array, the output will be `[2, 4, 6]`.

### Question 18:
```
function printCurrentTime(){
    let d = new Date();
    let time = d.toLocaleTimeString();
    console.log(time);
}

setInterval(printCurrentTime, 1000);
```

### Question 19:
The output will be `1 4 3 2`. The reason is `console.log(1) and console.log(4)` will directly output without call any function. Since `setTimeout(function() {console.log(2);}, 1000);` will be called, but it have to wait 1 second and it will be slower than `setTimeout(function() {console.log(3);}, 0);`


