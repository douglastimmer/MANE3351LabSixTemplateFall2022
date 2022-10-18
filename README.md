# MANE 3351 - Manufacturing Engineering Analysis

## Laboratory 6 Assignment

#### Assigned: October 19, 2022

#### Due: October 24, 2022 (before 3:30 pm)

---

#### Learning Goals

1.  Write user-defined scalar function in Python

#### Description

The purpose of this laboratory is the use of user-defined functions in Python.

For this lab you will write a function that evaluates the probability density function of the smallest extreme value probability density function (pdf) shown below.

$$
f(x)=\frac{1}{\sigma}\exp\left[\frac{x-\mu}{\sigma}-\exp\left[\frac{x-\mu}{\sigma}\right]\right]
$$

where $\sigma>0$, $-\infty<\mu<\infty$, and $-\infty< x<\infty$. Your user-defined function will accept three parameters $x$, $\mu$ (mu) and $\sigma$ (sigma) and returns the value of $f(x)$.

#### Step 1

Edit the first cell (markdown), to update your personal information.

#### Step 2

In cell 2 (Python cell), define a scalar function to return a single value of $f(x)$ defined in equation 1 above when provided the values of *x*, $\mu$ and $\sigma$. 

Examples of user-defined functions have been provided in most, if not all, classroom Jupyter Notebook examples. A helpful resource for this step is [How to Create User-Defined Functions in Python](https://towardsdatascience.com/how-to-create-user-defined-functions-in-python-e5a529386534). 

#### Step 3

Add three lines below the function declaration to input the values for $x$, $\mu$, and $\sigma$. Use the Jupyter Notebook classroom demonstration from lecture 12, October 5 as an example.

#### Step 4

Add a line below the input commands to run and store your user-defined function.

#### Step 5

After running and testing your program, save the Jupyter Notebook. Upload your repository using GitHub desktop.
