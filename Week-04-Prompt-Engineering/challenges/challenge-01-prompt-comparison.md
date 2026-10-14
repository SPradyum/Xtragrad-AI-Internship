# Challenge 1 — Prompt Comparison

## Objective
Compare a vague prompt with a structured prompt.

## Tool
ChatGPT (practice exercise documented now).

## Initial prompt
> Explain Python.

## Illustrative initial output
Python is a programming language used to build websites, automate tasks, analyze data, and create applications. It supports variables, conditions, loops, functions, and classes.

## Improved prompt
> Act as a Python tutor for a beginner CSE student. Explain variables, common data types, and conditional statements in simple language. Give one short code example for each concept, explain the output, and finish with five practice questions. Use headings.

## Illustrative improved output

### Variables
A variable is a name that refers to a value.
```python
student_name = "Aarav"
age = 20
print(student_name, age)
```
Output: `Aarav 20`

### Common data types
- `int`: whole numbers, e.g. `7`
- `float`: decimal numbers, e.g. `3.5`
- `str`: text, e.g. `"Python"`
- `bool`: `True` or `False`

### Conditional statements
```python
marks = 72
if marks >= 40:
    print("Pass")
else:
    print("Try again")
```
Output: `Pass`

### Practice questions
1. Create a variable containing your name.
2. What is the type of `8.25`?
3. Store a number in `age` and print it.
4. Write an `if` statement that checks whether a number is positive.
5. What is the purpose of `else`?

## Evaluation
| Criterion | Initial prompt | Improved prompt |
|---|---|---|
| Relevance | Pass | Pass |
| Clarity | Partial | Pass |
| Completeness | Partial | Pass |
| Output structure | Unspecified | Headings, examples, outputs, quiz |
| Constraint adherence | Few constraints | Mostly follows instructions |

## Observation
The initial prompt leaves audience, depth, and format unspecified. The improved prompt specifies audience, topics, examples, and a quiz, making the output more predictable. The response still requires review.

## Key learning
Specific prompts communicate both the task and the criteria for a useful answer. Detail improves controllability but does not remove the need to verify output.
