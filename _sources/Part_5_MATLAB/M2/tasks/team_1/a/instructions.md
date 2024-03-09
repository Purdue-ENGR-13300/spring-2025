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

## Introduction

The following task demonstrates scalar and row/column vector manipulations.
These include matrix methods and element by element methods. {program}`MATLAB`
was designed to perform matrix operations by default. All mathematical
operations involving element-wise multiplication, division, and exponentiation
of vectors requires suppression of the default matrix math. This is done using
*dot notation*, or the use of a period before the following symbols:

- Multiplication: 	`*`
- Division: 	      `/`
- Exponentiation: 	`^`


## Task Instructions

1.	Open the {program}`MATLAB` Template and fill out the header information. Then
   save the file as {glue:text}`../../../5_team_assignments.md::deliverable_ma2_team_1_m:`

2.	In the {MATLAB}`%% INTIALIZATION` section, create the following scalars and vectors: </br>

   - {MATLAB}`Ascalar = 3`

   - {MATLAB}`Arowvector = [0 1 2 3]`

   - {MATLAB}`Browvector` with four elements starting at $4$ and ending at $-2$
     with increments of $-2$. Do this by typing {MATLAB}`Browvector = 4:-2:-2`
     _NOTE: this notation {MATLAB}`start: increment value: end` allows you to
     create vectors of any size with any starting value, increment size, and
     ending value._

   - {MATLAB}`Crowvector` with three elements of your choice between $-5$ and
     $5$ inclusive.

   - {MATLAB}`Acolvector = [0; 1; 2; 3]`
      
     ```{admonition} Note
     :class: note

     This is a $4 \times 1$ column vector, which is different from
     {MATLAB}`Arowvector`. You could also create {MATLAB}`Acolvector` by
     computing the transpose of {MATLAB}`Arowvector` by typing
     {MATLAB}`Acolvector = Arowvector'`
     ```

   - {MATLAB}`Bcolvector = [-4; -3; -2; -1]
   
   3.	Open the Task 1 & 2 answer sheet ({glue:text}`../../../5_team_assignments.md::deliverable_ma2_team_pdf:`). Then compute each of the operations under the {MATLAB}`%% CALCULATIONS` section of your script. 

*% IN THE ABOVE POINT, WE NEED TO MENTION THE DOCX VERSION AND NOT THE PDF. SO, DO WE STILL HAVE TO USE GLUE? DO WE NEED TO MAKE A NEW FILE IN TEAM_ASSIGNMENTS?*

   ### Part A
   Fill in the table with the calculated output and an explanation of what {program}`MATLAB` did to get the result or why {program}`MATLAB` cannot perform the operation. 
   _NOTE: If there are any calculations that cause errors, comment it out and re-run the code._</br>
      i.	   {MATLAB}`Calc1 = Arowvector + Arowvector`</br>
      ii.	{MATLAB}`Calc2 = Arowvector + Browvector`</br>
      iii.	{MATLAB}`Calc3 = Arowvector + Ascalar`</br>
      iv.	{MATLAB}`Calc4 = Arowvector – Arowvector`</br>
      v.    {MATLAB}`Calc5 = Arowvector – Crowvector`</br>
      vi.	{MATLAB}`Calc6 = Acolvector + Bcolvector`</br>
      vii.	{MATLAB}`Calc7 = Arowvector + Bcolvector`</br>

   ### Part B
   Fill in the table with the calculated output and an explanation of what {program}`MATLAB` did to get the result or why {program}`MATLAB` cannot perform the operation. 
   _NOTE: If there are any calculations that cause errors, comment it out and re-run the code._</br>
      i.	   {MATLAB}`Calc8 = Arowvector * Browvector`</br>
      ii.	{MATLAB}`Calc9 = Arowvector .* Browvector`</br>
      iii.	{MATLAB}`Calc10 = Arowvector * Ascalar`</br>
      iv.	{MATLAB}`Calc11 = Arowvector .* Ascalar`</br>
      v.	   {MATLAB}`Calc12 = Arowvector ./ Browvector`</br>
      vi.	{MATLAB}`Calc 13 = Arowvector ^ Ascalar`</br>
      vii.	{MATLAB}`Calc14 = Arowvector .^ Ascalar`</br>

4.	Save your scripts again and submit your deliverables to Gradescope. 