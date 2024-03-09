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

(mod:ma2_ind_task_2)=
# Task 2

## Introduction
Engineers regularly perform economic analyses on potential purchases needed for
their projects. You are part of team working on a manufacturing productivity
improvement project and are planning to take out an amortized loan to pay for
necessary equipment and training. As part of the purchase and cost analysis, you
must determine some information about expected payments for the loan.  

[Amortization](https://www.investopedia.com/terms/a/amortized_loan.asp) is one common type of loan processing. The loan has fixed payments over its life, and the payments are applied to both interest accrued and the
original principle. The interest is calculated on the existing principle at the
end of each payment period. Early payments in an amortized loan are mostly
paying accrued interest with only small amounts paying down the original
principle. Over time, the size of the interest component of the total payment
decreases and the size of the principal component increases.  

You can calculate the fixed payment amount on an amortized loan using the equation 

```{math}
:name: eq:ma2:fixed payment amount

A = \frac{P[r(1+r)^n]}{(1+r)^n-1}
```


Where  
- $P$ is the principal amount of the loan (i.e., the amount borrowed) 
- $n$ is the number of total payments for the life of the loan 
- $r$ is the [periodic interest rate](https://www.bankrate.com/glossary/p/periodic-rate/), in decimal form, in terms of the time period between payments (e.g., percent per month when n payments are monthly payments) 
You want to know how much principle has been paid back after some number of payments, $t$. This is called the cumulative principal payment, $S$. For example: You have a loan with a $$1000/month$ payment. For the first three payments, the amount you paid towards principle was $$100$, then $$120$, and then $$145$. Your cumulative principal payments for those months were $$100$, $$220$, and $$365$. A general equation to calculate the cumulative principal payment is 

```{math}
:name: eq:ma2:cumulative principal payment

S(t) = A \sum_{k=1}^{t} (1+r)^{-(n-k+1)}
```

Where 
- $S(t)$ is the cumulative principal payment after payment $t$. [Click here](https://www.khanacademy.org/math/ap-calculus-ab/ab-integration-new/ab-6-3/a/review-summation-notation) for help with summation notation. 
You expect the project will take out a loan with a principle of $$500,000$, with an annual interest rate of $7%$, and paid back in equal monthly installments over a period of $n$ years, where $n$ will be determined by user input. 
Use {program}`MATLAB` to write a script that will determine the cumulative total payments and the cumulative principal payments at each monthly interval.


## Task Instructions

1. Open the {program}`MATLAB` Template and fill out the header in formation.
   Then save the file as
   {glue:text}`../../../6_ind_assignments.md::deliverable_ma2_ind_2_m:`

2. In the {MATLAB}`%% INITIALIZATION` section, define variables for the
   principal ($$500,000$), annual interest rate ($7%$), and get user input for
   the time for repayment (in years).

3.	In the {MATLAB}`%% CALCULATIONS` section of your script do the following. Be sure to use at least 1 {MATLAB}`for` loop in your calculations.
  •	Determine a vector of the cumulative total payments that have been paid toward the loan at each month for the entire loan period.
  •	Determine a vector of the cumulative principal payments that have been paid at each month for the entire loan period. 
  •	Determine the total interest paid back on the loan (i.e. the amount over $$500,000$ paid back).
  •	Determine the number of payments that are made before the payments on the principal is greater than or equal to the payments on the interest. 

4.	In the {MATLAB}`%% OUTPUTS` section, display the principal, interest rate, and time of repayment (in years) that the user entered, the vectors for cumulative total payments and cumulative principal payments, the total amount repaid, and the total interest paid back using {MATLAB}`fprintf` and {MATLAB}`disp`. 

5.	Publish your script as {glue:text}`../../../6_ind_assignments.md::deliverable_ma2_ind_2_pdf:` and submit your deliverables to Gradescope. _(Note: {program}`MATLAB` will produce an error if you try to publish a script that requires user input. Before you publish, comment out your input statement and hard code the time for repayment as 30 years.)_

% Automatically generated of Sample Output section.
```{include} /_build/intermediate/Part_5_MATLAB/M2/tasks/ind_2/a/sample_output.md
```