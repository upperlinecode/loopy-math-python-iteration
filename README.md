# Loopy Math

[![Run on Repl.it](https://repl.it/badge/github/upperlinecode/loopy-math-python-iteration)](https://repl.it/github/upperlinecode/loopy-math-python-iteration)

## TL;DR

This lab will give you practice with `for __ in range(__):` and style loops. Open up loops.py, where the challenges are written as python comments. Run the code after each new loop you write to see if your code works as intended.

## Contents

1. [Intro](#intro)
2. [The Lab](#the-lab)
3. [Extra Help](#extra-help)
4. [Stretch](#stretch)

## Intro

![Pandas Looping Through a Slide](https://media.giphy.com/media/ieaUdBJJC19uw/giphy.gif)

Python can be used to make mathematical tasks much less... well... mathy. Use `for` loops to compute some of these math challenges without having to add hundreds of numbers by hand.

## The Lab

Loops in python allow us to automate processes that would be tedious and exhausting otherwise.

Without loops, printing 100 different numbers would take 100 lines of code. With loops, we can do it in 2 lines of code. More impressively, we can bump that number up to 10,000, or even into the millions and billions without having to add extra lines of code.

Open up the main.py file, and try to complete each of the `for ___ in range(___):` loops described there. 

## Extra Help

Here's the easiest answer for problem 1:
```python
for i in range(101):
  print(i)
```
This method will also print the zero, which is fine, but not technically what the challenge asked for. So remember that range can also take TWO arguments - a start and an end. You could refine your answer this way:
```python
for i in range(0, 101):
  print(i)
```

Each of the challenges can be done in at least two ways, and some can be done in as many as 10 ways, so as long as your output meets the criteria for each problem, you're doing great!

## Stretch

There are stretch activities built right into this lab.
