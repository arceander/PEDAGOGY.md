\# Roadmap



This roadmap describes the planned development of \*\*PEDAGOGY.md\*\*.



\*\*PEDAGOGY.md\*\* is an open documentation standard for describing the pedagogical, methodological, assessment, organizational, ethical and AI-related design of a course, subject, module or learning experience.



The project is developed progressively. The first goal is to publish a usable v1.0 standard. Later versions will add examples, documentation, schemas, validation tools, translations and advanced AI-oriented resources.



\---



\## Current status



\*\*Current stage:\*\* v1.0 draft



\*\*Main goal:\*\* Prepare the first public GitHub release of the standard.



The current version defines:



\- the core purpose of \*\*PEDAGOGY.md\*\*;

\- the advanced 18-section structure;

\- the distinction between specification, template and examples;

\- the initial documentation ecosystem;

\- the relationship between \*\*PEDAGOGY.md\*\* and complementary files;

\- basic AI usage rules;

\- contribution and maintenance principles.



\---



\## v1.0 — First public release



\### Goal



Publish a clear, usable and coherent first version of \*\*PEDAGOGY.md\*\* as an open documentation standard.



The v1.0 release should be sufficient for teachers, teaching teams and educational technologists to understand the standard, copy the template and complete a first course-level \*\*PEDAGOGY.md\*\* file.



\### Target repository structure



```text

PEDAGOGY.md/

│

├── README.md

├── PEDAGOGY.md

├── PEDAGOGY.template.md

├── PEDAGOGY.example.md

│

├── docs/

│   ├── getting-started.md

│   ├── ai-usage.md

│   └── file-ecosystem.md

│

├── examples/

│   └── university-course.md

│

├── CONTRIBUTING.md

├── LICENSE

├── CHANGELOG.md

└── ROADMAP.md

```



\### Planned files



\#### Core files



\- `README.md`

\- `PEDAGOGY.md`

\- `PEDAGOGY.template.md`

\- `PEDAGOGY.example.md`



\#### Documentation



\- `docs/getting-started.md`

\- `docs/ai-usage.md`

\- `docs/file-ecosystem.md`



\#### Governance and maintenance



\- `CONTRIBUTING.md`

\- `LICENSE`

\- `CHANGELOG.md`

\- `ROADMAP.md`



\#### Examples



\- `examples/university-course.md`

\- Optional additional example: `examples/ict-primary-education.md`

\- Optional additional example: `examples/school-organization.md`



\### v1.0 scope



The v1.0 release includes:



\- definition of the standard;

\- rationale for its use;

\- advanced structure;

\- template for teachers;

\- at least one completed example;

\- AI usage guidance;

\- file ecosystem documentation;

\- contribution guidelines;

\- versioning roadmap.



\### Out of scope for v1.0



The following elements are not required for v1.0:



\- formal JSON schema;

\- automated validation tools;

\- full multilingual documentation;

\- LMS integration;

\- software package;

\- complete research background;

\- issue templates;

\- pull request templates;

\- advanced agent library;

\- full skill system.



These may be added in later versions.



\---



\## v1.1 — Documentation expansion



\### Goal



Improve usability for teachers and strengthen documentation.



\### Planned additions



\#### Additional documentation



\- `docs/rationale.md`

\- `docs/structure.md`

\- `docs/faq.md`

\- `docs/quality-criteria.md`

\- `docs/teacher-guide.md`



\#### Example expansion



\- `examples/primary-education.md`

\- `examples/secondary-education.md`

\- `examples/vocational-education.md`

\- `examples/higher-education.md`

\- `examples/teacher-training.md`

\- `examples/microcredential.md`



\#### Template refinement



\- Add required / recommended / advanced field labels.

\- Add short examples inside the template.

\- Create a shortened template for quick adoption.

\- Create an advanced template for AI-agent configuration.



\#### Documentation improvements



\- Add “good and weak examples” for selected fields.

\- Add completion checklist by level.

\- Add guidance for teaching teams.

\- Add guidance for updating \*\*PEDAGOGY.md\*\* across course editions.



\### Expected outcome



By v1.1, the standard should be easier to adopt by teachers who are not familiar with structured documentation or AI-supported course design.



\---



\## v1.2 — AI assistant and modular ecosystem



\### Goal



Develop the AI-oriented and modular dimensions of the standard.



\### Planned additions



\#### Complementary file drafts



\- `assessment.md`

\- `activities.md`

\- `content.md`

\- `ai-policy.md`

\- `feedback.md`

\- `cases.md`

\- `analytics.md`

\- `ethics.md`



\#### AI-oriented documentation



\- `docs/developer-guide.md`

\- `docs/agent-design.md`

\- `docs/prompting-with-PEDAGOGY.md`

\- `docs/ai-safety-and-boundaries.md`



\#### Agent examples



\- `agents/tutor-agent.md`

\- `agents/feedback-agent.md`

\- `agents/activity-generator-agent.md`

\- `agents/case-simulator-agent.md`



\#### Prompt examples



\- `prompts/teacher-prompts.md`

\- `prompts/student-prompts.md`

\- `prompts/feedback-prompts.md`

\- `prompts/assessment-prompts.md`



\### Expected outcome



By v1.2, \*\*PEDAGOGY.md\*\* should support the design of course-specific AI assistants, prompts and modular files more explicitly.



\---



\## v1.3 — Research and theoretical grounding



\### Goal



Document the research background that supports the standard.



\### Planned additions



\- `docs/research-background.md`

\- Matrix linking each \*\*PEDAGOGY.md\*\* section with literature.

\- Short research rationale for learning design.

\- Short research rationale for constructive alignment.

\- Short research rationale for feedback.

\- Short research rationale for AI agents.

\- Short research rationale for inclusion and accessibility.

\- Short research rationale for learning analytics.

\- APA 7 reference list.

\- DOI verification for scientific references.



\### Research areas to include



\- learning design;

\- instructional design;

\- constructive alignment;

\- assessment for learning;

\- formative feedback;

\- self-regulated learning;

\- universal design for learning;

\- educational AI;

\- pedagogical agents;

\- intelligent tutoring systems;

\- AI literacy;

\- learning analytics;

\- responsible AI in education.



\### Expected outcome



By v1.3, the project should have a clear research foundation suitable for academic dissemination, conference presentations or journal article development.



\---



\## v2.0 — Formal specification and validation



\### Goal



Move from documentation standard to more formal and interoperable specification.



\### Planned additions



\#### Formal schema



\- `schemas/PEDAGOGY.schema.json`

\- Required field definitions.

\- Recommended field definitions.

\- Advanced field definitions.

\- Validation examples.

\- Machine-readable metadata.



\#### Validation tools



\- Checklist-based validation.

\- Schema-based validation.

\- AI-assisted validation prompt.

\- Consistency checker between outcomes, activities, assessment and feedback.

\- Completeness checker.



\#### Interoperability



\- Export examples for LMS contexts.

\- Metadata mapping with educational standards.

\- Possible mapping with learning object metadata.

\- Possible mapping with xAPI or learning analytics contexts.

\- AI-agent configuration patterns.



\#### Advanced governance



\- `.github/ISSUE\_TEMPLATE/`

\- `.github/PULL\_REQUEST\_TEMPLATE.md`

\- `CODE\_OF\_CONDUCT.md`

\- Versioned release notes.

\- Maintainer guidelines.



\### Expected outcome



By v2.0, \*\*PEDAGOGY.md\*\* should be usable not only as a Markdown documentation standard, but also as a more formal specification that can support validation, interoperability and AI-assisted course design workflows.



\---



\## Future possibilities



The following ideas are not yet scheduled.



\### Multilingual versions



Possible translations:



\- Spanish;

\- Basque;

\- French;

\- Portuguese;

\- other languages.



Possible structure:



```text

translations/

├── es/

├── eu/

├── fr/

└── pt/

```



\### Visual tools



Possible tools:



\- visual map of the \*\*PEDAGOGY.md\*\* structure;

\- completion dashboard;

\- alignment map;

\- field dependency diagram;

\- course design canvas;

\- printable teacher worksheet.



\### LMS integration



Possible integrations:



\- Moodle/eGela course design support;

\- Canvas course planning;

\- Google Classroom planning;

\- export to LMS activity structures;

\- alignment with gradebook logic.



\### AI workflows



Possible workflows:



\- generate activities from \*\*PEDAGOGY.md\*\*;

\- generate rubrics from \*\*PEDAGOGY.md\*\*;

\- generate feedback from \*\*PEDAGOGY.md\*\*;

\- generate cases from \*\*PEDAGOGY.md\*\*;

\- audit alignment in a course;

\- create AI agents from \*\*PEDAGOGY.md\*\*;

\- create student-facing learning assistants;

\- create teacher-facing planning assistants.



\### Community examples



Possible example repository:



```text

examples/

├── primary-education/

├── secondary-education/

├── vocational-education/

├── higher-education/

├── teacher-training/

├── microcredentials/

└── online-learning/

```



\---



\## Versioning policy



The project follows a simple versioning model.



| Version | Meaning |

|---|---|

| `0.x` | Experimental drafts |

| `1.0` | First stable public version |

| `1.x` | Backward-compatible improvements |

| `2.0` | Major structural revision |



\### Patch updates



Patch updates may include:



\- typo corrections;

\- small wording improvements;

\- additional examples;

\- minor clarifications;

\- documentation fixes.



\### Minor updates



Minor updates may include:



\- new optional fields;

\- new examples;

\- new documentation files;

\- improved templates;

\- additional complementary files.



\### Major updates



Major updates may include:



\- changes to the core structure;

\- removal of sections;

\- redefinition of required fields;

\- changes to the AI interpretation model;

\- changes to the modular file ecosystem;

\- formal schema revisions.



\---



\## Release checklist



Before publishing a release, check:



\- `README.md` is up to date.

\- `PEDAGOGY.md` reflects the current standard.

\- `PEDAGOGY.template.md` matches the standard.

\- At least one `PEDAGOGY.example.md` is available.

\- Documentation files are coherent.

\- `CONTRIBUTING.md` is up to date.

\- `LICENSE` is included.

\- `CHANGELOG.md` is updated.

\- Version numbers are consistent.

\- Known limitations are documented.

\- Links between files work.

\- Examples do not include sensitive or confidential information.

\- AI guidance respects human oversight and academic integrity.

\- The repository structure is clear.



\---



\## Current priorities



The immediate priorities are:



1\. Publish the first GitHub release.

2\. Collect feedback from teachers, educational technologists and AI-in-education researchers.



\---



\## Summary



The roadmap follows a progressive development logic:



\- v1.0: usable standard and minimal documentation;

\- v1.1: teacher-facing documentation and examples;

\- v1.2: AI agents, prompts and modular files;

\- v1.3: research background;

\- v2.0: formal schema, validation and interoperability.



The project should evolve without losing its central purpose:



> To make pedagogical intent explicit, structured and actionable for human teachers and AI-supported educational systems.

