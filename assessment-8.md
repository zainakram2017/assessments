# Assessment-8

Type the following program in your editor and observe the results:

```javascript
let x = 1;
while (x <= 10) {
    console.log(x);
    x++;
}
```

## Task-01 (Reverse a Number)

Write a program to reveres any given integer number.

```
Input: 12345
Revers: 54321
```

## Task-02 (Sum of digits)

Write a program to sum of digits of any given integer number.

```
Input: 459
Sum: 18
```

## Task-03 (Denomination)

Change the Lab-task-05 of Lab-02 to find denomination in given amount. Use the same scenario and implement the task using while loop.

## Task-04 (Sum of Numbers)

Write a program that ask user to enter a positive number (do not accept –ve number). The program should use a while loop to sum all the number from 1 up to the number entered.

## Task-05 (Ocean Level)

Assuming the oceans level is currently rising at about 1.5 millimeters per year, write a program that display a table showing number of millimeters that the ocean will have risen each year for the next 25 years. Assuming the starting year is 2018.

## Task-06 (Sum the geometric series)

Write a program that sums the first n items in a geometric series using while loop. User will input the n. use the following formula or use your previous knowledge.

## Task-07 (Membership Fee Increase)

A country club, Which currently charges Rs. 2500 per year for a membership, has announced it will increase its membership 4% each year for the next six years. Write a program that uses while loop to display projected rates for the next six years.

## Task-08 (Population)

Write a program that predicts the size of a population of organisms. The program should ask the user for the starting number of organism, their average daily population increase (as percentage), and the number of days they will multiply. A loop should display the size of population for each day.

**Input Validation:**

- Do not accept a number less than 2 for the starting size of population
- Do not accept a negative number for average daily population increase
- Do not accept a number less than 1 for the number of days they will multiply

## Task-09 (Projected Score)

A team is currently scoring with the run rate of 6.25 per over. The team has scored 188 in the 30 over while its 4 players are back in pavilion. Write a program that display projected score for next 5,10,15 and 20 overs if the team continue to score with current run rate or with run rate of 7,8,9 and 10. Display Score in the following format. Use while loop.

```md
Overs bowled    6.25    7    8    9    10
Projected Score
In 35 Overs
In 40 Overs
In 45 Overs
In 50 Overs
```

## Task-10 (Math Tutor)

Write a program that generate two random numbers and ask the users to write the sum of two numbers. You have to write a program that uses a do while loop to allow user to test his/her addition skills as long as he/she wants to. When the loop end the program must tell the user that how many answers were correct out of asked question.

## Task-11 (Hotel Occupancy)

Write a program that calculates the occupancy rate for a hotel. The program should start by asking the user how many floors the hotel has. A loop should then iterate one for each floor. In each iteration, the loop should ask the user for the number of rooms on the floor and how many of them are occupied. After all the iterations, the program should display how many rooms the hotel has and the percentage of rooms that are occupied.

**Input validation:**

- The program should not accept the number less than 1 for the number of floors
- Do not accept a number less than 10 for number of rooms on each floor

## Task-12 (Palindrome)

Modify task-11 of lab 3 so it may accept integer of any length to determine whether its palindrome or not.

## Task-13 (Binary to Decimal Conversion)

Modify Task 12 of Lab-03 so it may accept binary number of any bits and converts it into decimal number using loop.

## Task-14 (Saving Account Balance)

Write a program that calculates the balance of a saving account at the end of a period of time. It should ask the user for the annual interest rate, the starting balance, and the number of months that have passed since the account was established. A loop should then iterate once for every month, performing the following:

A. Ask the user the amount deposited into the account during the month. (Do not accept negative numbers). This amount should be added to the balance

B. Ask the user for the amount withdrawn from the account during the month. (Do not accept negative numbers). This amount should be subtracted from the balance

C. Calculate the monthly interest rate. The monthly interest rate is the annual interest rate divided by twelve. Multiply the monthly interest rate by the balance and add the result to the balance

After the last iteration the program should display:

- The ending balance
- The total amount of deposits
- The total amount of withdraws
- The total interest earned

If a negative balance is calculated at any point, a message should display indicating that account has been closed and loop should terminate.
