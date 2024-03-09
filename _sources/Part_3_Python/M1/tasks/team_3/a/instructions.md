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


# Task 3 [Required] - Autograded


## Learning Objectives 

Perform arithmetic operations in {program}`Python` (i.e., addition, subtraction,
multiplication, division, and exponentiation), while keeping in mind order of
operations; Employ the {program}`VS Code` IDE to write, edit, and save
{program}`Python` code; Output {program}`Python` data from script to screen; use
various built-in and imported functions; import modules into script; Writing
scripts to enable auto grader.


## Introduction

As you know, in this class we use {program}`Gradescope` for assignment
submission and grading. One feature of {program}`Gradescope` is that it has a
{program}`Python` auto grader, which allows for the near-instant grading of
{program}`Python` scripts you submit. This is advantageous, as it allows you to
submit your script to {program}`Gradescope` as many times as you want until you
receive full marks. This will help you learn from your mistakes. Note that while
not all {program}`Python` tasks will be auto graded, but there will always be at
least one which is. 

In this task, you will be using specific variable names and creating print
statements using {python}`f` strings that should have a specific format that the
auto grader expects to calculate the area and perimeter of a rectangle and
output information about it to the screen.

The auto grader will be checking the values assigned to each variable (hence the
importance to use the exact variable names when writing your script) as well as
the output of your print statement. The rubric items for this problem will be
written such that you will be told where you have errors, if any.


## Task Instructions

Make a flow chart in your previously created PDF document and then open the
template and rename it
{glue:text}`../../../4_team_assignments.md::deliverable_py1_team_3_py:`. Create
a variable named {python}`width` which is equal to $7.2$. Create another
variable called {python}`height` which is equal to $3.1$. Now, create a variable
called {python}`area` which calculates the area of the rectangle and a variable
called {python}`perimeter` which calculates the perimeter of the rectangle.

Next, use an {python}`f` string in a print statement to output the following
information. Note that the area and perimeter measurements should be rounded to
$1$ decimal place.

% Automatically generated of Sample Output section.
```{include} /_build/intermediate/Part_3_Python/M1/tasks/team_3/a/sample_output.md
```

Once you’ve completed the rest of the team tasks, you can submit everything to
the Py1 Team submission drop-link in {program}`Gradescope` and see if you
received full marks. If not, make the requisite changes and submit again until
you have completed it correctly.