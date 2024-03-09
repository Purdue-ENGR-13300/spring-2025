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

(mod:py1_ind_task_1)=
# Task 1

## Learning Objectives 

Create and execute simple scripts comprised of basic {program}`Python` concepts;
Apply course code standard in development of {program}`Python` scripts;
Modularize and comment code in {program}`Python` for readability and
reusability.
 
## Task Instructions

In this task, you will be doing calculations using both {program}`Python` and
{program}`MS Excel`. By performing the calculations with both tools, you will
gain insight into the differences in syntax between the two

(mod:py1_ind_task_1_part_a)=
### Part A

1. Open an {program}`MS Word` document and create a table with four columns with
   headings as shown on the next page. 

2. Open an {program}`MS Excel` sheet. 

3. Assuming problems 1-5 shown on the next page are computed sequentially in the
   order shown, calculate in {program}`MS Excel` the result of each expression. 

4. Perform these calculations in a {program}`Python` script and use the same
   variable names as in the equation. 

5. In your {program}`Python` script, make sure to print out the resulting
   calculation for each problem so that you can fill in the table for Step 6. 

6. Fill in the table, using 4 decimal places when necessary.

   ```{admonition} Note
   :class: note

   You should get the same values for each expression in both {program}`MS
   Excel` and {program}`Python`
   ```

7. Repeat steps 4-6 for problems 6-10. Treat the values you computed in problems
   1-5 as a data set that you are performing these operations on (i.e. put the
   results from problems 1-5 in the same row/column in {program}`MS Excel`, and
   put them in a list in {program}`Python`). 

8. Save your {program}`MS Excel` sheet as a PDF with the formulas visible with
   the name {glue:text}`../../../5_ind_assignments.md::deliverable_py1_ind_1_excel_pdf:`.

9. Save your {program}`Python` script as
   {glue:text}`../../../5_ind_assignments.md::deliverable_py1_ind_1_py:`.


```{admonition} Hint
:class: hint

Remember the order of operations. You will need to import the math and
statistics modules to do some of the calculations in {program}`Python`. 
```


```{table} Equations in MS Excel and Python
:name: tab:py1:eqns

|  Problem Number |  Equation | {program}`MS Excel` Calculations | {program}`Python` Calculations |
|:---------------:|:---------:|--------------------|---------------------|
| 1 | $a = 5$                   | | |
| 2 | $b = a^{1/3}$             | | |
| 3 | $c = \sin(\sqrt{b})$      | | |
| 4 | $d = \text{int}(90.5)$    | | |
| 5 | $e = 254 \text{ mod } 66$ | | |
```

Consider the values of $a$, $b$, $c$, $d$, and $e$ computed above to be a data set, and
use them to answer questions 6-10 in the table below. Use built-in or imported
functions for each calculation. Round to four decimal places where necessary.
(Hint: In {program}`Python`, create a list that contains these values.)

```{table} Calculations in MS Excel and Python
:name: tab:py1:cals

|  Problem Number |  Calculation | {program}`MS Excel` Calculations | {program}`Python` Calculations |
|:---------------:|:---------:|--------------------|---------------------|
|  6 | Find the mean               |||
|  7 | Find the median             |||
|  8 | Find the maximum            |||
|  9 | Find the range              |||
| 10 | Find the standard deviation |||
```


### Part B

Answer the following questions and include the answers in your previously
created {program}`MS Word` document: 

1. What differences did you notice between the {program}`MS Excel` calculations
   and the {program}`Python` calculations? 

   a. You can add a fifth column with the heading – "Differences" to the table
      from {ref}`mod:py1_ind_task_1_part_a` to answer this question.  

2. What {program}`Python` function did you use to output these variables to the screen? Did
   you have to use an imported library in {program}`Python`, or was the function built into
the standard library? 

3. What syntax differences exist between {program}`Python` and {program}`MS
   Excel`? Be specific. 
 
Save the {program}`MS Word` document as a PDF with the name
{glue:text}`../../../5_ind_assignments.md::deliverable_py1_ind_1_word_pdf:`.