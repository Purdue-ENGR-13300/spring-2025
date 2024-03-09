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

(mod:ma2_ind_task_1)=
# Task 1


## Introduction

Cylindrical steel tanks have many outdoor uses. They are used in oil and gas
refining, food production, farming, liquified gas storage, and more. Cylindrical
tanks can have flat end caps, elliptical end caps, or spherical end caps. Your
company uses cylindrical tanks with flat end caps (see figure). 
You are working on a design for a tank fill measurement system that can be used in tanks
that are installed horizontally. The tank you are working with is an outdoor
storage container and will be used to store water. The tank has liquid measuring
sensors along its height, which alert an operator once the liquid has reached
the height of a particular sensor. From these height measurements, the volume of
the tank can be calculated. The cylindrical tank has radius r and length L. As
the sensors are inside the tank, all measurements are internal measurements, so
the tank wall thickness is not relevant nor required for this application. When
a cylindrical tank with flat ends is installed horizontally, the fluid volume at
any fluid height within the tank can be calculated using the function

```{math}
:name: eq:ma2:fluid volume

V_f = L \left( \cos^{-1} \left(\frac{r-h}{r}\right) r^2 - (r-h) \sqrt{2rh - h^2} \right)
```

Where
- $V_f$ is the fluid volume
- $h$is the fluid height measured from the tank bottom
- $r$ is the tank radius
- $L$ is the length of cylindrical section of the tank

```{figure} cylindrical_tank.png

A model of a horizontal cylindrical tank
```

The client you are working for wants to be alerted when the volume in the tank
is less than 20% of the maximum volume. The fluid height is not measured
instantaneously in this system. As the tank is progressively emptied, sensors
are tripped, indicating that the fluid has reached the height of a particular
sensor. 


## Task Instructions

1.	Open the {program}`MATLAB` Template and fill out the header in formation.
   Then save the file as
   {glue:text}`../../../6_ind_assignments.md::deliverable_ma2_ind_1_m:`

2.	Write a script that follows the flowchart below to simulate the tank emptying
   process and meet the safety needs of the system. The script will need a fluid
   height vector with decreasing increments of $0.1m$ and to step through the
   vector while calculating the volume at every height, triggering an alert just
   after the fluid has fallen below $20%$ of the maximum volume. 

   ```{figure} flowchart.png

   Flowchart for MA2 Individual Task 1
   ```

   a.	In the {MATLAB}`%% INITIALIZATION`section, define the testing values as variables:
      i.	   The tank has an inner radius of $1.25m$, an inner length of $5.5m$. 
      ii.	Assume the tank starts off completely full when the emptying begins. 
      iii.	The tank has sensors placed every $0.1m$ in height along the tank. 
      iv.	The client wants to know when the volume of the tank falls below $20%$ capacity. 

   b.	In the {MATLAB}`%% CALCULATIONS` section: 
      i.	   Calculate the maximum tank volume. _To make sure that you’ve coded the equation correctly, use the variables initialized above to find a volume {math}`V_f = 26.9981m^3`._ 
      ii.	Calculate the tank fill capacity that will trigger an alert. 
      iii.	Create a vector of fluid height values and a vector of corresponding volumes using a while loop. 
      iv.	Stop adding elements to the vector as close as possible to the fill capacity, just going below it. 

   c. In the {MATLAB}`%% OUTPUTS` section, display the number of iterations to
      fall below $20%$ capacity, final fluid height, final fluid volume, and a
      warning that the volume is too low in a well-formatted print statements.

3.	Publish your script as
   {glue:text}`../../../6_ind_assignments.md::deliverable_ma2_ind_1_pdf:` and
   submit your deliverables to Gradescope.

4.	Expected Output:

   ```
   Number of iterations = 19
   Remaining volume = 4.98 m^3
   Fluid height= 0.60 m
   WARNING: The tank is now below 20% capacity. Please refill.
   ```

% Automatically generated of Sample Output section.
```{include} /_build/intermediate/Part_5_MATLAB/M2/tasks/ind_1/a/sample_output.md
```