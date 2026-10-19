# Tech Stack Evaluation

## Project
FYP Supervisor Recommendation System Using Multi-Criteria Decision Making

## Requirements that drive the decision
List 3 to 5 requirements from your own docs/requirements.md. Include at
least 2 non-functional requirements.
- [FR1]: The system shall students to enter and update their skills and project interests.
- [FR2]: The system shall allow lecturers to manage their profiles, expertise, and research areas.
- [FR4]: The system shall calculate a matching score for each lecturer based on the selected criteria.
- [FR5]: The system shall display eligible supervisors in order of their matching scores, from highest to lowest.
- [NFR1]: [requirement]
- [NFR2]: [requirement]

## Options
- Option A: Static website using HTML, CSS and JavaScript on GitHub Pages.
- Option B: Python web app using Flask with a database on a cloud host.
- Option C: Laravel web application with a MySQL database, using a free hosted development environment.

## Decision matrix
Weight: how important the criterion is for YOUR project (1 = low, 5 = high).
Score: how well each option does (1 = poor, 5 = excellent).
Weighted score = weight x score. Add them up for each option.

| Criterion                          | Weight | A score | B score | C score |
|------------------------------------|--------|---------|---------|---------|
| Fits my requirements               |   5    |    2    |         |    5    |
| Skills I already have              |   4    |    5    |         |    4    |
| Time to build before my deadline   |   3    |    4    |         |    3    |
| Free hosting and tools             |   4    |    5    |         |    4    |
| Performance and security needs     |   4    |    1    |         |    4    |
| Room to grow later                 |   4    |    2    |         |    4    |
| **Total (weighted)**               |        |    74   |         |    98   |

## Decision record
- **Context:** The project requires a web application that support student and lecturer accounts, profile management, supervisor recoomendations, score calculations and supervision requests. 
- **Decision:** Option C
- **Reasons:** [2 to 3 reasons, linked to your requirements and the matrix]
- **Consequences:** [what becomes easy, what becomes hard]
- **Risks and next review:** [what could go wrong, and when you will check again]
