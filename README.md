# Java Data Structures Challenges

A Java project focused on core data structures, algorithmic problem solving, custom collection behavior, palindrome validation, sorting logic, and decimal-to-binary conversion.

The project includes multiple Java challenges that demonstrate how data structures can be used to solve common programming problems.

## Overview

This project demonstrates Java data structure usage through focused problem-solving tasks.

The main topics include checking whether a text is a palindrome, creating a custom list structure that prevents duplicate values, sorting list elements, removing items safely, and converting decimal numbers into binary format.

The project focuses on choosing suitable data structures for different problems and implementing clean Java logic around them.

## Tech Stack

* Java
* Maven
* Collections Framework
* ArrayList
* Stack / Deque concepts
* Custom collection behavior
* String processing
* Sorting logic
* Algorithmic thinking

## Core Concepts

* Java data structures
* Palindrome checking
* String normalization
* Case-insensitive comparison
* Removing punctuation and spaces
* Custom list behavior
* Duplicate prevention
* Sorting collection elements
* Object removal logic
* Decimal-to-binary conversion
* Stack-based algorithm design

## Challenge 1: Palindrome Checker

The `checkForPalindrome()` method checks whether a given string is a palindrome.

Method:

```java
checkForPalindrome(String input)
```

The method handles cases such as:

* Uppercase and lowercase letters
* Spaces
* Punctuation marks
* Special characters such as `. , ? ! _ -`

Example inputs:

```text
I did, did I?              -> palindrome
Racecar                    -> palindrome
hello                      -> not palindrome
Was it a car or a cat I saw? -> palindrome
```

## Challenge 2: Custom WorkintechList

The `WorkintechList` class behaves like a list structure but prevents duplicate data.

Main behavior:

* Stores elements like an `ArrayList`
* Prevents duplicate values
* Sorts elements after insert/remove operations
* Supports object-based removal
* Keeps collection data organized

This challenge demonstrates how custom collection behavior can be created on top of Java collection concepts.

## Challenge 3: Decimal to Binary Conversion

The `convertDecimalToBinary()` method converts a decimal number into binary format.

Method:

```java
convertDecimalToBinary(int number)
```

Example conversions:

```text
5  -> 101
6  -> 110
13 -> 1101
```

This challenge focuses on using a suitable data structure to reverse and build the binary representation correctly.

## Features

* Palindrome validation
* String cleanup and normalization
* Case-insensitive comparison
* Custom list implementation
* Duplicate prevention logic
* Automatic sorting after operations
* Object removal from custom list
* Decimal-to-binary conversion
* Data-structure-based algorithm design
* Clean Java method structure

## Example Logic

### Palindrome Normalization

```java
String cleaned = input
        .replaceAll("[^a-zA-Z0-9]", "")
        .toLowerCase();
```

### Decimal to Binary Concept

```text
13 / 2 -> remainder 1
6  / 2 -> remainder 0
3  / 2 -> remainder 1
1  / 2 -> remainder 1

Binary result: 1101
```

## Project Structure

```text
src/
 └── main/
     └── java/
         └── org/example/
             ├── Main.java
             ├── WorkintechList.java
             └── ...
```

## What This Project Demonstrates

* Using Java collections to solve logic problems
* Choosing suitable data structures for specific tasks
* Processing and normalizing strings
* Implementing palindrome logic
* Creating custom list behavior
* Preventing duplicate values in collections
* Sorting data after collection operations
* Removing objects safely from a collection
* Converting decimal numbers into binary format
* Writing clean and reusable Java methods

## Getting Started

### Prerequisites

Make sure you have the following installed:

* Java 17+
* Maven
* IntelliJ IDEA or another Java IDE

### Installation

Clone the repository:

```bash
git clone https://github.com/emreyildirim-33/java-data-structures-challenges.git
cd java-data-structures-challenges
```

Run the project or tests from your IDE.

You can also run Maven tests with:

```bash
mvn test
```

## Notes

This project focuses on Java data structures, collection behavior, string processing, sorting logic, and algorithmic problem solving.

The main purpose is to demonstrate how data structures can be applied to common Java problems such as palindrome validation, custom list behavior, and number conversion.

## Repository

GitHub: https://github.com/emreyildirim-33/java-data-structures-challenges
