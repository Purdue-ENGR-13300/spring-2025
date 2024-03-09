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

# Task 4 [Required]

## Learning Objectives
Read and interpret a flowchart that contains user-defined functions; Design a program with user-defined functions; Understand the execution sequence for a program with user-defined functions.

## Introduction
As the scripts and programs we write become more complex, we often do not want to put all of our code directly in the {python}`main` function. {program}`Python` allows users to easily write their own functions in order to modularize their programs; these are called user-defined functions.

## Task Instructions
### Part A 
Your team is designing an electric vehicle that will be charged by a wind turbine. You want to write a program that gives a rough estimate for how far the vehicle can travel after a given amount of charging time. On the next page is a flowchart for that program. Find the output of the program given the following initial conditions:

```{table} Cases for M05 team task 4
:class: cases
:name: tab:M05:team_cases

| $\rho$ (${\kilo\gram}/{\meter^3}$) | A (${\meter^2}$) | $C_p$ | v (${\meter}/{\second}$)| t ($\text{hour}$) | $\epsilon_v$ | 
|:----------------------------------:|:----------------:|:-----:|:-----------------------:|:----------:|:-------------|
|                                1.2 |              400 |   0.3 |                       6 |          1 |        0.007 |
|                                1.2 |             2500 |   0.3 |                       4 |          5 |        0.007 |
```

The power of the wind turbine is given by:

```{math}
:name: eq:py1:power

P =  \frac{1}{2} \rho A v^3 C_p
```

Where 
- $P$ is the power
- $\rho$ is the air density
- $A$ is the rotor swept area
- $v$ is the wind velocity
- $C_p$ is a coefficient of efficiency

The energy in the car is given by:

```{math}
:name: eq:py1:energy

E = Pt
```

Where
- E is the energy
- P is the power
- t is the time

The distance that an electric vehicle can travel is given by:
```{math}
:name: eq:py1:distance

d = E\epsilon_v
```

Where
- d is the distance
- E is the energy
- $\epsilon_v$ is the vehicle efficiency

```{figure} flowchart.png

Flowchart for Team Task 4A
```

### Part B
An advertising company would like a program that allows them to compare the unit cost of various circular signs that they make. Create a flowchart for a program where the user can input the diameter (in inches) and price (in dollars) of a sign and the output will display the unit cost (dollars per square inch) of the sign. Your program should include a {python}`main` function, a function to calculate the area, and a function to calculate the unit price.