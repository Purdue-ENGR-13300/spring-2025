---
jupytext:
  text_representation:
    extension: .md
    format_name: myst
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---
```{include} /macros.md
```

# Task 3 [Required]

## Introduction

Computers use binary for all calculations. It is important to be able to track
binary operations to understand how the computer operates. One way to represent
a binary calculator is with an **XOR** and **AND** gate as shown in the
{numref}`M10:fig:xor_truth_table`.  When adding two single digit binary numbers,
the sum represents the first digit, and the carry represents the second digit.
So, if we added $1 + 1$ in binary we would get $1$ $0$, where $0$ is in the
sum column and the carry is $1$.  

Reference:  https://www.electronics-tutorials.ws/combination/comb_7.html

```{figure} xor.png
:name: M10:fig:xor_truth_table

XOR logic gate symbol and truth table
```

## Task Instructions
1. Open the {program}`MATLAB` Template and fill out the header information. Then
   save the file as {glue:text}`../../../5_team_assignments.md::deliverable_ma2_team_3_m:`

2. In the script, write a {program}`MATLAB` program that:

   1. Uses the input command in {program}`MATLAB` to prompt the user to enter a
      binary number of 1 or 0.  _Remember that the input command in
      {program}`MATLAB` yields a number rather than a string like in
      {program}`Python`._ 

   2.	Checks if the number that the user inputs is anything other than $1$ or
      $0$ and prints an error statement if it is not $0$ or $1$.

   3.	Prompts the user for a second binary number of $1$ or $0$. 

   4.	Checks if the second number that the user inputs is anything other than
      $1$ or $0$ and prints an error statement if it is not $0$ or $1$.

   5.	If the user enters a $1$ or $0$ for each input, calculate the result of
      the binary addition (use the chart above). 

   6.	Prints a line that shows {matlab}`Binary sum = ##` where the
      {matlab}`##`’s are the digits of the binary addition. 

3.	Save your script and upload all deliverables to Gradescope. 
