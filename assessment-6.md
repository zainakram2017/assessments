# Assessment-6

Type the following program in your editor and observe the results:

```javascript
let trueValue, falseValue;
let x = 5, y = 10;
trueValue = x < y;
falseValue = x > y;
console.log("True is " + trueValue);
console.log("False is " + falseValue);
```

## Startup (02)

Type the following program in your editor:

```javascript
let x = 5, y = 10;
console.log("X is " + x + " and Y is " + y);
if (x > y)
    console.log("X is greater than y");
```

Place semicolon at the end of if condition and then run again and observe the output.

## Startup (03) Even – Odd Number

Type the following program in your editor:

```javascript
const readline = require('readline').createInterface({
    input: process.stdin,
    output: process.stdout
});

readline.question("Enter a number: ", x => {
    if (x % 2 === 0)
        console.log(x + " is even");
    else
        console.log(x + " is odd");
    readline.close();
});
```

## Task-01 (Magic Date)

Write a program that asks the user to enter a month, day and year in numeric form. The program should then determine whether the month times the day is equal to year. If so, it should display that date is magic otherwise date is not magic.

## Task-02 (Area of Rectangle)

The area of rectangle is the rectangle's length times its width. Write a program that asks for the length and width of two rectangles. The program should tell the user which rectangle has the greater area or if the areas are same.

## Task-03 (Body Mass Index)

Write a program that calculates and displays a person's Body Mass Index (BMI). The BMI is often used to determine whether a person with sedentary lifestyle is overweight or underweight for their height. A person's BMI is calculated with following formula:

```
BMI = weight * 703 / height²
```

Where weight is measured in pounds and height is measured in inches. The program should display a message indicating whether the person has optimal weight, is underweight, or is overweight. A sedentary person's weight is considered to be optimal if their BMI is between 18.5 and 25. If the BMI is less than 18.5, the person is considered to be underweight. If the BMI value is greater than 25 then the person is overweight.

## Task-04 (Mass & Weight)

Scientists measure an object's mass in kilograms and its weight in newton. If you know the amount of mass that an object has, you can calculate its weight in newton with following formula:

```md
Weight = mass * 9.8
```

Write a program that asks the user to enter an object's mass, and then calculates and displays its weight. If the object's weight is more than 1000 newton, display a message indicating it is too heavy. If the object's weight is less than 1000 display a message indicating object is too light.

## Task-05 (Time Calculator)

Write a program that asks the user to enter a number of seconds.

- There are 60 seconds in a minute. If the number of seconds entered by the user is greater than or equals to 60, the program should display the number of minutes in that many seconds.
- There are 3600 seconds in an hour. If the number of seconds entered by the user is greater than or equals to 3600, the program should display the number of hours in that many seconds.
- There are 86400 seconds in a day. If the number of seconds entered by the user is greater than or equals to 86400, the program should display the number of days in that many seconds.

## Task-06 (Bank Charges)

A bank charges Rs. 50 per month plus the following cheque fees for a commercial checking account:

- Rs. 10 each for fewer than 20 cheques
- Rs. 08 each for 20-39 cheques
- Rs. 06 each for 40 to 59 cheques
- Rs. 04 each for 60 or more cheques

The bank also charges an extra Rs. 100 if the balance of the account falls below Rs. 15000 (Before any cheque fee applied). Write a program that asks for the beginning balance and number of cheques written. Compute and displays the bank service fee for the month.

Input Validation: Do not accept a negative value for the number of cheques written. If a negative value is given for beginning balance, display an urgent message that an account is overdrawn. If after applying service charges the beginning balance becomes negative, display overdrawn message.

## Task-07 (Shipping Charges)

A shipping company charges the following rates:

| Weight of package (in Kilograms) | Rate per 500 Kilometer Shipped |
|----------------------------------|-------------------------------|
| 2 Kg or less                     | Rs. 50                       |
| Over 2 Kg but not more than 6 Kg | Rs. 100                      |
| Over 6 Kg but not more than 10 Kg| Rs. 150                      |
| Over 10 Kg but not more than 20 Kg| Rs. 200                      |

Write a program that asks for the weight and the distance it is to be shipped, and then displays the charges. Do not accept the weights of less than 0 and more than 20. Do not accept the distance of less than 10 and more than 3000 kilometer.

## Task-08 (Fat Gram Calculator)

Write a program that asks for the number of calories and fat grams in a food. The program should display the percentage of calories that come from fat. If the calories from fat are less than 30% of the total calories of the food, it should also display a message indicating that the food is low in fat.

One gram of fat has 9 calories, so:

```md
Calories from fat = fat grams * 9
```

The percentage of calories from fat can be calculated as:

```md
Calories from fat divided by total calories
```

Input Validation: Make sure the number of calories and fat grams are not less than 0. Also, the number of calories from fat cannot be greater than the total number of calories. If that happens, display an error message indicating either the calories or fat grams were incorrectly entered.

## Task-09 (Sales Commission Calculator)

The salespeople each receive $200 per week plus 9% of their gross sales for that week. For example, a salesperson who sells $5000 worth of chemicals in a week receives $200 plus 9% of $5000, or a total of $650. Develop a program that inputs three salesperson's gross sales for last week and calculates and displays each salesperson's earnings. You also have to compute average, min and max sales and print it as summary. The value of sales must not be negative.

## Task-10 (Credit Limit)

Develop a program that will determine whether a department-store customer has exceeded the credit limit on a charge account. For each customer, the following facts are available:
a) Account number (an integer)
b) Balance at the beginning of the month
c) Total of all items charged by this customer this month
d) Total of all credits applied to this customer's account this month
e) Allowed credit limit

The program should input each of these facts, calculate the new balance (= beginning balance + charges – credits) and determine whether the new balance exceeds the customer's credit limit. For those customers whose credit limit is exceeded, the program should display the customer's account number, credit limit, new balance and the message "Credit Limit Exceeded."

## Task-11 (Palindrome)

A palindrome is a number or a text phrase that reads the same backward as forward. For example, each of the following five-digit integers is a palindrome: 12321, 55555, 45554 and 11611. Write a program that reads in a five-digit integer and determines whether it's a palindrome. [Hint: Use the division and modulus operators to separate the number into its individual digits.]

## Task-12 (Binary to Decimal Conversion)

Input an integer containing only 0s and 1s (i.e., a "binary" integer) and print its decimal equivalent. Use the modulus and division operators to pick off the "binary" number's digits one at a time from right to left. Much as in the decimal number system, where the rightmost digit has a positional value of 1, the next digit left has a positional value of 10, then 100, then 1000, and so on, in the binary number system the rightmost digit has a positional value of 1, the next digit left has a positional value of 2, then 4, then 8, and so on. Thus the decimal number 234 can be interpreted as 2 *100 + 3* 10 + 4 *1. The decimal equivalent of binary 1101 is 1* 1 + 0 *2 + 1* 4 + 1 * 8 or 1 + 0 + 4 + 8, or 13.

## Task-13 (Geometry Calculator)

Write a program that displays the following menu:

```md
1. Calculate the area of a circle
2. Calculate the area of a Rectangle
3. Calculate the Area of a Triangle
4. Calculate the area of a Cylinder
5. Calculate the area of Trapezoid
6. Quit
```

If the user enters 1, the program should ask for the radius of the circle and then display its area. Use the following formula:

```md
Area = π r² where π = 3.14159
```

If the user enters 2, the program should ask for length and width of rectangle and display the area of rectangle using following formula:

```md
Area = length * width
```

If the user enters 3, the program should ask for the length of triangle's base, and its height, and then display its area. Use the following formula:

```md
Area = base * height * 0.5
```

If the user enters 4, the program should ask for the height and radius of the cylinder and display the area of cylinder using following formula:

```md
Area = 2 * π * r² + h (2 * π * r)
```

If user enters 5, the program should ask for base a and base b and height h and compute the area of Trapezoid using the following formula:

```md
Area = h * ((a + b) / 2)
```

If the user enters 6, the program should end.

Input Validation: Display an error message when user enters a number outside the range of 1 through 6 when selecting an item from the menu. Do not accept negative values for the circle's radius, the rectangle's length or width, or triangle's and Trapezoid's base or height.
