# Challenge 2 — AI Study Assistant

## Objective
Generate a seven-day revision plan within a fixed daily time limit.

## Tool
ChatGPT (practice exercise documented now).

## Input
- Duration: 7 days
- Available time: 2 hours per day
- Topics: Python fundamentals, functions, lists, dictionaries, file handling

## Prompt
> Act as a study planner for a beginner CSE student. Create a seven-day Python revision plan with exactly two hours per day. Cover Python fundamentals, functions, lists, dictionaries, and file handling. Each day must include topic study, coding practice, and review. Use columns Day, Topic, Study, Practice, Review. Do not schedule more than 120 minutes per day.

## Generated plan
| Day | Topic | Study | Practice | Review | Total |
|---|---|---:|---:|---:|---:|
| 1 | Fundamentals and variables | 45 min | 60 min | 15 min | 120 min |
| 2 | Data types, operators, conditions | 40 min | 65 min | 15 min | 120 min |
| 3 | Loops and problem-solving | 35 min | 70 min | 15 min | 120 min |
| 4 | Functions and parameters | 40 min | 65 min | 15 min | 120 min |
| 5 | Lists and operations | 35 min | 70 min | 15 min | 120 min |
| 6 | Dictionaries and methods | 35 min | 70 min | 15 min | 120 min |
| 7 | File handling and mixed revision | 35 min | 65 min | 20 min | 120 min |

## Evaluation
| Criterion | Result | Observation |
|---|---|---|
| Relevance | Pass | Covers the requested topics |
| Completeness | Pass | Includes all seven days |
| Time constraint | Pass | Each day totals 120 minutes |
| Format adherence | Pass | Uses a table |
| Learning progression | Partial | Adjust based on actual prior knowledge |

## Refinement
> Add three coding problems per day, ordered from easy to moderate, and provide hints without revealing complete solutions unless requested.

## Key learning
Explicit time limits, topics, and table columns make a plan easier to inspect. The timetable should be adjusted based on actual progress.
