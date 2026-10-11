# Functions

## Basic Idea

A **Function** is a rule that takes an input and produces **only one output** for that input

Think of it like a machine: you put a number in, the machine does something to it, and you get a number out

![Function as a Machine](./.assets/function-machine.jpg)

Example notation for a function:
$$
f(x) = x^2
$$

Here, **f** is the function name, **x** is the input and $f(x)$ is the output.

Here we can place any value (which is defined for a function, we'll talk about that later) in place of x.
For example:
$$
\begin{aligned}
f(x) &= x^2 \\
f(1) &= 1^2 = 1 \\
f(2) &= 2^2 = 4 \\
f(3) &= 3^2 = 9 \\
\end{aligned}
$$

Notice that $f(x)$ means "**f of x**" and not $f \cdot x$.

## What makes a rule a function

The Most important rule is:
**Every valid input must have exactly one output.**
- One input -> one output: valid
- Two input -> same output: valid
- One input -> more than one output: not a function

For example, consider $y = x^2$. Both $x = \pm 2$ gives the same output $4$. That's perfectly fine because each input matches to one output.

But a relation like $y^2 = x$ gives two possible values of $y$ when $x = 4$:

$$
y = \pm 2
$$

Therefore, $y^2 = x$, when treated as a rule assigning $y$ to each $x$, is **not a function** over the real numbers.

## Domain and Range
Every function has two important concepts:
- **Domain:** the set of permitted inputs.
- **Range:** the set of outputs the function actually produces.

For $f(x) = x^2$ assuming real numbers:
- Domain: $\mathbb{R}$, because any real number can be squared
- Range: $[0, \infty)$, because a real number squared cannot be negative

## Note before we move forward
Functions are the foundations of calculus because calculus studies how their outputs change when their inputs change.
We'll learn about their usage in the next chapters.

