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

# Individual Assignments

% TODO add MATLAB guidelines
````{admonition} Assigment Goals
:class: note

```{include} /guidelines/matlab.md
```
```{include} /guidelines/individual_task_points.md
```
```{include} /guidelines/common_steps.md
```

````

**Notes Before You Start**


```{include} /guidelines/gradescope.md
```

```{include} /guidelines/individual.md
```

```{code-cell} ipython3
:tags: ["remove-cell"]

from myst_nb import glue

mnum = "ma2_ind"

glue("deliverable_ma2_ind_1_m", mnum+"_1_username.m")
glue("deliverable_ma2_ind_1_pdf", mnum+"_1_username.pdf")
glue("deliverable_ma2_ind_2_m", mnum+"_2_username.m")
glue("deliverable_ma2_ind_2_pdf", mnum+"_2_username.pdf")
```

```{table} Deliverables
:class: deliverables
:name: tab:M10:individual_deliverables

|    Task(s) |  Deliverables                          |
|:----------:|:---------------------------------------|
|          1 | {glue:text}`deliverable_ma2_ind_1_m`   |
|          1 | {glue:text}`deliverable_ma2_ind_1_pdf` |
|          2 | {glue:text}`deliverable_ma2_ind_2_m`   |
|          2 | {glue:text}`deliverable_ma2_ind_2_pdf` |

```