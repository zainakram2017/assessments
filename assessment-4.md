# Assessment-4

Type the following program in your editor:

```javascript
const readline = require('readline').createInterface({
    input: process.stdin,
    output: process.stdout
});

async function calculateArea() {
    let length, width, area;
    
    console.log("This program calculates the area of a rectangle.\n");
    
    await new Promise(resolve => {
        readline.question("Enter the Length of Rectangle: ", input => {
            length = Number(input);
            resolve();
        });
    });
    
    await new Promise(resolve => {
        readline.question("Enter the Width of Rectangle: ", input => {
            width = Number(input);
            resolve();
        });
    });
    
    area = length * width;
    console.log("The area of rectangle is " + area);
    readline.close();
}

calculateArea();
```

- Compile the code and observe the program output.
- Change the case of variables and then observe the behavior of program.
- Try to enter input with space, fractional value and character value and observe the output.

## Task-01

Study the following program and complete the table. You may execute this program:

```javascript
const readline = require('readline').createInterface({
    input: process.stdin,
    output: process.stdout
});

async function calculate() {
    let value1, value2, value3;
    
    await new Promise(resolve => {
        readline.question("Enter the number: ", input => {
            value1 = Number(input);
            resolve();
        });
    });
    
    value2 = 2 * Math.pow(value1, 2.0);
    value3 = 3 + value2 / 2 - 1;
    console.log(value3);
    readline.close();
}

calculate();
```

Complete the table:

| If user enters | Value of variable value3 displayed |
|----------------|-----------------------------------|
| 2              |                                   |
| 5              |                                   |
| 4.3            |                                   |
| 6              |                                   |

## Task-02 (Credit Available)

A retail store grants its customers a maximum amount of credit. Each customer's available credit is their maximum amount of credit minus the amount of credit used. Write a pseudo code on paper that asks for a customer's maximum amount of credit and amount of credit used. The program should display the remaining credit. Convert this algorithm into a complete JavaScript program in your lab.

## Task-03 (Golf Scores)

Write an algorithm that asks user to enter a golfer's score for three games of golf and then display the average of three scores. After you write algorithm, convert it into complete JavaScript program.

## Task-04 (Underflow & Overflow)

Write a program that defines a variable named test and initialize it with 32767. Display the value. Then add one (1) to test and display the value. Then subtract one(1) from test and display the value. Write your observation for three value assignments you done.

## Task-05 (Trigonometry)

Assume variable angle1 and angle2 holds angles in radians. Write a program that adds the sine of angle1 to cosine of angle2, and stores the result in variable x.

## Task-06 (Cosecant)

The cosecant of the angle a is 1 / sine(a). Write a program that calculates the cosecant of the angle stored in variable a and store the result in variable y. Display the result.

## Task-07 (Denomination)

Write a program which accepts amount as integer and display total number of Notes of Rs. 500, 100, 50, 20, 10, 5 and 1.
For example, when user enter a number, 575, the results would be like this:

```
500: 1
100: 0
50: 1
20: 1
10: 0
5: 1
1: 0
```

## Task-08 (Stadium Capacity)

There are three seating categories at a stadium. For a softball game, Class A seats costs Rs. 2000, Class B seats cost Rs. 1000, and class C seats cost Rs. 500. Write a program that asks how many tickets for each class of seats were sold, then display the amount of income generated from ticket sale.

## Task-09 (Average Rainfall)

Write a program that calculates the average rainfall for three months. The program should ask the user to enter the name of month, such as June or July and the amount of rain (in millimeters) that fell each month. The program should display a message similar to the following:
"The average rain for July, August & September is 20.65 millimeter."

## Task-10 (Box Office)

A movie theater only keeps 20 percent of the revenue earned from ticket sale. The remainder goes to the movie distributor. Write a program that calculates a theater's gross and net box office profit for a night. The program should ask for:

- Name of the movie
- How many adult and child tickets were sold
- If an adult is above sixty then a further 10 percent discount is offered
- The price of adult ticket is Rs. 500 and for child is Rs. 250

The program should display report similar to:

```
Movie Name "Action"
Adult Tickets Sold 382
Child Ticket Sold 127
Adults Above 60 10
Gross Box Office Profit Rs.
Net Box Office Profit Rs.
Amount Paid to Distributor Rs.
```

## Task-11 (Calories per serving)

A bag of cookies holds 40 cookies. The calories information on the bag claims that there are 10 "servings" in the bag and that a serving equals to 300 calories. Write a program that asks the user to input how many cookies he or she actually ate and then report how many total calories were consumed.

## Task-12 (Senior Citizen Property Tax)

Madison County provides a $5,000 homeowner exemption for its senior citizens. For example if a senior's house is valued at $158,000 its assessed value would be $94,800, as explained above. However, it would only pay tax on $89,800. At last year's tax rate of $2.64 for each $100 of assessed value, the property tax would be $2,370.72. In addition to the tax break, senior citizens are allowed to pay their property tax in four equal payments. The quarterly payment due on this property would be $592.68. Write a program that asks the user to input the actual value of a piece of property and the current tax rate for each $100 of assessed value. The program should then calculate and report how much annual property tax a senior homeowner will be charged for this property and what the quarterly tax would be.

## Task-13 (Interest Earned)

Assuming there are no deposits other than the original investment, the balance in a saving account after one year may be calculated. Principal is the balance in the saving account, rate is the interest rate and T is the number of times interest is compounded during year (T is 4 if the interest is compounded quarterly). Write a program that asks for the principal, the interest rate, and the number of times the interest is compounded. It should display report similar to:

```
Interest Rate: 4.25%
Time Compounded: 12
Principal: Rs. 1000
Interest: Rs. 43.34
Amounts in Savings: Rs. 1043.34
```

## Task-14 (Monthly Payments)

The monthly payment on a loan may be calculated by the following formula. Rate is monthly interest rate, which is the annual interest rate divided by 12. (12% annual interest would be 1 percent monthly interest.) N is the number of payments and L is the amount of loan. Write a program that asks for these values and displays report similar to:

```
Loan Amount: Rs. 10000
Monthly Interest Rate: 1%
Number of Payments: 36
Monthly Payments: Rs. 332.14
Amount Paid Back: Rs. 11957.15
Interest Paid: Rs. 1957.15
```

## Task-15 (Pizza PI)

Pizza Palace needs a program to calculate the number of slices a pizza of any size can be divided into. The program should perform the following steps:
A. Ask the user for diameter of Pizza in inches
B. Calculate the number of slices that may be taken from a pizza of that size
C. Display a message telling the number of slices

To calculate the number of slices that may be taken from the pizza, you must know the following facts:

- Each slice should have an area of 14.125 inches
- To calculate the number of slices, simply divide the area of the pizza by 14.125
- The area of the pizza is calculated with this formula: Area = PI *r* r

## Task-16 (How many Pizzas?)

Modify the program you wrote in Programming Challenge 13 (Pizza PI) so that it reports the number of pizzas you need to buy for a party if each person attending is expected to eat an average of four slices. The program should ask the user for the number of people who will be at the party and for the diameter of the pizzas to be ordered. It should then calculate and display the number of pizzas to purchase.

## Task-17 (Stock Transaction Program)

Last month Kathryn purchased some stocks in ACME Software. Here are the details of the purchase:

- The number of shares that Kathryn purchased was 1000
- When Kathryn purchased the stock, she paid Rs. 32.87 per share
- She also paid broker a commission that amounted 2% of the amount she paid for the stock

Two weeks later Kathryn sold the stock. Here are the details of the sale:

- The number of shares that Kathryn sold was 1000
- She sold the stock for Rs.33.92 per share
- She paid her stock broker another commission that amounted to 2% of the amount she received for the stock

Write a program that displays the following information:

- The amount of money Kathryn paid for the stock
- The amount of commission Kathryn paid her broker when she bought the stock
- The amount that Kathryn sold the stock for
- The amount of commission Kathryn paid her broker when she sold the stock
- Display the amount of profit that Kathryn made after selling her stock and paying the two commissions to her broker. (If the amount is in negative then it means Kathryn lost money on transaction)
