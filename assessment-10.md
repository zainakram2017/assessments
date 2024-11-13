# Assessment-10

Type the following program in your editor and observe the results:

```javascript
const arr = [12, 34, 54, 67, 89, 24];
for (let x = 0; x < 6; x++) {
    console.log(arr[x]);
}
```

## Startup (02) (Understand Functions)

Type the following program in your editor and observe the results:

```javascript
function displayMessage() {
    console.log("Hello from the displayMessage() Function.");
}

console.log("Hello from the Main.");
displayMessage();
console.log("Good Bye from main.");
```

## Understanding how function call works

This will allow students to understand how a function call works to get results from functions.

```javascript
let total = sum(value1, value2); // Function Call
```

## Algorithmic Workbench

- `name` is an integer array with 20 elements. Write a for loop that prints each element of the array.
- The arrays `numberArray1` and `numberArray2` have 100 elements. Write a loop that copies the values from `numberArray1` to `numberArray2`.

## Task-01 (Largest/Smallest Array Value)

Write a program that lets the user enter 10 values into an array. The program should then display the largest and smallest value of the array.

## Task-02 (Rainfall Statistics)

Write a program that lets the user enter the total rainfall for each of 12 months into an array of doubles. The program should calculate and display the total rainfall for the year, the average monthly rainfall, and the month with the highest and lowest amounts.

**Input validation:** Do not accept negative numbers for monthly rainfall figures

## Task-03 (Element Swapping)

Write a Program that will input an array of 10 integers. Your program will swap every element with its next elements and then print it.

## Task-04 (Reverse Array Elements)

Write a program that will reverse the elements of 1-D array. Your program will do the following:

- Ask user to size of array to insert integer elements
- Inputs array elements
- Reverse them and then print

## Task-05 (Element Rotation)

Write a program that will input an integer array. Your program will print the array after rotating the elements of array.

## Task-06 (Element Exchange)

Write a program that will input an array of integer of odd size. Your program will exchange the middle element of array with the first, last element with middle and first element with last element of array and then print.

## Task-07 (Printing Even Elements)

Write a program that inputs an array of size given by user. The program will then print only even values of arrays.

## Task-08

Write a program that inputs an integer array and swap first and last element of an integer 1-d array.

## Task-09 (Merging Arrays)

Suppose A, B, C are arrays of integers of size M, N, and M + N respectively. The numbers in array A appear in ascending order while the numbers in array B appear in descending order. Write a program to produce third array C by merging arrays A and B in ascending order. Make use of nested loop where required.

## Task-10 (Lottery Application)

Write a program that simulates a lottery. The program should have an array of five integers named lottery, and should generate a random number in the range of 0 through 9 for each element in the array. The user should enter five digits which should be stored in an integer array named user. The program is to compare the corresponding elements in the two arrays and keep a count of the digits that match.

The program should display the random numbers stored in the lottery array and the number of matching digits. If all the digits match display a message proclaiming the user as a grand prize winner.

## Task-11 (Markup)

Write a function that asks user to enter an item's wholesale cost and its markup percentage. It should then display the item's retail price. For example:

- If an item's wholesale cost is 5.00 and its markup percentage is 100%, then the item's retail price is 10.00.
- If an item's wholesale cost is 5.00 and its markup percentage is 50%, then the item's retail price is 7.50.

The program should have a function named `calculateRetail` that receives the wholesale cost and markup percentage as argument and returns the retail price of the item.

**Input validation:** Do not accept negative values for either wholesale cost of item or percentage.

## Task-12 (Falling Distance)

When an object is falling because of gravity, the following formula can be used to determine the distance of object falls in specific time period:
d = ½gt²

The variables in the formula are as follows: d is the distance in meters, g is 9.8, and t is the amount of time, in seconds, that object has been falling.

Write a function named `fallingDistance` that accepts an object's falling time (in seconds) as an argument. The function should return distance, in meters, that the object has fallen during that time interval. Write a program that demonstrates the function by calling it in a loop that passes the values 1 through 10 as arguments, and display the return value.

## Task-13 (Kinetic Energy)

In Physics, an object that is in motion is said to have kinetic energy. The following formula can be used to determine a moving object's kinetic energy:
KE = ½mv²

The variables in the formula are as follows: KE is the kinetic energy, m is the object's mass in kilogram, and v is the object velocity, in meters per second.

Write a function named `kineticEnergy` that accepts an object's mass (in kilogram) and velocity (in meter per seconds) as arguments. The function should return the amount of kinetic energy that the object has. Demonstrate the function by calling it in a program that asks the user to enter values for mass and velocity.

## Task-14 (Present Value)

Suppose you want to deposit a certain amount of money into a savings account, and then leave it alone to draw interest for the next 10 years. At the end of 10 years, you would like to have Rs. 1,000,000 in the account. How much do you need to deposit today to make that happen? You can use the following formula, which is known as the present value formula:
P = F/(1 + r)ⁿ

The terms in the formula are as follows:

- P is the present value or the amount that you need to deposit today
- F is the future value that you want in the account (in this case, F is Rs. 1,000,000)
- r is the annual interest rate
- n is the number of years that you plan to let the money sit in the account

Write a program that has a function named `presentValue` that performs this calculation. The function should accept the future value, annual interest rate, and the number of years as arguments. It should return the present value, which is the amount that you need to deposit today. Demonstrate the function in a program that lets the user experiment with different values for the formula's terms.

## Task-15 (Star Search)

A particular talent competition has five judges, each of whom awards a score between 0 and 10 to each performer. Fractional scores, such as 8.3, are allowed. A performer's final score is determined by dropping the highest and lowest score received, then averaging the three remaining scores. Write a program that uses this method to calculate a contestant's score. It should include the following functions:

- `getJudgeData()` should ask the user for a judge's score, store it in a reference parameter variable and validate it. This function should be called by main once for each five judges.
- `calcScore()` should calculate and display the average of the three scores that remain after dropping highest and lowest scores the performer received. This function should be called just once by main and should be passed the five scores.

The last two functions, described below, should be called by `calcScore`, which uses the returned information to determine which of the scores to drop:

- `findLowest()` should find the lowest of the five scores passed to it.
- `findHighest()` should find the highest of the five scores passed to it.

**Input validation:** Do not accept scores below 0 and above 10.
