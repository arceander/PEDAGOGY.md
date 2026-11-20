# File ecosystem



This document explains the file ecosystem around **PEDAGOGY.md**.



**PEDAGOGY.md** is designed as the core pedagogical specification file of a course, subject, module or learning experience. It should define the main pedagogical logic of the course, but it should not contain every operational detail.



When information becomes too long, too specific or too frequently updated, it should be moved to a complementary file.



---



## 1. Core idea

PEDAGOGY.md supports selective and proportionate adoption. Teachers and teaching teams choose the documentation components that serve their learning context. A course may keep the relevant information in a single PEDAGOGY.md file or develop selected complementary modules. The file and folder structures shown in this repository are examples of possible implementations; they do not prescribe a directory structure. Modules that are not adopted are not automatically pending or missing.



The file ecosystem follows a modular principle:



> **PEDAGOGY.md** defines the pedagogical matrix. Complementary files develop specific dimensions of the course.



This avoids two problems:



1. Overloading **PEDAGOGY.md** with too much operational detail.

2. Fragmenting the course design into disconnected documents without a common pedagogical reference.



The goal is to keep **PEDAGOGY.md** readable, stable and useful as a context file for teachers, teaching teams and AI systems.



---



## 2. Example repository structure



A course-level implementation of **PEDAGOGY.md** may use the following structure:

This is a menu illustrated as one possible arrangement. Create only what you adopt. Even advanced documentation can remain in one file; no empty folders or replica of Ant_26.27 are required.



```text

course-name/

│

├── PEDAGOGY.md

├── assessment.md

├── activities.md

├── content.md

├── ai-policy.md

├── feedback.md

├── cases.md

├── analytics.md

├── ethics.md

│

├── rubrics/

│   ├── project-rubric.md

│   ├── presentation-rubric.md

│   └── exam-rubric.md

│

├── resources/

│   ├── readings.md

│   ├── links.md

│   ├── slides/

│   └── worksheets/

│

├── prompts/

│   ├── teacher-prompts.md

│   ├── student-prompts.md

│   └── feedback-prompts.md

│

├── agents/

│   ├── tutor-agent.md

│   ├── feedback-agent.md

│   └── activity-generator-agent.md

│

└── skills/

    ├── generate-case.md

    ├── review-draft.md

    └── create-rubric.md

```



Not every course needs all these files.



For a first implementation, **PEDAGOGY.md** may be enough. Additional files should be added only when they improve clarity, maintainability or reuse.



---



## 3. Main file: PEDAGOGY.md



### Function



**PEDAGOGY.md** is the matrix file.



It defines the general pedagogical, methodological, assessment, organizational, ethical and AI-related logic of the course.



### It should include



- course identity;

- educational context;

- learner profile;

- learning outcomes and competences;

- pedagogical principles;

- methodological approach;

- content organization;

- learning activity ecosystem;

- assessment model;

- feedback model;

- quality criteria;

- roles and responsibilities;

- AI use policy;

- AI agent behaviour;

- inclusion and accessibility principles;

- learning evidence and analytics principles;

- related files;

- versioning and maintenance.



### It should not include



- every detailed activity instruction;

- full rubrics for all tasks;

- complete reading lists if they are long;

- all prompts;

- complete banks of cases;

- all feedback templates;

- all AI agent system prompts;

- detailed analytics dashboards;

- large collections of teaching resources.



Those details should be modularized.



---



## 4. Complementary files

Every module in this section is optional. Responsibilities can be combined in a smaller arrangement. PEDAGOGY.md remains the Markdown entry point; an inventory may link to a spreadsheet or another suitable maintained format when helpful.



### 4.1 assessment.md



#### Function



`assessment.md` develops the assessment system of the course.



It expands the Assessment Design section of **PEDAGOGY.md**.



#### Recommended content



- assessment philosophy;

- assessment tasks;

- weighting;

- minimum requirements;

- assessment criteria;

- evidence of learning;

- rubrics;

- grading rules;

- reassessment rules;

- academic integrity expectations;

- AI use in assessment;

- examples of performance levels;

- moderation or review procedures.



#### Use this file when



Use `assessment.md` when assessment information is too detailed for **PEDAGOGY.md**.



For example:



> The course has several projects, each with its own rubric, minimum requirements and reassessment rules.



#### Relationship with PEDAGOGY.md



**PEDAGOGY.md** should summarize the assessment model.



`assessment.md` should contain the detailed operational assessment system.



---



### 4.2 activities.md



#### Function



`activities.md` describes the detailed learning activities of the course.



It expands the Learning Activities section of **PEDAGOGY.md**.



#### Recommended content



- task descriptions;

- activity sequence;

- weekly activities;

- instructions for students;

- timing;

- grouping;

- required resources;

- expected outputs;

- submission rules;

- relation to learning outcomes;

- relation to assessment;

- teacher notes;

- AI use rules for each activity.



#### Use this file when



Use `activities.md` when the course has many activities or a structured activity code such as:



```text

T → TP → PS → Prj

```



or:



```text

Lecture → Practice → Project → Reflection

```



#### Relationship with PEDAGOGY.md



**PEDAGOGY.md** should describe the activity ecosystem.



`activities.md` may maintain an inventory that points to detailed instructions rather than duplicating them.

#### Internal design and learner instructions

An internal activity record can hold identifiers, content anchors, learning outcomes, method, evidence, resources, case references, timing, criteria and AI conditions as needed. The learner-facing sheet should explain purpose, task, product, criteria and relevant conditions clearly. It does not need to display every internal field. A worksheet and its design inventory are complementary views.

AI acknowledgements may record purpose, use, tool and the learner's checks or changes. Permissions remain a teacher-defined decision for the course and activity. Ant's TP/P labels, rubric scales and worksheet layout are examples, not universal requirements.



---



### 4.3 content.md



#### Function



`content.md` organizes the conceptual and resource structure of the course.



It expands the Content Organization section of **PEDAGOGY.md**.



#### Recommended content



- topics;

- conceptual blocks;

- stable conceptual architecture and dependencies;

- edition-specific teaching route, where relevant;

- key concepts;

- threshold concepts;

- required readings;

- recommended readings;

- multimedia resources;

- links;

- bibliography;

- relation between contents and outcomes;

- relation between contents and activities;

- update notes.



#### Use this file when



Use `content.md` when the course has many topics, readings, resources or conceptual blocks.



#### Relationship with PEDAGOGY.md



**PEDAGOGY.md** should define the conceptual structure.



`content.md` should maintain the content map. A chapter or topic has a stable identity independent of the week in which it is taught. Sessions may select, combine and revisit content; record specific correspondences when they help planning and maintenance. Book chapters, slides and activities can serve different functions while remaining aligned.

Where an ontology is adopted, content materials develop disciplinary meaning and the ontology organizes concept identities and relationships. It should point to the developed meaning rather than establish a competing syllabus.



---



### 4.4 ai-policy.md



#### Function



`ai-policy.md` defines the detailed AI use policy of the course.



It expands the AI Use Policy section of **PEDAGOGY.md**.



#### Recommended content



- general AI policy;

- allowed uses;

- recommended uses;

- restricted uses;

- prohibited uses;

- AI use by students;

- AI use by teachers;

- AI use in assessment;

- AI use in feedback;

- transparency rules;

- citation or acknowledgement rules;

- privacy requirements;

- academic integrity rules;

- examples of acceptable and unacceptable use;

- consequences of misuse.



#### Use this file when



Use `ai-policy.md` when AI use is relevant to the course or when students are allowed to use generative AI in learning or assessment tasks.



#### Relationship with PEDAGOGY.md



**PEDAGOGY.md** should define the general AI policy.



`ai-policy.md` should define the detailed rules and examples.



---



### 4.5 feedback.md



#### Function



`feedback.md` defines the feedback model in detail.



It expands the Feedback Model section of **PEDAGOGY.md**.



#### Recommended content



- feedback principles;

- feedback tone;

- feedback timing;

- feedback depth;

- feedback structure;

- teacher feedback templates;

- peer feedback templates;

- self-assessment prompts;

- AI-assisted feedback rules;

- examples of good feedback;

- examples of poor feedback;

- feedforward strategies;

- escalation rules.



#### Use this file when



Use `feedback.md` when feedback is central to the course or when an AI assistant will provide formative feedback.



#### Relationship with PEDAGOGY.md



**PEDAGOGY.md** should define the feedback model.



`feedback.md` should provide examples, templates and operational guidance.



---



### 4.6 cases.md



#### Function



`cases.md` collects case studies, problems, simulations or scenarios used in the course.



#### Recommended content



- case title;

- context;

- actors;

- problem or dilemma;

- available information;

- guiding questions;

- expected analysis;

- possible variants;

- difficulty level;

- relation to learning outcomes;

- relation to assessment;

- teacher notes;

- AI use rules.



#### Use this file when



Use `cases.md` when the course uses case-based learning, problem-based learning, simulations or professional scenarios.



#### Relationship with PEDAGOGY.md



**PEDAGOGY.md** should describe the role of cases in the methodology.



`cases.md` may define the shared design, narrative rules, scaffolding and use of persistent scenarios, with individual cases in `cases/` or in the same file. Distinguish a case from the activities that use it. A scenario can be revisited to describe, interpret, diagnose or plan as learners develop their understanding. Record what is given, whose perspective is represented and what is an interpretation.

A small example or one-off case can remain inside an activity. Adopt a separate case system only when it serves the course. Ant uses four persistent schools; the ICT configuration intentionally omits this module.



---



### 4.7 analytics.md



#### Function



`analytics.md` defines how learning evidence may be collected, interpreted and used.



It expands the Learning Evidence and Analytics section of **PEDAGOGY.md**.



#### Recommended content



- evidence of learning;

- observable indicators;

- data sources;

- LMS data;

- activity data;

- assessment data;

- feedback data;

- AI interaction data;

- interpretation rules;

- interpretation cautions;

- privacy limits;

- human oversight requirements;

- use of analytics for teaching improvement;

- use of analytics for learner support.



#### Use this file when



Use `analytics.md` when the course uses learning analytics, LMS data, AI interaction data or systematic evidence for teaching improvement.



#### Relationship with PEDAGOGY.md



**PEDAGOGY.md** should define the principles.



`analytics.md` should define the operational data model and interpretation rules.



---



### 4.8 ethics.md



#### Function



`ethics.md` develops the ethical principles and boundaries of the course.



#### Recommended content



- privacy;

- transparency;

- academic integrity;

- bias;

- fairness;

- accessibility;

- inclusion;

- human oversight;

- data minimization;

- responsible AI use;

- protection of vulnerable learners;

- limits of automation;

- institutional compliance.



#### Use this file when



Use `ethics.md` when the course involves AI, student data, analytics, external platforms, sensitive contexts or high-stakes assessment.



#### Relationship with PEDAGOGY.md



**PEDAGOGY.md** should define ethical constraints at a general level.



`ethics.md` should provide detailed governance principles.



---



### 4.9 ontology.md

An optional ontology maintains concept identities, preferred terms, access definitions, relationships and locations in the learning materials. It can help keep teaching materials and AI context conceptually aligned, including when teachers do not consult its entries directly.

Use a vocabulary proportionate to the course. See the [ontology guide](ontology.md) for a minimal record, maintenance rules and a small example. A course may omit this module entirely.

---

## 5. Folders



### 5.1 rubrics/



#### Function



The `rubrics/` folder stores specific rubrics.



#### Recommended contents



```text

rubrics/

├── project-1-rubric.md

├── project-2-rubric.md

├── presentation-rubric.md

├── exam-rubric.md

└── participation-rubric.md

```



#### Use this folder when



Use `rubrics/` when the course has several tasks, products or competences assessed through specific rubrics.



#### Relationship with PEDAGOGY.md



**PEDAGOGY.md** defines the general quality criteria.



`rubrics/` contains task-specific rubrics.



---



### 5.2 resources/



#### Function



The `resources/` folder stores teaching and learning resources.



#### Recommended contents



```text

resources/

├── readings.md

├── links.md

├── bibliography.md

├── slides/

├── worksheets/

├── examples/

└── datasets/

```



#### Use this folder when



Use `resources/` when the course uses multiple documents, links, readings, slides, tools or examples.



#### Relationship with PEDAGOGY.md



**PEDAGOGY.md** identifies the role of resources.



`resources/` stores or references them.



---



#### Resource inventory and justified uses

Where an inventory is useful, keep one identity per source and record its different uses as separate relationships. A compact record can contain an identifier, reference or link, access conditions, pedagogical contribution and relevant review information. Add source type, license or other metadata when it serves a real need.

Distinguish source identity, pedagogical relevance and currency checks. Review requirements depend on source type: legislation and live institutional pages need different checks from a theoretical book. A structurally valid inventory does not establish that every claim in a source is correct or that a legal reference remains current.

| Source | Target | Function | Justification |
|---|---|---|---|
| Local resource ID | Topic, concept or activity ID | Grounds, illustrates, contextualizes or regulates | Why the source serves this specific target |

Use stable identifiers when reuse warrants them; a tiny collection may need only a short table. Ant's large spreadsheet is an example of an extended implementation.

---

### 5.3 prompts/



#### Function



The `prompts/` folder stores reusable prompts.



#### Recommended contents



```text

prompts/

├── teacher-prompts.md

├── student-prompts.md

├── activity-prompts.md

├── feedback-prompts.md

├── assessment-prompts.md

└── reflection-prompts.md

```



#### Use this folder when



Use `prompts/` when teachers or students repeatedly use AI for similar tasks.



#### Relationship with PEDAGOGY.md



**PEDAGOGY.md** defines the pedagogical and ethical boundaries.



`prompts/` operationalizes recurring AI-supported tasks.



---



### 5.4 agents/



#### Function



The `agents/` folder describes course-specific AI agents.



#### Recommended contents



```text

agents/

├── tutor-agent.md

├── feedback-agent.md

├── activity-generator-agent.md

├── case-simulator-agent.md

└── assessment-support-agent.md

```



#### Use this folder when



Use `agents/` when the course uses different AI assistants with different roles.



#### Relationship with PEDAGOGY.md



**PEDAGOGY.md** defines the general AI agent behaviour.



`agents/` specifies individual agents.



---



### 5.5 skills/



#### Function



The `skills/` folder defines specific actions that an AI system can execute within the pedagogical boundaries of the course.



#### Recommended contents



```text

skills/

├── generate-case.md

├── review-draft.md

├── create-rubric.md

├── adapt-explanation.md

├── generate-quiz.md

└── provide-feedback.md

```



#### Use this folder when



Use `skills/` when the course has recurring AI-supported workflows.



#### Relationship with PEDAGOGY.md



**PEDAGOGY.md** defines the context.



`skills/` defines executable actions based on that context.



---



## 6. What belongs in PEDAGOGY.md?



Keep information in **PEDAGOGY.md** when it is:



- central to the course identity;

- stable across most of the course;

- necessary for understanding the pedagogical logic;

- relevant to multiple activities or resources;

- needed by AI systems as core context;

- useful for alignment between outcomes, activities, assessment and feedback.



Examples:



- The course follows a case-based methodology.

- Feedback should be formative, specific and improvement-oriented.

- AI may be used for brainstorming and revision, but not to complete assessable work.

- Students are future teachers with limited prior knowledge of school organization.



---



## 7. What should move to complementary files?



Move information to complementary files when it is:



- too detailed;

- frequently updated;

- task-specific;

- resource-heavy;

- only relevant to one activity;

- better represented as a table, rubric or bank;

- likely to distract from the core pedagogical logic.



Examples:



- A full 20-item rubric for Project 2.

- A complete list of weekly readings.

- A bank of 15 case studies.

- Detailed prompts for student use.

- A full AI agent system prompt.

- Step-by-step instructions for a single practical task.



---



## 8. Decision rule



Use this decision rule:



> If the information defines the course logic, keep it in **PEDAGOGY.md**.

> If the information operationalizes one part of the course in detail, move it to a complementary file.



Examples:



| Information | Location |
|---|---|
| The course uses project-based learning | `PEDAGOGY.md` |
| Full instructions for Project 1 | `activities.md` |
| General assessment model | `PEDAGOGY.md` |
| Rubric for Project 1 | `rubrics/project-1-rubric.md` |
| General AI use policy | `PEDAGOGY.md` |
| Task-specific AI use examples | `ai-policy.md` |
| Feedback principles | `PEDAGOGY.md` |
| Feedback templates | `feedback.md` |
| Role of cases in the course | `PEDAGOGY.md` |
| Full case bank | `cases.md` |
| General analytics principles | `PEDAGOGY.md` |
| Detailed data indicators | `analytics.md` |



---



## 9. Minimal course implementation

The structure below is sufficient when the relevant design is clear. The README is optional; the course-level PEDAGOGY.md can be the only file.



A minimal implementation may include only:



```text

course-name/

├── PEDAGOGY.md

└── README.md

```



This is enough when:



- the course is simple;

- there are few activities;

- assessment is straightforward;

- no AI agent is being configured;

- the teacher wants an initial structured description.



---



## 10. Recommended course implementation

This is an illustrative selection for a course with several documentation needs. It is not a set of required directories and may be reduced or combined.



A recommended implementation includes:



```text

course-name/

├── PEDAGOGY.md

├── assessment.md

├── activities.md

├── content.md

├── ai-policy.md

├── feedback.md

├── rubrics/

└── resources/

```



This is suitable when:



- the course has several activities;

- assessment has multiple components;

- students use AI;

- feedback is important;

- the course has many readings or resources;

- the teaching team wants maintainable documentation.



---



## 11. Advanced course implementation

This is one possible larger arrangement. Advanced depth does not require this many files, or the adoption of cases, analytics, agents or an ontology when they do not serve the course.



An advanced implementation includes:



```text

course-name/

├── PEDAGOGY.md

├── assessment.md

├── activities.md

├── content.md

├── ai-policy.md

├── feedback.md

├── cases.md

├── analytics.md

├── ethics.md

├── rubrics/

├── resources/

├── prompts/

├── agents/

└── skills/

```



This is suitable when:



- the course uses AI assistants;

- there are multiple agents or workflows;

- learning analytics are used;

- case-based learning is central;

- assessment is complex;

- there are several teachers;

- the course is reused across editions;

- documentation needs to be versioned.



---



## 12. Example: university course with AI assistant

This configuration intentionally omits a persistent case module. Scenarios embedded in individual exercises may still be useful. See the [ICT course example](../examples/ict-primary-education.md).



Example structure:



```text

ict-primary-education/

│

├── PEDAGOGY.md

├── assessment.md

├── activities.md

├── ai-policy.md

├── feedback.md

│

├── rubrics/

│   ├── self-training-rubric.md

│   ├── techno-pedagogical-design-rubric.md

│   └── playlab-rubric.md

│

├── resources/

│   ├── digcomp.md

│   ├── digcompedu.md

│   ├── tpack.md

│   └── digital-wellbeing.md

│

├── agents/

│   ├── ict-tutor-agent.md

│   └── playlab-feedback-agent.md

│

└── prompts/

    ├── student-reflection-prompts.md

    └── project-feedback-prompts.md

```



In this example:



- `PEDAGOGY.md` defines the overall pedagogical logic.

- `assessment.md` explains the grading system.

- `activities.md` contains TP, PS and project instructions.

- `ai-policy.md` defines AI use in projects and assessment.

- `feedback.md` defines formative feedback rules.

- `rubrics/` stores project rubrics.

- `resources/` stores frameworks and readings.

- `agents/` defines course-specific AI assistants.

- `prompts/` stores reusable prompts.



---



## 13. Example: school organization course with cases

This configuration adopts persistent scenarios to support repeated organizational analysis. See the [Ant_26.27 example](../examples/school-organization.md), including its ontology and development state. Other courses do not need to copy it.



Example structure:



```text

school-organization/

│

├── PEDAGOGY.md

├── assessment.md

├── activities.md

├── content.md

├── cases.md

├── feedback.md

│

├── rubrics/

│   ├── interview-project-rubric.md

│   └── strategic-plan-rubric.md

│

├── resources/

│   ├── legislation.md

│   ├── institutional-documents.md

│   └── readings.md

│

└── agents/

    ├── conceptual-tutor-agent.md

    ├── case-analysis-agent.md

    └── feedback-agent.md

```



In this example:



- `PEDAGOGY.md` defines the course logic.

- `cases.md` stores fictional school cases.

- `activities.md` stores theoretical-practical exercises and practical sessions.

- `content.md` organizes theory and institutional documents.

- `feedback.md` guides teacher and AI-assisted feedback.

- `agents/` defines assistants for conceptual tutoring, case analysis and formative feedback.



---



## 14. Versioning across files

### Module register and development states

Maintain a concise register in the course-level PEDAGOGY.md when complementary modules are adopted. For each adopted module, record its location, function, state and version; add alignment and dependencies where useful. A single-file course can simply state its arrangement.

| Selection state | Meaning |
|---|---|
| Adopted | Included in this implementation; also record its development state. |
| Explicitly planned | The teacher intends to develop it and has recorded that intention. |
| Not adopted or not applicable | Valid local selection; not automatically missing or pending. |
| Retired or replaced | No longer used; preserve history when references depend on it. |

For adopted material, distinguish a draft, a teacher-approved design, use in teaching and evaluated results where relevant. Teacher approval of a design is not evidence of its educational effects. There is no need to list every option that is not adopted.

### Identifiers and change propagation

Use identifiers when they help reuse or relationships. Preserve identities across timetable changes, and do not reuse retired IDs. Record mergers, splits and replacements with their history. Ant's codes are one local convention, not a required schema.

Before changing a shared concept, criterion, source or architectural decision, identify the related materials. Keep editorial adjustments local when appropriate; update dependent modules when the change affects them. A newer timestamp alone does not establish an approved decision.



When complementary files are used, versioning should remain consistent.



Recommended rule:



> **PEDAGOGY.md** defines the course-level version.

> Complementary files may have their own local version numbers, but they should state which version of **PEDAGOGY.md** they are aligned with.



Example:



```markdown

# PEDAGOGY.md



- Version: 1.0

- Course edition: 2026/2027

- Last updated: 2026-06-26

```



```markdown

# assessment.md



- Version: 1.0

- Aligned with: PEDAGOGY.md v1.0

- Last updated: 2026-06-26

```



This makes it easier to know whether a rubric, activity file or AI agent specification is aligned with the current course design.



---



## 15. AI use across the file ecosystem



When an AI system uses the file ecosystem, it should follow this order:



1. Read **PEDAGOGY.md** first.

2. Identify the relevant task.

3. Read the actual module register and identify the relevant adopted files. Do not assume every illustrated option exists.

4. Use the complementary file only for the specific detail needed.

5. Apply the following authority rule:

   - **PEDAGOGY.md** is authoritative for the overall pedagogical logic.

   - Complementary files are authoritative for detailed operational information within their domain when they are current and aligned with **PEDAGOGY.md**.

6. If a contradiction appears, check version dates and file responsibilities.

7. If the contradiction affects the core course logic, update **PEDAGOGY.md**.

8. If the contradiction affects only operational detail, update the relevant complementary file.

9. If contradictions remain, ask the teacher or maintainer for clarification.



Example:



A user asks the AI to give feedback on Project 2.



When the relevant files exist and are adopted, the AI should read:



1. `PEDAGOGY.md`

2. `feedback.md`

3. `assessment.md`

4. `rubrics/project-2-rubric.md`

5. `activities/project-2-instructions.md`, if available



---



## 16. Handling contradictions

Resolve contradictions within the scope of each source and the teacher's validated decisions. Check development state as well as dates. Content materials develop disciplinary meaning; an ontology provides access definitions and relationships, and a resource inventory maintains source metadata. If clarification is essential, identify the exact issue rather than treating the absence of an optional module as a contradiction.



Contradictions may appear between files.



Examples:



- `PEDAGOGY.md` says AI is prohibited in assessment, but `ai-policy.md` allows AI-assisted drafting.

- `assessment.md` gives one weighting, while `PEDAGOGY.md` gives another.

- `activities.md` lists a task that is not reflected in assessment.

- A rubric evaluates a criterion not defined in the course quality criteria.



### Recommended resolution process



1. Identify the contradiction.

2. Check version dates.

3. Check which file is intended to be authoritative for the affected domain.

4. Distinguish whether the contradiction affects:

   - the core pedagogical logic; or

   - the operational detail of one domain.

5. Prefer **PEDAGOGY.md** for core pedagogical logic.

6. Prefer the current domain-specific file for operational details, provided that it does not contradict the core logic.

7. Update **PEDAGOGY.md** if the contradiction affects the general course logic.

8. Update the complementary file if the contradiction affects only detailed implementation.

9. Document significant changes in the changelog.



### Recommended authority hierarchy



| Issue | Primary file |
|---|---|
| General course logic | `PEDAGOGY.md` |
| Detailed assessment | `assessment.md` |
| Detailed activities | `activities.md` |
| Detailed AI rules | `ai-policy.md` |
| Feedback templates | `feedback.md` |
| Case design and content | Adopted `cases.md` / `cases/` |
| Developed disciplinary meaning | Current content materials |
| Concept identities and relationships | Adopted `ontology.md` |
| Source metadata and documented uses | Adopted resource inventory |
| Rubric descriptors | `rubrics/` |
| Agent-specific behaviour | `agents/` |
| Analytics indicators | `analytics.md` |
| Ethics and governance | `ethics.md` |



---



## 17. Maintenance checklist

Apply each check only to the material the course adopts. Optional modules not adopted do not need to be created to pass this checklist.



Use this checklist when maintaining a course file ecosystem.



- [ ] `PEDAGOGY.md` is current.

- [ ] The module register reflects the actual selection and development states.
- [ ] Changes affecting related material have been propagated.
- [ ] Concept and resource identifiers preserve their history where used.

- [ ] Complementary files reference the current version of `PEDAGOGY.md`.

- [ ] Assessment information is consistent across files.

- [ ] Activity instructions match the methodology.

- [ ] Rubrics match the quality criteria.

- [ ] AI policy is consistent with assessment rules.

- [ ] Feedback templates match the feedback model.

- [ ] Cases match the intended learning outcomes.

- [ ] Agent specifications follow AI Agent Behaviour.

- [ ] Prompts follow the AI Use Policy.

- [ ] Analytics rules respect privacy and human oversight.

- [ ] Ethical constraints are visible and updated.

- [ ] Known limitations are documented.

- [ ] Changes are recorded in the changelog.



---



## 18. Summary



The **PEDAGOGY.md** ecosystem is modular.



The core principle is:



> Keep the pedagogical logic in **PEDAGOGY.md**. Move detailed operational content to complementary files.



This structure allows teachers and AI systems to work from a shared pedagogical foundation while keeping documentation clear, maintainable and reusable.

