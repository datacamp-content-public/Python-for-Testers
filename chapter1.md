---
title: Basics
description: 'An overview of the basic concepts to understand when it comes to Python to be able to start reading/writing Python'
---

## Python Data Types

```yaml
type: NormalExercise 
lang: python
xp: 100 
skills: 2
key: 6a123d9ae2   
```


Python offers several different data types built into it.

* Integers 
    * A number with essentially no limit to length, all based on the computers hardware
    * Examples:
        * 10
        * -1000
        * 12345678901234567890
        * 0
* Float
    * A number with a decimal point
    * Examples:
        * 1.24
        * -7.567
        * .2
* Strings
    * A combination of letters, numbers, characters wrapped in either single or double quotes
    * All characters between the delimiters are considered part of the single string
    * Examples:
        * "Python is Awesome!"
        * 'testing is cool'
        * 'Python 3.70'
* Boolean Types
    * True or False
    * We'll discuss boolean values more indepth later on


`@instructions`
- Instruction 1
- Instruction 2
- Instruction 3

`@hint`
- Here is the hint for this setup problem. 
- It should get students 50% of the way to the correct answer.
- So don't provide the answer, but don't just reiterate the instructions.
- Typically one hint per instruction is a sensible amount.

`@pre_exercise_code`

```{python}
# Load datasets and packages here.
```


`@sample_code`

```{python}
print(type(10))
print(type(-1000))
print(type(1.24))
print(type(-0.74))
print(type('Python is Awesome!'))
print(type("testing is cool"))
print(type(True))
print(type(False))
```


`@solution`

```{python}
# Answer goes here
# Make sure to match the comments with your sample code
# to help students see the differences from solution
# to given.
```


`@sct`

```{python}
# Update this to something more informative.
success_msg("Some praise! Then reinforce a learning objective from the exercise.")
```


