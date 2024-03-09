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

# Task 5 [Required]

## Introduction
 
The following exercises are to be worked on as a team. Each exercise has a
sample of Python code. Your goal is to rewrite each sample in {program}`MATLAB`. Each
exercise should be in its own {MATLAB}`.m` file.

## Exercise A

*Previous Python Code*

```
x = ***
y = ***
if x<=50:
    z=4
    if y<30:
        z=x*y
    elif y>=100:
        z=x+y
    
elif y >= 60:
    if x > 80:
        z=x
    elif y > 50:
        z=y
else:
    z=z*2

print('z=', z)
```

*Expected Output:* </br>
_NOTE: replace the *** for x and y in the Python code to run each case separately. Clear the variables in the workspace for this to run accurately each time._

```{table} Expected Output
:class: expected_output
:name: tab:M10:exercise A expected output

| x  | y  | Output                                      |
|:--:|:--:|:--------------------------------------------|
| 40 | 40 | z=4                                         | 
| 20 | 20 | z=400                                       | 
| 55 | 20 | Error:Unrecognised function or variable 'z' |   
```

## Exercise B

*Previous Python Code*
```
i=1
x=3
y=6
while i<10:
    for z in [x,y]:
        i+=z
    if x<3:
        x+=1
print(i)
```

*Expected Output:* 
```
10
```

## Exercise C

*Previous Python Code*

```
x= [3,6,-2,1]
y=0

for index in x:
    if index <= 3: 
        y=y+index
    print(f'y={y}')
```

*Expected Output:*
```
y = 3
y = 3
y = 1
y = 2
```

Save your scripts for each exercise and upload all deliverables to Gradescope. 

