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

# Pre-Class Assignments


````{admonition} Assigment Goals
:class: note

```{include} /guidelines/python.md
```

2. This assignment has one task and is worth 1 point.

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

mnum = "py1_pre"

glue("deliverable_py1_pre_1_py", mnum+"_1_username.py")
```

```{table} Deliverables
:class: deliverables
:name: tab:Py:M1:pre_class_deliverables

|    Task(s) |  Deliverables                                  |
|:----------:|:-----------------------------------------------|
|          1 | {glue:text}`deliverable_py1_pre_1_py`         |
```