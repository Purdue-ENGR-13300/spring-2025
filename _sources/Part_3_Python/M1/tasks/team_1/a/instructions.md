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

# Task 1

## Learning Objectives
Perform arithmetic operations (i.e., addition, subtraction, multiplication,
division, and exponentiation), in {program}`Python` while keeping in mind order
of operations; Employ {program}`Visual Studio Code` to write, edit, and save
{program}`Python` code; Output {program}`Python` data from script to screen.


## Task Instructions

### Part A: Introduction to the ENGR 133 Python template
Save a copy the template and rename it to
{glue:text}`../../../4_team_assignments.md::deliverable_py1_team_1_py:`.  Import the
{python}`math` module in the appropriate part of the template. Now, inside the
{python}`main()` function, add the following line of code:

```python
print(math.sqrt(4))
```

%```{code-cell} ipython3
%print(math.sqrt(4))
%```

Now run the script. The value "$2$" should have been printed to the console. If
it was not, make sure that you correctly imported the {python}`math` module and
properly indented all code inside the {python}`main()` function.  


### Part B: Calculations and variable names
For this Part, continue working in the same {program}`Python` file as for Part
A. For this task, you will be performing some calculations with
{program}`Python` and learning about proper variable naming. 

Variables associate a name with a location in your computer's memory, which
contains information for a number or string (or more complicated data type).
{program}`Python` has a few rules with regard to naming variables, which are
listed as follows: 
1.	Variable names are case-sensitive, so {python}`Cat` is not going to be the
   same variable as {python}`cat`. 
2.	Variable names must be made up of numbers, letters, and underscores
   {python}`_` 
3.	A variable name cannot start with a number. 
4.	There are some specific variable names that cannot be used as
   {program}`Python` reserves them for other uses. For example, you could not
   have a variable named {python}`def` since {python}`def` is a keyword in
   {program}`Python` that indicates that a function is being defined. Similarly,
   {python}`for` cannot be used since this is a keyword indicating the creation
   of a {python}`for` loop (which will be covered in a future {program}`Python`
   module). If you try naming a variable with one of these reserved keywords,
   {program}`Python` will indicate that you have a Syntax Error with that
   variable.    


Add the following code snippet to your script and comment out the lines that
will not work due to improper variable naming or improper syntax. Add a comment
next to that line explaining what the error was. Directly below it, rewrite that
line such that the error is now corrected. 

% We intentionally avoid syntax highlighting in the code below because some of
% it is not valid Python code.

```
a = 7
b = 4 + a
print(B)
class = b * 100 / 4
one-plus-one = 2
2_squared = 2^2 
```