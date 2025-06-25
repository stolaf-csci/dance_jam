<a href="https://colab.research.google.com/github/chefs-kiss/cs1_spring2025/blob/main/2_variables.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

# Warm-up

Finish flowchart and print exercises from algorithms workbook


# Discussion: Apple Orchards and Operators

Diana is writing a program to help an apple orchard. She knows that the orchard gathered in total **42** apples this week, and then sold them in bags of **5**. She adds some calculations to her program that she thinks would be helpful for the orchard.

1. 42 / 5 = 8.4		    
2. 42 // 5 = __
3. 42 % 5 = __



We've figured out that:
1. 42 / 5 = 8.4, which is how many bags of apples there are in total.

What is Diana calculating when she uses the // and % operators, and what is the context of that operator in terms of apples or bags of apples?




# Casting example

The following code accompanies the casting section we see in the slide deck


```python
print("float(5) =", float(5))
print("int(3.14) =", int(3.14))
print("int(3.9) =", int(3.9))
print("int(7/4) =", int(7/4))
print("float(7//4) =", float(7//4))
```

    float(5) = 5.0
    int(3.14) = 3
    int(3.9) = 3
    int(7/4) = 1
    float(7//4) = 1.0




---


# Discussion: Predict the Output

Use the order of precedence for operators to find the following values:
1. `(1+2)**3`
2. `4 + 3 / 8`
3. `int((4+3)/2)`
4. `float(19//5)`
5. `3*(1//3)`
6. `1/3`
7. `1.2 - 1`

Initial guesses:

1.

2.

3.

4.

5.

6.

7.

Once you have a guess, try evaluating a few in the code chunk below:


```python

```

# Enter a Number example

The following code accompanies the input + printing section we see in the slide deck


```python
number = int(input("Enter a whole number: "))
squared = number ** 2
print("The square of", str(number), "is", str(squared))
```

    Enter a whole number: 2
    The square of 2 is 4



```python
print(f"The square of {number} is {squared}")
```

    The square of 2 is 4


---


# Concept Checks

These are meant to test (very informally) how the concepts stuck during the lecture. Chat about each question with a partner without looking back at the material. After chatting, beef up your initial answers by revisiting the notes or textbook.





## Namespace and Objectspace

Using at the code below, fill in the rest of the following (double-click to edit):

namespace --> objectspace

1. a --> 4

2. __ --> __

3. __ --> __


```python
a = 4
b = a + a
a = b *4
```

To check your work, add a print statement to see the final value of `a`

## Variable Types and Naming


First, add (ok) after any variables which are valid variable names.

Secondly, for the valid variable names do the following:

Bold any of the following variable names which follow good naming conventions.

Italize any names which are not meaningful.


1. Pipp1n
2. PIPPIN!
3. _2hobbit4u
4. pippinTook
5. 1ring2rule
6. pip_the_hobbit
7. PIPPIN$$
8. p

Write a brief reason for variables you made bold or italic.

---
# Exercises

It may be helpful to draw out your program. Feel free to grab a sheet of paper, or grab a whiteboard marker and draw on the walls (they're whiteboards!)

## Temperature Conversion Program

We want a program that will convert temperatures from **C** to **F**. The steps for doing this are:
1. Use the input function to get the temperature in **C** from the user, and store it in as a float in an appropriately named variable.
2. Convert the **C** temperature to its **F** equivalent. The formula to convert C to F is: **9/5 C + 32**.
3. Use print to provide the user with a message that tells them the temperature in C (that they provided) and what its equivalent temperature is in F.


An example of running your program will produce the following first line for the user input (user enters 0) and the second line as the output:

`What is the temperature in C: 0`

`0C is 32F.`


Once you have a program that works, try to make it more efficient by using only one variable and only two lines of code.


```python
#your code here



```

## The Year You Turn 100

Write a program that prompts the user to enter their age and the current year. It then displays the year they will turn 100.

An example of executing this program is given below:

`What is your age? 30`

`What year is it? 2024`

`You will turn 100 in the year 2094`


```python
#your code here
```
