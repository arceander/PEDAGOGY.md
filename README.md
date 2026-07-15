# PEDAGOGY.md



**PEDAGOGY.md** is an open documentation standard for describing the pedagogical, methodological, assessment, organizational and ethical design of a course, subject, module or learning experience in a structured Markdown file.



Its purpose is to make the pedagogical intent of a course explicit, reusable and actionable so that AI systems, educational assistants, teaching agents, learning resources, rubrics, activities and feedback processes can operate coherently within the course context.



**PEDAGOGY.md** is designed to act as the core pedagogical specification file of a course.



---



## Why PEDAGOGY.md?



Generative AI systems can produce educational materials, explanations, feedback, rubrics, activities and tutoring interactions. However, without a clear representation of the pedagogical context, these outputs often become generic, misaligned or inconsistent with the real design of the course.



**PEDAGOGY.md** addresses this problem by documenting the pedagogical logic of a course in a structured and machine-readable format.



It helps answer questions such as:



- What is the course trying to achieve?

- Who are the learners?

- What pedagogical principles guide the course?

- How are contents, activities, assessment and feedback organized?

- What counts as quality student work?

- What role should teachers, learners and AI systems play?

- What uses of AI are allowed, recommended, restricted or prohibited?

- How should an AI assistant behave within this specific learning context?



The central idea is simple:



> AI systems can only act pedagogically if they understand the pedagogical context in which they operate.



---



## What is PEDAGOGY.md?



**PEDAGOGY.md** is not a syllabus, a lesson plan or a technical configuration file.



It is a structured pedagogical specification that describes the “pedagogical DNA” of a course.



It can be used to:



- document the instructional design of a course;

- align learning outcomes, activities, assessment and feedback;

- configure AI assistants or educational agents;

- generate teaching and learning resources;

- support coherent feedback practices;

- define responsible AI use in educational settings;

- make course design more explicit, shareable and reusable;

- create complementary files such as `assessment.md`, `activities.md`, `ai-policy.md` or `feedback.md`.



---



## Who is it for?



**PEDAGOGY.md** is intended for:



- teachers and lecturers;

- instructional designers;

- educational technologists;

- teacher educators;

- schools, universities and training providers;

- AI-in-education researchers;

- developers of educational AI assistants;

- teams designing AI-supported learning environments.



The standard is written in Markdown so that it can be used by educators without advanced technical knowledge while remaining readable by AI systems and software tools.



---



## Core principles



**PEDAGOGY.md** is based on eight design principles.



### 1. Pedagogical clarity



The file should make the teaching and learning approach explicit.



### 2. Practical usability



Teachers should be able to complete and maintain it without technical expertise.



### 3. Instructional alignment



Learning outcomes, activities, assessment, feedback and AI use should be coherent.



### 4. Contextualization



The file should describe the real institutional, curricular, learner and organizational context.



### 5. Modularity



The core file should remain manageable while allowing more detailed complementary files.



### 6. AI-readability



The structure should help AI systems interpret and apply the course design.



### 7. Pedagogical traceability



AI-generated outputs should be justifiable from the information defined in **PEDAGOGY.md**.



### 8. Ethical responsibility



The file should define limits related to privacy, transparency, inclusion, assessment, human oversight and responsible AI use.



---



## Standard structure



The advanced version of **PEDAGOGY.md** includes the following sections:



1. **Course Identity**

   Basic identification of the course, subject, module or learning experience.



2. **Educational Context**

   Institutional, curricular, regulatory and organizational conditions.



3. **Learner Profile**

   Characteristics, needs, prior knowledge, difficulties and accessibility considerations.



4. **Learning Outcomes and Competences**

   Expected knowledge, skills, competences and performance levels.



5. **Pedagogical Principles**

   Core learning and teaching principles guiding the course.



6. **Methodological Approach**

   Teaching strategies, learning strategies, session structure and use of technology.



7. **Content Organization**

   Topics, conceptual blocks, key concepts, readings and resources.



8. **Learning Activities**

   Types of activities, expected outputs and relationship with learning outcomes.



9. **Assessment Design**

   Assessment approach, tasks, criteria, evidence, weighting and academic integrity.



10. **Feedback Model**

    Feedback purpose, timing, tone, depth and focus.



11. **Quality Criteria for Student Work**

    Standards for evaluating the quality of student productions.



12. **Roles and Responsibilities**

    Expected roles of teachers, learners, AI systems and other actors.



13. **AI Use Policy**

    Allowed, recommended, restricted and prohibited uses of AI.



14. **AI Agent Behaviour**

    Behavioural specification for AI assistants or educational agents and AI feedback rules.



15. **Inclusion and Accessibility**

    Accessibility principles, learner variability and inclusive design considerations.



16. **Learning Evidence and Analytics**

    Evidence of learning, data sources, interpretation rules and privacy limits.



17. **Related Files and Modular Extensions**

    Relationship with complementary files such as `assessment.md`, `activities.md`, `ai-policy.md`, `feedback.md`, `cases.md`, `skills/`, `prompts/` or `agents/`.



18. **Versioning and Maintenance**

    Version history, review frequency, known limitations and pending improvements.



---



## Quick start



To use **PEDAGOGY.md** in your own course:



1. Copy `PEDAGOGY.template.md`.

2. Rename it as `PEDAGOGY.md`.

3. Complete the required sections first:

   - Course Identity

   - Educational Context

   - Learner Profile

   - Learning Outcomes and Competences

   - Pedagogical Principles

   - Methodological Approach

   - Assessment Design

   - Feedback Model

   - AI Use Policy

4. Add more detail progressively.

5. Use the file as context when creating teaching resources, AI assistants, rubrics, activities or feedback models.

6. Update the file when the course design changes.



---



## Example use cases



### 1. Designing an AI teaching assistant



A teacher can use **PEDAGOGY.md** to configure an AI assistant that explains concepts, generates examples, supports students, gives feedback and respects the pedagogical boundaries of the course.



### 2. Generating aligned learning activities



An AI system can use the file to generate activities that match the course methodology, learner profile, learning outcomes and assessment model.



### 3. Supporting formative feedback



The feedback section can guide teachers or AI assistants in providing feedback that is consistent in tone, depth, structure and pedagogical purpose.



### 4. Making AI use transparent



The AI policy section can clarify which uses of AI are allowed, restricted or prohibited in learning activities and assessment tasks.



### 5. Improving course documentation



Even without AI, **PEDAGOGY.md** can help teaching teams make course design explicit, review alignment and coordinate pedagogical decisions.



---



## Related files



**PEDAGOGY.md** can be extended through complementary files:



| File or folder | Purpose |

|---|---|

| `assessment.md` | Detailed assessment system, rubrics, criteria, weighting, reassessment rules and grading guidance. |

| `activities.md` | Detailed design of learning activities, instructions, timing, grouping, outputs and sequencing. |

| `content.md` | Course topics, conceptual blocks, key concepts, readings and learning resources. |

| `ai-policy.md` | Detailed AI use policy, including transparency, authorship, privacy and academic integrity. |

| `feedback.md` | Feedback templates, tone, depth, examples, correction rules and AI-assisted feedback guidance. |

| `cases.md` | Practical cases, problems, simulations, scenarios and discussion prompts. |

| `rubrics/` | Specific rubrics for tasks, products, competences or learning outcomes. |

| `resources/` | Teaching materials, readings, links, examples, slides, worksheets and reusable resources. |

| `skills/` | AI-executable skills based on the pedagogical context of the course. |

| `prompts/` | Reusable prompts for teachers, learners or AI agents. |

| `agents/` | Specifications for specific educational agents derived from **PEDAGOGY.md**. |

| `analytics.md` | Learning evidence, indicators, data sources, interpretation rules and ethical limits. |

| `ethics.md` | Ethical principles for AI, data, privacy, transparency, bias, equity and human oversight. |



---



## How AI systems should use PEDAGOGY.md



An AI system using **PEDAGOGY.md** should:



- treat it as the primary pedagogical context of the course;

- align outputs with learning outcomes, methodology, assessment and feedback criteria;

- respect the defined roles of teachers, learners and AI systems;

- follow the AI use policy and ethical constraints;

- adapt explanations and scaffolding to the learner profile;

- avoid generating resources that contradict the course design;

- ask for clarification when the file does not provide enough information;

- make outputs traceable to the pedagogical decisions documented in the file.



An AI system should not:



- replace teacher judgement;

- assign grades without human supervision;

- infer sensitive learner information;

- ignore institutional rules or privacy requirements;

- provide answers that undermine assessment integrity;

- act outside the role defined for the AI agent;

- generate learning activities misaligned with the stated outcomes and assessment model.



---



## Repository contents



This repository may include:



- `PEDAGOGY.md`

- `PEDAGOGY.template.md`

- `PEDAGOGY.example.md`

- `docs/`

- `examples/`

- `schemas/`

- `.github/`

- `CONTRIBUTING.md`

- `CHANGELOG.md`

- `ROADMAP.md`

- `LICENSE`



Recommended first files:



- `PEDAGOGY.md`: specification of the standard.

- `PEDAGOGY.template.md`: editable template for teachers.

- `PEDAGOGY.example.md`: completed example.

- `docs/getting-started.md`: quick start guide.

- `docs/structure.md`: explanation of each section.

- `docs/ai-usage.md`: guidance for AI systems.

- `docs/file-ecosystem.md`: explanation of related files.

- `CONTRIBUTING.md`: contribution guidelines.

- `CHANGELOG.md`: version history.

- `ROADMAP.md`: planned development.



---



## Status



**Current version:** v1.0 draft



This project is under active development. The current version proposes an advanced structure for **PEDAGOGY.md** and a first documentation ecosystem for sharing, testing and improving the standard.



Future work may include:



- simplified and advanced templates;

- examples from different educational levels;

- multilingual versions;

- a formal JSON schema;

- validation tools;

- LMS-oriented implementation examples;

- AI assistant configuration examples;

- research-based documentation;

- community contributions.



---



## Contributing



Contributions are welcome.



You can contribute by:



- improving the template;

- proposing new fields;

- adding examples;

- clarifying documentation;

- translating the standard;

- identifying ambiguities;

- suggesting links with learning design, instructional design, assessment, feedback or AI-in-education frameworks.



Before proposing a new section or field, consider whether it should belong to the core **PEDAGOGY.md** file or to a complementary file such as `assessment.md`, `activities.md`, `ai-policy.md` or `feedback.md`.



---



## License



This project is intended to be shared as an open educational documentation standard.



**Recommended license:** Creative Commons Attribution 4.0 International — CC BY 4.0.



This allows others to use, adapt and redistribute the material, provided that appropriate credit is given.



---



## Citation



If you use or adapt **PEDAGOGY.md**, please cite the project as:



> Arce, A., Portillo, J. and Tejada, E. (2026). *PEDAGOGY.md: An open documentation standard for pedagogical design and AI-supported education*. GitHub repository.



---



## Acknowledgements



**PEDAGOGY.md** is informed by work on learning design, instructional design, constructive alignment, feedback, educational AI, pedagogical agents, universal design for learning, learning analytics and responsible AI in education.



The project builds on the idea that pedagogical intent should be made explicit, structured and actionable so that educational technologies and AI systems can support, rather than replace, professional teaching judgement.

