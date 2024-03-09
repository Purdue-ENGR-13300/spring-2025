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

(individual)=
# Individual Assignments

````{admonition} Assigment Goals
:class: note

```{include} /guidelines/python.md
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

mnum = "py1_ind"

glue("deliverable_py1_ind_1_word_pdf", mnum+"_1_username.pdf")
glue("deliverable_py1_ind_1_excel_pdf", mnum+"_1_excel_username.pdf")
glue("deliverable_py1_ind_1_py", mnum+"_1_username.py")
glue("deliverable_py1_ind_2_pdf", mnum+"_2_username.pdf")
glue("deliverable_py1_ind_2_py", mnum+"_2_username.py")
```

```{table} Deliverables
:class: deliverables
:name: tab:Py:M1:individual_deliverables

|    Task(s) |  Deliverables                                 |
|:----------:|:----------------------------------------------|
|          1 | {glue:text}`deliverable_py1_ind_1_word_pdf`   |
|          1 | {glue:text}`deliverable_py1_ind_1_excel_pdf`  |
|          1 | {glue:text}`deliverable_py1_ind_1_py`         |
|          2 | {glue:text}`deliverable_py1_ind_2_pdf`        |
|          2 | {glue:text}`deliverable_py1_ind_2_py`         |
```