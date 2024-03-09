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

# Task 5 

## Learning Objectives  

Create and execute simple scripts comprised of basic {program}`Python` concepts;
Describe the characteristic and purpose of modules in {program}`Python`; Import
modules in {program}`Python` (i.e. `math` module); Employ the {program}`VS Code`
IDE to write, edit, and save {program}`Python` code; Output data from a script
to the screen in {program}`Python`; Apply course code standard in development of
{program}`Python` scripts. 

 
## Introduction
 
Modules are a simple way to structure a program. There are standard modules in
the standard library and there can be other {program}`Python` files, or
directories containing {program}`Python` files, in the current directory (each
of which constitutes a module). Standard modules in {program}`Python` must be
imported before use. 


## Task Instructions 

Make a flow chart in your previously created PDF document and then open the
template and rename it
{glue:text}`../../../4_team_assignments.md::deliverable_py1_team_5_py:`. Write a script
that computes the volume of a regular prism (a prism whose base is a regular
polygon) with $3$-$10$ sides. Each side has a side length of
$\qty{10}{\centi\meter}$, and the prism has a height of
$\qty{15}{\centi\meter}$.  Ask the user to enter the number of sides that the
regular polygon has (for example, $3$ sides would result in the solid having a
triangular base, and $6$ sides would result in the solid having a hexagonal
base). Be sure to cast the returned string from the {python}`input()` function
to an {python}`int`.   

You can use the following formula to calculate the volume of a prism: 

```{math}
:name: eq:py1:vol

V = A_b h
```

```{math}
:name: eq:py1:area
 
A_b = \frac{n s^2}{4 \tan(\frac{\pi}{n})}
```
 
Where 

- $A_b$ is the area of the base of the prism, in this case, the area of the
  regular polygon chosen by the user 

- $h$ is the height of the prism 

- $n$ is the number of sides that the regular polygon has 

- $s$ is the length of one side 

- $V$ is the volume of the solid 

Format your output to match the sample below.

```{admonition} Hint
:class: hint dropdown

The $\tan$ function in {program}`Python` returns the tangent of $x$ assuming $x$
is in radians. 
```

% Automatically generated of Sample Output section.
```{include} /_build/intermediate/Part_3_Python/M1/tasks/team_5/a/sample_output.md
```