# sim-C Docs

## What is sim-C?

<p align="justify">Often people have trouble programming in C (especially beginners) due to its low level syntax and availability of stable third party libraries. We present sim-C a high-level front end for C which creates a dynamically typed syntax for C. User can write code in this high level syntax and then compile it to optimized C code. sim-C does not process the code and simply translates it to C thus, there is no possibility of the code running slowly. So, with sim-C users can write code faster using the high level syntax and at the same time be able to harness the power and speed of a C program. Let us make C cool again.</p>

## Pipeline

<p align="center">
  <img src="./simc-pipeline.png">
</p>


## Execution



## Syntax

<details>

  <summary><b>Operators</b></summary>

### Arithmetic operators

  1) Addition operator (+):-

  ```console
  1 + 2
  ```
  <b>Result => 1 + 2</b>

  2) Subtraction operator (-):-

  ```console
  1 - 2
  ```
  <b>Result => 1 - 2</b>

  3) Multiplication operator (*):-

  ```console
  1 * 2
  ```
  <b>Result => 1 * 2</b>

  4) Division operator (/):-

  ```console
  1 / 2
  ```
  <b>Result => 1 / 2</b>

  5) Modulo operator (%):-

  ```console
  1 % 2
  ```
  <b>Result => 1 % 2</b>

  ### Relational operator

  1) Less than (<):-

  ```console
  1 < 2
  ```
  <b>Result => 1 < 2</b>

  2) Greater than (>):-

  ```console
  1 > 2
  ```
  <b>Result => 1 > 2</b>

  3) Equal to (==):-
  ```console
  1 == 2
  ```
  <b>Result => 1 == 2</b>

  4) Less than equal to (<=):-
  ```console
  1 <= 2
  ```
  <b>Result => 1 <= 2</b>

  5) Greater than equal to (>=):-
  ```console
  1 >= 2
  ```
  <b>Result => 1 >= 2</b>

  6) Not equal to (!=):-
  ```console
  1 != 2
  ```
  <b>Result => 1 != 2</b>

  ### Assignment operator

  ```console
  a = 1
  ```
  <b>Result => a = 2</b>

</details>

<hr />

<details>

  <summary><b>Variables</b></summary>

  ### Declaring a variable

  ```console
  var a
  ```
  <b>Note: Here a is name of variable.</b>
  <b>Result => var a</b>

  ### Initializing a variable

  ```console
  var a = 2
  ```
  <b>Note: Here a is name of variable and it gets a value of 2.</b>
  <b>Result => int a = 2</b>

  ### Assigning value to a variable

  ```console
  a = 3
  ```
  <b>Note: Here a is name of variable, we also assume here that a is declared earler in the code.</b>
  <b>Result => a = 3</b>

</details>

<hr />

<details>

  <summary><b>Strings</b></summary>

  ### Initializing a string variable

  ```console
  var a = "Hello"
  ```
  <b>Note: Strings should be enclosed within double quotes (" ").</b>
  <b>Result => char* a = "Hello"</b>

</details>

<hr />

<details>

  <summary><b>Print statement</b></summary>

  ### Syntax of print statement

  ```console
  print("Hello World")
  ```

  <b>Result => printf("Hello World")</b>

</details>

<hr />