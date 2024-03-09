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

# Task 2


## Introduction

This task is designed for students to compare vectors and arrays using
relational operators in {program}`MATLAB`. In addition, they will apply {MATLAB}`any`, {MATLAB}`all`, and {MATLAB}`find`
functions in {program}`MATLAB`.  


## Task Instructions

1. Open the {program}`MATLAB` Template and fill out the header information. Then
   save the file as
   {glue:text}`../../../5_team_assignments.md::deliverable_ma2_team_2_m:`

2.	In the {MATLAB}`%% INTIALIZATION` section, create the following vectors and arrays: </br>
    • {MATLAB}`Cvector = [1, 2];`</br>
    •	{MATLAB}`Aarray = [1, 2; 3, 4];`</br>
    •	{MATLAB}`Barray = [1, 0; -1, 4];`</br>
    •	{MATLAB}`Carray = [1, 2; 3, 4; 5, 6];`</br>
    •	{MATLAB}`Darray = [0, 0, 1; 3, 5, -5; 1, 0, 1];`</br>


3. Open the Task 1 & 2 Answer Sheet
   ({glue:text}`../../../5_team_assignments.md::deliverable_ma2_team_pdf:`). Then
   compute each of the operations under the {MATLAB}`%% CALCULATIONS` section of
   your script. 

*% IN THE ABOVE POINT, WE NEED TO MENTION THE DOCX VERSION AND NOT THE PDF. SO, DO WE STILL HAVE TO USE GLUE? DO WE NEED TO MAKE A NEW FILE IN TEAM_ASSIGNMENTS?*

   ### Part A
   Fill in the table with the calculated output and an explanation of what {program}`MATLAB` did to get the result or why {program}`MATLAB` cannot perform the operation. </br>
   _NOTE: If there are any calculations that cause errors, comment it out and re-run the code._</br>
    i.	  {MATLAB}`Ans_A = Aarray >= Barray`</br>
    ii.	  {MATLAB}`Ans_B = Aarray .* Barray ~= 1`</br>
    iii.	{MATLAB}`Ans_C = Barray < (Aarray – Ans_B) <= (Ans_B < 1) * 3`</br>
    iv.	  {MATLAB}`Ans_D = Barray > Carray`</br>
    v.	  {MATLAB}`Ans_E = [Barray; Cvector] == Carray`</br>


   ### Part B
   Fill in the table with the calculated output and an explanation of what {program}`MATLAB` did to get the result or why {program}`MATLAB` cannot perform the operation. </br>
   _NOTE: If there are any calculations that cause errors, comment it out and re-run the code._</br>
    i.	  {MATLAB}`Ans_F = any(Aarray) + any(Barray)`</br>
    ii.	  {MATLAB}`Ans_G = all(Aarray) + all(Barray)`</br>
    iii.	{MATLAB}`Ans_H = all(Carray > 1)`</br>
    iv.	  {MATLAB}`Ans_I = all(any(Barray < -1))+any(all(Darray))`</br>
    v.	  {MATLAB}`Ans_J = find(Barray).^(find(Carray > 5))`</br>
    vi.	  {MATLAB}`Ans_K = find(any(Darray == 1))`</br>

4.	Save your scripts again and submit your deliverables to Gradescope. 
