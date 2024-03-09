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

# Task 0


## Learning Objectives

Perform arithmetic operations (i.e., addition, subtraction, multiplication,
division, and exponentiation), in {program}`Python` while keeping in mind order
of operations; Employ {program}`Visual Studio Code` to write, edit, and save
{program}`Python` code; Output {program}`Python` data from script to screen.


## Introduction

{program}`Python 3` is a powerful programming language for performing
computations, scripting, and database management. As an engineering tool, it
offers standard mathematical operations as part of its basic environment.
Therefore, you can design standard computational models, process data, and
generate reports. The language must work within the limits of the machine it is
running on. As a result, there may be differences between what you compute by
hand and what {program}`Python` computes.

Unless mentioned otherwise, for all {program}`Python` tasks (pre-class, team and
individual) you will be writing your scripts using
{file}`ENGR133_Python_template.py`. This template contains header information
that must always be edited to reflect the task your Python file is meant to
solve, and you will always be prompted in the problem statement to rename the
file. 

The template contains a section for importing modules, and a function called
{python}`main()` where you will be writing your code. While user-defined
functions will be taught in more detail in the next {program}`Python` module,
for now you will just need to remember to write all your code within that
function. Note that, when writing code inside a function, it must be indented 1
tab (or 4 spaces) relative to the indentation level of the function.  


## Task Instructions

Before beginning this activity, completely watch the pre-class videos and take
the pre-class quizzes. Additionally, do some research into some common
{program}`Python` libraries (i.e. the
[`math`](https://docs.python.org/3/library/math.html) library will be helpful
for this assignment). There are many functions within the `math` library in
particular that will be needed for this task. It is important for your learning
and ability to contribute to future assignments that you understand the covered
topics.  In this task, you will be doing calculations in {program}`Python`.

1. Make a copy of the {file}`ENGR133_Python_Template.py` {program}`Python`
   template and rename the file to
   {glue:text}`../../../3_pre-class_material.md::deliverable_py1_pre_1_py:`.

2. Make sure to fill out all header information, including a short description
   of the code.

3. Include all needed import statements in the labeled section of the template.

   ```{admonition} Hint
   :class: hint dropdown
   
   The {python}`math` module may be useful.
   ```

4. In your main script, initialize three variables `a`, `b`, and `c` ($5$, $9$,
   and $2$) that can be used in the calculations.

5. Create three variables that compute the following three equations in
   {program}`Python` using appropriate syntax and function calls where needed.
   Be careful with order of operations.

      1. {math}`a * b^2 + \sin(c)`
      2. {math}`\frac{\pi}{c} - b!`
      3. {math}`b^3 + \frac{c}{4} + \sin^{-1}{(1)}`

6. After each calculation, print the output to the command window rounded to
   three decimal places.  Research
   [f-strings](https://docs.python.org/3/reference/lexical_analysis.html#formatted-string-literals)
   and the [format specification
   mini-language](https://docs.python.org/3/library/string.html#format-specification-mini-language)
   to learn how to round to three decimal places.

   ```{admonition} Hint
   :class: hint dropdown
   
   Do not use the {python}`round()` function.
   ```

7. Save the file as 
   {glue:text}`../../../3_pre-class_material.md::deliverable_py1_pre_1_py:` and
   turn in the assignment on Gradescope.

% Automatically generated of Sample Output section.
```{include} /_build/intermediate/Part_3_Python/M1/tasks/pre_0/a/sample_output.md
```