# Challenge 4 — Quiz Generator and Validation

## Objective
Generate five beginner-level multiple-choice questions about introductory AI concepts and validate the answer key.

## Tool
ChatGPT (practice exercise documented now).

## Prompt
> Create five beginner-level multiple-choice questions about AI, machine learning, labelled training data, classification, and model evaluation. Each question must have four options (A–D), exactly one best answer, and a short explanation. Provide a separate answer key and avoid ambiguous wording.

## Generated quiz

**1. Which statement best describes artificial intelligence?**
A. A system that can only store files  
B. A broad field focused on systems performing tasks associated with intelligence  
C. A programming language  
D. A type of monitor  
**Answer: B.** AI is a broad field concerned with tasks such as reasoning, perception, prediction, and language processing.

**2. What is a common characteristic of machine learning?**
A. It always requires no data  
B. It learns patterns from data to perform a task  
C. It guarantees perfect predictions  
D. It can only be used for images  
**Answer: B.** Machine-learning methods use data to learn patterns relevant to a task.

**3. In supervised learning, what is labelled training data?**
A. Examples associated with known target answers  
B. Deleted data  
C. Data containing only filenames  
D. Data never used during training  
**Answer: A.** Labels provide target outputs for training examples.

**4. Which is a classification task?**
A. Predicting tomorrow’s temperature as a continuous number  
B. Sorting files alphabetically  
C. Classifying an email as spam or not spam  
D. Compressing an image  
**Answer: C.** Classification predicts a category or class label.

**5. Why evaluate a model on data not used for training?**
A. To automatically enlarge training data  
B. To estimate performance on unseen examples  
C. To guarantee no bias  
D. To eliminate the need for testing  
**Answer: B.** Held-out evaluation helps estimate generalization but cannot guarantee performance in every real-world setting.

## Answer validation
| Question | Answer | Status | Reason |
|---|---|---|---|
| 1 | B | Pass | Broad description of AI |
| 2 | B | Pass | Correctly describes learning patterns from data |
| 3 | A | Pass | Correct description of labelled examples |
| 4 | C | Pass | Spam detection is classification |
| 5 | B | Pass | Held-out data estimates generalization |

## Evaluation
- Five questions: Pass
- Four options per question: Pass
- One best answer per question: Pass
- Explanations included: Pass
- All five target concepts covered: Pass

## Limitations
These introductory questions do not comprehensively test AI knowledge. A formal quiz should be checked against course material.

## Key learning
Explicit requirements for question count, options, answer uniqueness, and explanations make the output easier to validate. The answer key must still be checked.
