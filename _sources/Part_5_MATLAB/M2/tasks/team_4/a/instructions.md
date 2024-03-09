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

# Task 4

## Introduction 

Recall from {program}`Python` 3 that a Maclaurin series is an $n^\text{th}$
degree polynomial that can be used to approximate a function around $x = 0$.
The exponential function, $e^x$, can be approximated as follows: 

```{math}
e^x
= \sum_{n=0}^\infty \frac{x^n}{n!}
= 1 + x + \frac{x^2}{2!} + \frac{x^3}{3!} + \cdots
```

Where the infinite series approximation converges with the actual function over
all real numbers.  Practically, for a finite approximation, the fewer terms that
are used, the less accurate the approximation will be, particularly as $x$ gets
further from $0$.  


## Part A

1. Open the {program}`MATLAB` Template and fill out the header information. Then
   save the file as {glue:text}`../../../5_team_assignments.md::deliverable_ma2_team_4a_m:`.

2. Using the factorial function in {program}`MATLAB`, write a program that uses
   the Maclaurin series (above) to approximate $e^x$ with specific values of $n$
   and $x$. The program will need to ask the user to input $n$ and $x$ (in this
   order).  The program should also display the percent error of the error value
   with respect to a calculation of the actual value. See the example output in
   {ref}`mod:part_5_matlab_m2_team_4_a_a_sample_output` below.

```{admonition} Note
:class: note

You may want to revisit your flowchart created in the {program}`Python` 3
assignment and make notes of changes that need to be made for {program}`MATLAB`.
You do not have to turn in a flowchart for this task. 
```

% Automatically generated of Sample Output section.
```{include} /_build/intermediate/Part_5_MATLAB/M2/tasks/team_4/a/a_sample_output.md
```


## Part B

1. Open the {program}`MATLAB` Template again and fill out the header
   information. Then save the file as
   {glue:text}`../../../5_team_assignments.md::deliverable_ma2_team_4b_m:`.


2. Write a program that will generate as many terms as necessary to approximate
   the function to a specified level of accuracy (below a percent error
   threshold) at a specified value of $x$. The program will need to ask the user
   to input $x$ and the target error threshold (in this order). The program
   should also display the number of terms the series must contain before the
   target accuracy is achieved. See the example output in
   {ref}`mod:part_5_matlab_m2_team_4_a_b_sample_output` below.
   
```{admonition} Note
:class: note

You may want to revisit your flowchart created in the Python 3 assignment and
make notes of changes that need to be made for {program}`MATLAB`. You do not
have to turn in a flowchart for this task. 
```

% Automatically generated of Sample Output section.
```{include} /_build/intermediate/Part_5_MATLAB/M2/tasks/team_4/a/b_sample_output.md
```