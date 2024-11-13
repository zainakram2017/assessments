# Assignment 3

1. Answer following as Yes or No only
   * A. If it is true that x > y and it is also true that x < z, does that mean y < z is true?
   * B. If it is true that x >= y and it is also true that z == x, does that means that z == y is true?
   * C. If it is true that x != y and it is also true that x != z, does that mean z != y is true?

2. Following statements are in English. Convert these statements into JavaScript Language code as [Just write statement]
   * If age is greater than 18, print "You can vote"
   * If score is greater than 60, print "Pass" otherwise print "Fail"
   * If temperature is less than 0, print "Freezing"

3. The following code is syntactically correct, but it appears to contain a logical error. Can you find the error? Identify and rewrite the correct one. Give reason.

   ```javascript
   if (score >= 90)
       grade = "A";
   if (score >= 80)
       grade = "B";
   if (score >= 70)
       grade = "C";
   if (score >= 60)
       grade = "D";
   else
       grade = "F";
   ```

4. Write an if statement that performs the following logic: if the variable sales is greater than 50,000 then assign 0.25 to the variable commissionRate and assign 250 to the variable bonus.

5. Write an if/else statement that assigns 0.10 to the commisionRate unless sales is greater than or equals to 50,000, in which case it assigns 0.20 to commissionRate.

6. If you execute the following code, what it would display on screen if the user enters 5? If the user enters 15? What if user enters 30? What if the user enters -1?

   ```javascript
   let number = parseInt(prompt("Enter a number: "));
   if (number < 10)
       console.log("Less than 10");
   else if (number < 20)
       console.log("Less than 20");
   else
       console.log("20 or more");
   ```

7. What will the following code display?

   ```javascript
   let a = 10, b = 20;
   if (a > b)
       console.log("a is greater");
   else if (a < b)
       console.log("b is greater");
   else
       console.log("both are equal");
   ```

8. The following code is used in a book store program to determine how many discount coupons a customer gets. What are the number of coupons if a customer purchase 1,3,4,5,7 or 10 books.

   ```javascript
   if (books >= 1 && books < 3)
       coupons = 1;
   else if (books >= 3 && books < 5)
       coupons = 2;
   else if (books >= 5)
       coupons = 3;
   else
       coupons = 0;
   ```

9. Indicate whether each of the following relational expressions is true or false:
   * 'A' < 'B'
   * 'Z' > 'a'
   * '0' < '9'
   * 'A' < 'a'

10. Rewrite the following if/else statements using conditional operator:

    ```javascript
    // Statement 1
    if (x > y)
        max = x;
    else
        max = y;

    // Statement 2
    if (age >= 18)
        status = "Adult";
    else
        status = "Minor";

    // Statement 3
    if (score >= 60)
        result = "Pass";
    else
        result = "Fail";
    ```

11. The following statements are conditional expressions. Rewrite each with and if/else statement:

    ```javascript
    // Expression 1
    let max = num1 > num2 ? num1 : num2;

    // Expression 2
    let status = age >= 21 ? "Adult" : "Minor";

    // Expression 3
    let fee = isMember ? 2.00 : 10.00;
    ```

12. What will the following program display?

    ```javascript
    let x = 20, y = 10;
    let result = x > y ? "x is greater" : "y is greater";
    console.log(result);
    ```

13. Write and if statement that prints the message "The number is valid" if the variable temperature is within range -50 through 150.

14. Match the conditional expression with the if/else statements that performs the same operation:

    ```javascript
    // Expression
    z = x > y ? x : y;

    // Statements
    if (x > y)
        z = x;
    else
        z = y;
    ```

15. Following program has error, locate the error and rewrite the code by mentioning error in comment:

    ```javascript
    if x > y {
        console.log("x is greater");
    }
    ```

16. Following program has error, locate the error and rewrite the code by mentioning error in comment:

    ```javascript
    if (x > y)
        console.log("x is greater");
        console.log("y is smaller");
    ```

17. The following statement should determine if count is within range of 0 through 100. What is wrong with it?

    ```javascript
    if (count>=0 || count <=100)
    ```

18. The following statement should determine if count is outside the range of 0 through 100. What is wrong with it?

    ```javascript
    if (count<0 && count >100)
    ```
