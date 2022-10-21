# U4S1 Boolean Expressions

* Part A - Foundations 5.1
* Part B - Foundations Practice
* Part C - Instructor Challenge

## Part A

### Exercise 01

#### Step 01

In the package `partA` look at the file `AgeValidity`.

#### Step 02

* Modify `AgeValidity` to implement the following:
  * Have users enter their age
  * Declare a boolean variable, drivingUnderAge
  * Initialize drivingUnderAge to false
  * Write a boolean expression to check if the age entered by the
  user is less than or equal to 18, and then set drivingUnderAge
  to true
  * Print the value of drivingUnderAge

### Exercise 02

#### Step 01

In the package `partA` look at the file `ChkOddEven`

#### Step 02

* Modify the `ChkOddEven` to implement the following:
  * Input a number between 1 and 10
  * Use if statements
  * Test whether a number is odd or even
  * The program should generate the following output:
   
  ```
  −Enter a number: 7
  −The num is odd 7

### Exercise 03

#### Step 01

In the package `partA` look at the file `AgeCheck`

#### Step 02

* Examine `AgeCheck`:
    * The program has a logic problem
    * For some values, it prints the wrong answer
    * Find the problems and fix them. (You may need to run the
      program a few times and try different values to see which
      ones fail)
    * Replace the two if statements with an if/else statement
  
### Exercise 04

#### Step 01

In the package `partA` look at the file `ShoppingCart`

#### Step 02

* Examine `ShoppingCart`:
    * Use an if/else statement to implement the following:
      * Declare and initialize a boolean variable, outOfStock
      * If quantity > 1, change the message variable to indicate plural
      * If an item is out of stock, inform the user that the item is
      unavailable, else print the message and the total

### Exercise 05

#### Step 01

In the package `partA` look at the file `StringEquality`

#### Step 02

* Examine `StringEquality`:
    * Use an if and an if/else statement:
        * Declare a String variable name
        * Have the user input a value for the name
        * Check whether the name is “Moe,” and then print “You are
          the king of rock and roll”
        * Otherwise print “You are not the king”
        * Don’t use ==
      
## Part B

### Exercise 01

#### Step 01

In the package `partB.ex01` look at the file `BooleanDemoExample` and write comments for each line of code. When complete review with instructor.

#### Step 02

In the package `partB.ex01` complete the `TempCheck` per the following:

Create a program that takes in an expected user input as an integer.

The program should compare that input and based on the result of the comparison, print out a statement:

* If input is less than or equal to 45 - "It's cold - putting on a coat!"
* If input is greater than or equal to 46 and less than or equal to 65 - "It's not bad out - a hoodie will do just fine!"
* Any other situation, - "It's hot - a Tshirt will be perfect."

Your program is working correctly, if when run, the following is the output (Abe first name Lincoln last name):

```
Enter a number from 0 to 100
66
It's hot - a T shirt will be perfect.
```

> Use BooleanDemoExample for reference.

### Exercise 02

#### Step 01

In the package `partB.ex02` look at the file `EqualityStringExample` and write comments for each line of code. When complete review with instructor.

#### Step 02

In the package `partB.ex02` complete the `EqualityOperator` per the following:

    Create a program that compares two variables (4 and 5) and returns if they're equal to each other - true of false

Your program is working correctly, if when run, the following is the output:

```
Are 4 and 4 equal? true
Are 4 and 5 equal? false
```

> Use EqualityStringExample for reference.


### Exercise 03

#### Step 01

In the package `partB.ex03` look at the file `EqualityTestExample` and write comments for each line of code. When complete review with instructor.

#### Step 02

In the package `partB.ex03` complete the `IfElseNameCheck` per the following:

* Create a program that asks the user for their first name and stores it.
* Check the name the user input against Elvis - if it Elvis, print out "You are the king of rock and roll"
* After checking the name, if the user's name is anything aside from Elvis - "You are not the king"

Your program is working correctly, if when run, the following is the output:

```
Enter your name:
Elvis
You are the king of rock and roll
```

> Use EqualityTestExample for reference.

### Exercise 04

#### Step 01

In the package `partB.ex04` look at the file `IfDemo` and write comments for each line of code. When complete review with instructor.

#### Step 02

In the package `partB.ex04` complete the `IfElseDemo` per the following:

* Create a program that takes a user input as a number
* Check the number, if it is equal to 7, the program should print to the user "That's lucky!"
* If after checking the number and it is not equal to 7, print to the user "That's unlucky!"

Your program is working correctly, if when run, the following is the output:

```
Enter a number:
5
That's unlucky!
```

> Use IfDemo for reference.


## Part C

### Activity 01: Determining color in the visible spectrum

### Overview

Write an complete `ColorRange` in package `partC.ex01`, which when given a wavelength in nanometers will return the corresponding color in the visible spectrum.

| Color | Wavelength (nm) |
| ----- | --------------- |
|Violet| 380-450|
|Blue | 450-495|
|Green| 495 - 570 |
|Yellow| 570 - 590 |
|Orange| 590 - 620 |
|Red| 620-750 |

### Task

You must implement the following using a suitable `if` statement:

* Prompt the user to enter the wavelength, the value should be of type double.
* For each range (e.g. 380 - 450) the number on the left is included in the range, but the number on the right is not included in the range.
* If the input value is not found on the visible spectrum then state the wavelength is not within the visible spectrum.

#### Expected Output 1

```
Enter a color code:
630
The Color is Red
```

#### Expected Output 2

```
Enter a color code:
25.0
The entered wavelength is not a part of the visible spectrum.
```

#### Expected Output 3

```
Enter a color code:
750.5
The entered wavelength is not a part of the visible spectrum.
```
