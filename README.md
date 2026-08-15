# Java Count of Digits

A simple Java program to count the number of digits in a given number.

## Author

**Shaik Bhanu**

## Repository Name

`shaikbhanu-java-count-digits`

## File Name

`CountDigits.java`

## Description

This program accepts a number from the user and counts how many digits it contains.

## Features

* Accepts a number from the user
* Counts the digits using a `while` loop
* Handles zero correctly
* Supports negative numbers

## Requirements

* Java JDK 8 or later

## How to Run

Compile the program:

```bash
javac CountDigits.java
```

Run the program:

```bash
java CountDigits
```

## Example

```text
Enter a number: 12345
Number of digits: 5
```

## Algorithm

1. Read a number from the user.
2. Convert the number to its positive value using `Math.abs()`.
3. If the number is zero, set the count to 1.
4. Otherwise, repeatedly divide the number by 10.
5. Increase the count after each division.
6. Display the total number of digits.

## Time Complexity

**O(log n)**, where `n` is the input number.

## Space Complexity

**O(1)**

## Repository Structure

```text
shaikbhanu-java-count-digits/
│
├── CountDigits.java
└── README.md
```

## License

This project is created for educational purposes.

## Author

Shaik Bhanu
