# Tech Stack Evaluation

## Project
[Name of your Assignment 1 or FYP project, in one line]

## Requirements that drive the decision
List 3 to 5 requirements from your own docs/requirements.md. Include at
least 2 non-functional requirements.
- [FR or NFR number]: The system shall allow users to create, read, update, and delete journal entries via text input or voice recording.
- [FR or NFR number]: The system shall convert voice recordings into text using a Speech-to-Text (STT) engine and display the transcription for user review.
- [FR or NFR number]: The system shall deploy an Agentic AI that autonomously searches and recommends localized campus or community mental health resources based on the journal's emotional context.

## Options
- Option A: static website (HTML and JavaScript) on GitHub Pages
- Option B: Python web app (Flask) with a database on a cloud host
- Option C: localhost

## Decision matrix
Weight: how important the criterion is for YOUR project (1 = low, 5 = high).
Score: how well each option does (1 = poor, 5 = excellent).
Weighted score = weight x score. Add them up for each option.

| Criterion                          | Weight | A score | B score | C score |
|------------------------------------|--------|---------|---------|---------|
| Fits my requirements               |   5    |    5    |    5    |    1    |
| Skills I already have              |   4    |    3    |    3    |    1    |
| Time to build before my deadline   |   4    |    3    |    3    |    1    |
| Free hosting and tools             |   4    |    4    |    4    |    1    |
| Performance and security needs     |   4    |    3    |    3    |    1    |
| Room to grow later                 |   5    |    4    |    4    |    1    |
| **Total (weighted)**               |  220   |         |         |         |

## Decision record
- **Context:** voice recognition to text may be unaccurate 
- **Decision:** option B
- **Reasons:** easy to implement
- **Consequences:** to make sure the agentic ai provide the suitable measurements to the users, convert voice to text may be unaccurate
- **Risks and next review:** unsuitable measurements provided by the ai, training the ai
