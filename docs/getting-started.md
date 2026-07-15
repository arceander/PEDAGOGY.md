\# Getting started with PEDAGOGY.md



This guide explains how to start using \*\*PEDAGOGY.md\*\* to describe the pedagogical design of a course, subject, module or learning experience.



It is intended for teachers, teaching teams, instructional designers and educational technologists who want to make a course design explicit, reusable and usable by AI systems.



\---



\## 1. What you need before starting



Before completing \*\*PEDAGOGY.md\*\*, gather the main information about your course.



Recommended materials:



\- official course guide or syllabus;

\- learning outcomes or competences;

\- assessment criteria;

\- activity descriptions;

\- rubrics, if available;

\- course calendar;

\- institutional regulations;

\- AI use policy, if available;

\- examples of student work, if appropriate;

\- teaching resources, readings or links;

\- feedback guidelines, if available.



You do not need to have all this information before starting. The file can be completed progressively.



\---



\## 2. Copy the template



Start from the template file:



```text

PEDAGOGY.template.md

```



Copy it and rename the copy as:



```text

PEDAGOGY.md

```



Recommended folder structure:



```text

your-course/

│

├── PEDAGOGY.md

├── assessment.md

├── activities.md

├── content.md

├── ai-policy.md

├── feedback.md

├── rubrics/

├── resources/

└── agents/

```



At the beginning, you only need \*\*PEDAGOGY.md\*\*. The other files can be added later if the course documentation grows.



\---



\## 3. Complete the minimum sections first



Do not try to complete the full advanced structure in one sitting.



Start with the minimum sections. These provide the essential pedagogical context.



Minimum sections:



1\. Course Identity

2\. Educational Context

3\. Learner Profile

4\. Learning Outcomes and Competences

5\. Pedagogical Principles

6\. Methodological Approach

7\. Assessment Design

8\. Feedback Model

9\. AI Use Policy

10\. Versioning and Maintenance



These sections allow another teacher, teaching assistant or AI system to understand the basic logic of the course.



\---



\## 4. Section-by-section starting guide



\### 4.1 Course Identity



Describe the basic identity of the course.



Include:



\- course name;

\- educational level;

\- programme or degree;

\- institution;

\- teacher or teaching team;

\- language;

\- duration;

\- credits or workload;

\- modality;

\- short description.



Good example:



```markdown

\- Course name: Information and Communication Technology in Primary Education

\- Educational level: Undergraduate higher education

\- Programme / degree: Bachelor’s Degree in Primary Education

\- Language(s): English

\- Credits / workload: 6 ECTS

\- Modality: Face-to-face with lecture-based and computer-based practical sessions

```



Avoid:



```markdown

\- Course name: ICT

\- Description: A course about technology

```



The second version is too vague to guide teaching design or AI-supported actions.



\### 4.2 Educational Context



Describe the conditions that shape the course.



Include:



\- curriculum requirements;

\- institutional constraints;

\- available spaces;

\- available technologies;

\- timetable constraints;

\- coordination with other courses;

\- relevant contextual factors.



This section helps avoid unrealistic proposals.



For example, if students only have access to a computer lab once per week, an AI system should not generate a course plan requiring daily lab access.



\### 4.3 Learner Profile



Describe who the learners are.



Include:



\- typical learner profile;

\- prior knowledge;

\- prior skills;

\- digital competence;

\- language competence;

\- expected difficulties;

\- accessibility needs;

\- common misconceptions.



Good example:



> Students are second-year Primary Education students. They use digital tools in personal contexts, but many have limited experience selecting technologies according to pedagogical criteria.



This kind of information helps adapt explanations, examples, tasks and feedback.



\### 4.4 Learning Outcomes and Competences



Define what learners should know, understand and be able to do.



Include:



\- general competences;

\- specific competences;

\- learning outcomes;

\- knowledge outcomes;

\- skill outcomes;

\- attitudinal outcomes;

\- professional outcomes.



Good learning outcomes should describe observable learning.



Use verbs such as:



\- analyse;

\- design;

\- compare;

\- justify;

\- evaluate;

\- create;

\- diagnose;

\- apply;

\- reflect.



Avoid vague outcomes such as:



> Students will understand the subject.



Better:



> Students will be able to analyse a school case and identify organizational factors that affect participation, coordination and improvement.



\### 4.5 Pedagogical Principles



Describe the pedagogical identity of the course.



Include:



\- core pedagogical principles;

\- conception of learning;

\- conception of teaching;

\- what good learning looks like;

\- pedagogical priorities;

\- practices to avoid.



This section is important because AI systems may generate technically correct but pedagogically inappropriate outputs if the course principles are not explicit.



Example:



> The course follows a constructivist and practice-based approach. Learning is developed through progressive application of theoretical concepts to realistic educational situations.



\### 4.6 Methodological Approach



Describe how teaching and learning are organized.



Include:



\- main methodologies;

\- teaching strategies;

\- learning strategies;

\- session structure;

\- individual work;

\- collaborative work;

\- project-based work;

\- use of educational technology;

\- use of AI.



This section should translate pedagogical principles into actual teaching practices.



Example:



> The course follows a T → TP → PS → Prj sequence: theoretical content, immediate theoretical-practical application, practical session work and integrative project work.



\### 4.7 Assessment Design



Describe how learning is assessed.



Include:



\- assessment approach;

\- formative assessment;

\- summative assessment;

\- assessment tasks;

\- weighting;

\- minimum requirements;

\- criteria;

\- evidence of learning;

\- reassessment rules;

\- academic integrity expectations;

\- role of AI in assessment.



This section is essential for alignment.



AI-generated activities, feedback or rubrics should not contradict the assessment design.



\### 4.8 Feedback Model



Describe how feedback should be provided.



Include:



\- feedback purpose;

\- feedback timing;

\- feedback tone;

\- feedback depth;

\- feedback structure;

\- feedback focus;

\- when to correct directly;

\- when to give hints;

\- when to ask guiding questions;

\- AI feedback rules.



Example:



> Feedback should be formative, specific and improvement-oriented. It should identify what works, what needs improvement, why it matters and what the student should do next.



\### 4.9 AI Use Policy



Define how AI may and may not be used in the course.



Include:



\- allowed uses;

\- recommended uses;

\- restricted uses;

\- prohibited uses;

\- AI use by learners;

\- AI use by teachers;

\- AI use in assessment;

\- transparency requirements;

\- citation or acknowledgement rules;

\- data privacy requirements;

\- consequences of misuse.



This section is necessary when the file will be used with AI assistants or when students may use generative AI in course tasks.



\### 4.10 Versioning and Maintenance



Record the state of the file.



Include:



\- version;

\- last updated date;

\- updated by;

\- reviewed by;

\- course edition;

\- sections updated;

\- reason for update;

\- known limitations;

\- pending improvements.



Example:



```markdown

\- Version: 1.0 draft

\- Last updated: 2026-06-26

\- Updated by: Teaching team

\- Known limitations: Assessment criteria need to be reviewed after the first course edition.

```



\---



\## 5. Add recommended sections



Once the minimum sections are completed, add the recommended sections.



Recommended sections:



1\. Content Organization

2\. Learning Activities

3\. Quality Criteria for Student Work

4\. Roles and Responsibilities

5\. Inclusion and Accessibility



These sections make the file more useful for generating activities, resources, feedback and teaching materials.



\---



\## 6. Add advanced sections



Complete the advanced sections if you want to use \*\*PEDAGOGY.md\*\* with AI assistants, educational agents, analytics or modular documentation.



Advanced sections:



1\. AI Agent Behaviour

2\. Learning Evidence and Analytics

3\. Related Files and Modular Extensions



These sections are especially useful when:



\- the course uses an AI assistant;

\- several teachers coordinate the same course;

\- you want AI-generated outputs to follow specific rules;

\- you want to derive complementary files;

\- learning evidence or analytics will inform teaching decisions.



\---



\## 7. Use PEDAGOGY.md with an AI system



Once the file is completed, it can be used as context for AI-supported educational work.



Typical uses:



\- generate learning activities;

\- generate examples;

\- draft rubrics;

\- give formative feedback;

\- create study questions;

\- design case studies;

\- review alignment between activities and outcomes;

\- configure an AI teaching assistant;

\- create course-specific prompts;

\- produce student-facing explanations;

\- develop assessment support materials.



Recommended prompt:



```text

Use the following PEDAGOGY.md file as the primary pedagogical context for this course.



Generate outputs that are aligned with the learning outcomes, learner profile, methodology, assessment model, feedback rules and AI use policy.



Do not generate anything that contradicts the file.



If information is missing, identify the missing information before making assumptions.



Then provide the content of your PEDAGOGY.md.

```



\---



\## 8. Check alignment before using AI-generated outputs



Before using any AI-generated output, check whether it is aligned with the file.



Use this checklist:



\- \[ ] Does it match the learning outcomes?

\- \[ ] Is it appropriate for the learner profile?

\- \[ ] Does it follow the methodological approach?

\- \[ ] Is it compatible with the assessment model?

\- \[ ] Does it respect the feedback rules?

\- \[ ] Does it respect the AI use policy?

\- \[ ] Does it avoid sensitive or private data?

\- \[ ] Is it feasible in the actual course context?

\- \[ ] Is it pedagogically justified?



AI-generated outputs should be reviewed by a teacher before being used with students.



\---



\## 9. Derive complementary files



If a section becomes too long, move the details to a complementary file.



Recommended modularization:



| Information | Recommended file |

|---|---|

| Core pedagogical logic | `PEDAGOGY.md` |

| Detailed assessment system | `assessment.md` |

| Activities and task instructions | `activities.md` |

| Content, readings and resources | `content.md` |

| AI use rules | `ai-policy.md` |

| Feedback templates and examples | `feedback.md` |

| Case studies and scenarios | `cases.md` |

| Rubrics | `rubrics/` |

| Teaching materials | `resources/` |

| AI assistant instructions | `agents/` |

| Reusable prompts | `prompts/` |

| AI-executable actions | `skills/` |

| Learning evidence and analytics | `analytics.md` |

| Ethical principles and boundaries | `ethics.md` |



The core file should remain readable and maintainable.



\---



\## 10. Common mistakes



\### Mistake 1: Writing generic statements



Avoid:



> The course uses active methodologies.



Better:



> The course uses case-based learning, group discussion and project work. Students analyse realistic school situations and design justified improvement proposals.



\### Mistake 2: Describing contents but not pedagogy



A list of topics is not enough.



\*\*PEDAGOGY.md\*\* should explain how those topics are taught, applied, assessed and connected to student learning.



\### Mistake 3: Leaving assessment disconnected



Learning outcomes, activities and assessment should be aligned.



If students are expected to design a project, the assessment criteria should evaluate design quality, justification, feasibility and use of evidence.



\### Mistake 4: Defining AI use too vaguely



Avoid:



> Students may use AI responsibly.



Better:



> Students may use AI to clarify concepts, generate examples and revise text structure. They may not submit AI-generated analysis as their own. Relevant AI use must be declared in assessable tasks.



\### Mistake 5: Overloading PEDAGOGY.md



Do not put every rubric, reading, activity and prompt in the core file.



Use complementary files when details grow.



\---



\## 11. Recommended workflow



A practical workflow for teachers:



1\. Complete the minimum sections.

2\. Review coherence between outcomes, methodology and assessment.

3\. Add feedback and AI use rules.

4\. Complete learner profile and accessibility information.

5\. Add activity and content structure.

6\. Use the file to generate or review teaching materials.

7\. Move detailed information to complementary files.

8\. Update the versioning section.

9\. Review the file at the end of the course.

10\. Revise it before the next edition.



\---



\## 12. Completion checklist



Before using \*\*PEDAGOGY.md\*\* as course context, check:



\- \[ ] The course identity is clear.

\- \[ ] The educational context is specific.

\- \[ ] The learner profile is realistic.

\- \[ ] Learning outcomes are observable.

\- \[ ] Pedagogical principles are explicit.

\- \[ ] Methodology is described in practical terms.

\- \[ ] Assessment tasks and criteria are included.

\- \[ ] Feedback rules are defined.

\- \[ ] AI use is clearly bounded.

\- \[ ] Inclusion and accessibility have been considered.

\- \[ ] Related files are referenced if needed.

\- \[ ] The file has version information.

\- \[ ] Known limitations are listed.

\- \[ ] The teaching team has reviewed the file.



\---



\## 13. After completing the file



After completing \*\*PEDAGOGY.md\*\*, you can use it to create:



\- `assessment.md`;

\- `activities.md`;

\- `content.md`;

\- `ai-policy.md`;

\- `feedback.md`;

\- `cases.md`;

\- course-specific rubrics;

\- AI assistant instructions;

\- reusable prompts;

\- teaching materials;

\- student guides;

\- quality criteria;

\- research documentation.



The file should be treated as a living document. It should evolve as the course, students, institutional context and educational technologies change.



\---



\## 14. Minimum viable PEDAGOGY.md



If you need a short first version, complete only the following sections from the full structure:



```markdown

\# PEDAGOGY.md



\## 1. Course Identity



\## 2. Educational Context



\## 3. Learner Profile



\## 4. Learning Outcomes and Competences



\## 5. Pedagogical Principles



\## 6. Methodological Approach



\## 9. Assessment Design



\## 10. Feedback Model



\## 13. AI Use Policy



\## 18. Versioning and Maintenance

```



This minimum version is enough to begin using \*\*PEDAGOGY.md\*\* as a structured pedagogical context.



Later, expand it progressively.

