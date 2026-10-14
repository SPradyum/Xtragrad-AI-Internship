# Challenge 3 — Resume Analyzer

## Objective
Compare a fictional candidate profile with a job description without inventing qualifications.

## Tool
ChatGPT (practice exercise documented now).

## Fictional candidate profile
- Education: B.Tech. Computer Science student
- Listed skills: Python, HTML, CSS, MySQL
- Project: student portfolio website using HTML and CSS
- Professional experience: not stated
- Machine-learning experience: not stated

## Sample job description
**Junior Python Developer**
- Required: Python fundamentals, SQL, debugging, Git basics
- Preferred: REST APIs, automated testing, familiarity with a web framework

## Prompt
> Act as a resume-review assistant. Compare only the fictional candidate information and job description below. Separate supported matches from missing or unverified skills. Do not invent experience, certifications, project results, or proficiency levels. Return (1) supported matches, (2) missing or unverified requirements, (3) truthful improvement suggestions, and (4) three follow-up questions. If evidence is absent, label it “not stated.”

## Generated analysis

### Supported matches
- **Python:** Listed as a skill; proficiency is not demonstrated.
- **SQL/MySQL:** MySQL is listed and is relevant to SQL database work.
- **Project experience:** A portfolio website is listed, but it does not establish Python development experience.

### Missing or unverified
- Debugging: not stated.
- Git: not stated.
- REST APIs: not stated.
- Automated testing: not stated.
- Python web framework: not stated.
- Professional experience: not stated.

### Truthful improvement suggestions
- Build and document a Python project with verifiable functionality.
- If Git was used, provide a repository link and describe the actual workflow.
- Add debugging, testing, API, or framework skills only after gaining and demonstrating them.
- Describe personal contributions accurately.

### Follow-up questions
1. Have you built a Python project you can demonstrate?
2. Have you used Git for version control?
3. Have you worked with APIs, automated tests, or a Python web framework?

## Evaluation
| Criterion | Result | Observation |
|---|---|---|
| Uses supplied facts | Pass | Claims map to profile details |
| Distinguishes unknowns | Pass | Unverified skills marked “not stated” |
| Avoids fabricated achievements | Pass | No invented metrics or certifications |
| Actionability | Pass | Suggestions identify useful next evidence |

## Limitations
This fictional example is not a real employability assessment. Actual skills require supporting evidence.

## Key learning
A good analysis prompt constrains the AI to supplied facts and separates evidence from assumptions.
