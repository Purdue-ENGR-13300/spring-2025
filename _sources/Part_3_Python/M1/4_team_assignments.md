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

# Team Assignments

````{admonition} Assigment Goals
:class: note

```{include} /guidelines/python.md
```

2. This assignment has five tasks and is worth 5 points. **Complete tasks 3 and
   4 to earn 4 points.  Complete two of the remaining tasks to earn 1 additional
   point.**

```{include} /guidelines/common_steps.md
```

````

**Notes Before You Start**


```{include} /guidelines/gradescope.md
```

```{include} /guidelines/team.md
```

```{code-cell} ipython3
:tags: ["remove-cell"]

from myst_nb import glue

mnum = "py1_team"

glue("deliverable_py1_team_1_py", mnum+"_1_teamnumber.py")
glue("deliverable_py1_team_2_py", mnum+"_2_teamnumber.py")
glue("deliverable_py1_team_2_part_a_pdf", mnum+"_2_part_a_teamnumber.pdf")
glue("deliverable_py1_team_3_py", mnum+"_3_teamnumber.py")
glue("deliverable_py1_team_5_py", mnum+"_5_teamnumber.py")
glue("deliverable_py1_team_pdf", mnum+"_teamnumber.pdf")
```

```{table} Deliverables
:class: deliverables
:name: tab:Py:M1:team_deliverables

|    Task(s) |  Deliverables                                  |
|:----------:|:-----------------------------------------------|
|          1 | {glue:text}`deliverable_py1_team_1_py`         |
|          2 | {glue:text}`deliverable_py1_team_2_py`         |
|          2 | {glue:text}`deliverable_py1_team_2_part_a_pdf` |
|          3 | {glue:text}`deliverable_py1_team_3_py`         |
|          5 | {glue:text}`deliverable_py1_team_5_py`         |
| 2, 3, 4, 5 | {glue:text}`deliverable_py1_team_pdf`          |
```