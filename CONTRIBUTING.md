# Contributing to PEDAGOGY.md



Thank you for your interest in contributing to **PEDAGOGY.md**.



**PEDAGOGY.md** is an open documentation standard for describing the pedagogical, methodological, assessment, organizational, ethical and AI-related design of a course, subject, module or learning experience.



The goal of this project is to make pedagogical intent explicit, structured, reusable and actionable for teachers, teaching teams, educational technologists and AI systems.



---



## 1. What kinds of contributions are welcome?



Contributions may include:



- improving the core **PEDAGOGY.md** specification;

- improving `PEDAGOGY.template.md`;

- adding examples from different educational levels;

- clarifying existing sections;

- proposing new fields;

- improving documentation;

- translating documents;

- identifying ambiguities;

- suggesting links with learning design, instructional design, assessment or AI-in-education frameworks;

- proposing complementary files;

- improving AI usage guidance;

- improving ethical, accessibility or privacy guidance;

- reporting inconsistencies between files;

- suggesting better terminology.



---



## 2. Contribution principles



All contributions should preserve the following principles.



### 2.1 Pedagogical clarity



Contributions should make the course design easier to understand.



Avoid adding terminology, fields or structures that make the standard unnecessarily obscure.



### 2.2 Teacher usability



**PEDAGOGY.md** should remain usable by teachers without advanced technical knowledge.



A contribution should not make the standard depend on programming skills, specialized software or complex metadata systems unless the contribution is clearly optional or advanced.



### 2.3 Instructional alignment



Contributions should help align:



- learning outcomes;

- activities;

- assessment;

- feedback;

- quality criteria;

- AI use;

- learner support.



Avoid contributions that fragment the relationship between these elements.



### 2.4 Modularity



Not everything belongs in **PEDAGOGY.md**.



Before adding a new field or section, consider whether it should belong to:



- `PEDAGOGY.md`;

- `assessment.md`;

- `activities.md`;

- `content.md`;

- `ai-policy.md`;

- `feedback.md`;

- `cases.md`;

- `analytics.md`;

- `ethics.md`;

- `rubrics/`;

- `resources/`;

- `prompts/`;

- `agents/`;

- `skills/`.



Use this rule:



> If the information defines the core pedagogical logic, it may belong in **PEDAGOGY.md**.

> If it operationalizes a specific part of the course, it probably belongs in a complementary file.



### 2.5 AI-readability



The standard should be understandable by both humans and AI systems.



Contributions should support structured interpretation, consistency and traceability.



Avoid vague or purely decorative sections that do not help a teacher or AI system make better pedagogical decisions.



### 2.6 Ethical responsibility



Contributions should respect:



- privacy;

- transparency;

- academic integrity;

- inclusion;

- accessibility;

- fairness;

- human oversight;

- learner agency;

- responsible AI use.



Do not propose structures that promote automated high-stakes decisions without human supervision.



### 2.7 Institutional adaptability



The standard should be adaptable to different educational contexts.



Avoid assuming one specific country, institution, platform, assessment model, LMS or AI provider as universal.



---



## 3. Before proposing a change



Before opening an issue or pull request, ask:



1. What pedagogical problem does this change solve?

2. Is the change useful for teachers?

3. Is the change understandable without technical expertise?

4. Does it improve alignment, clarity or traceability?

5. Does it belong in the core **PEDAGOGY.md** file?

6. Would it be better placed in a complementary file?

7. Does it create unnecessary complexity?

8. Does it respect ethical and privacy boundaries?

9. Can it be illustrated with an example?

10. Is it compatible with the current structure of the standard?



---



## 4. How to propose a new field



If you want to propose a new field, include the following information:



### Proposed field



Name of the proposed field.



### Purpose



What pedagogical function does this field serve?



### Location



Where should it be placed?



- [ ] `PEDAGOGY.md`

- [ ] `assessment.md`

- [ ] `activities.md`

- [ ] `content.md`

- [ ] `ai-policy.md`

- [ ] `feedback.md`

- [ ] `cases.md`

- [ ] `analytics.md`

- [ ] `ethics.md`

- [ ] Other



### Completion level



- [ ] Required

- [ ] Recommended

- [ ] Advanced



### Pedagogical rationale



Why is this field needed?



### AI relevance



How would an AI system use this field?



### Example content



Provide an example of how a teacher would complete this field.



### Risks or limitations



Could this field create confusion, redundancy or excessive complexity?



---



## 5. How to propose a new section



If you want to propose a new section, explain:



- the purpose of the section;

- why existing sections are insufficient;

- what fields it would contain;

- whether it is required, recommended or advanced;

- how it supports teachers;

- how it supports AI systems;

- how it relates to existing files;

- whether it could be a complementary file instead of a core section.



A new section should not be added only because the topic is interesting. It should solve a clear pedagogical or documentation problem.



---



## 6. How to propose a complementary file



If you want to propose a new complementary file, include:



### Proposed file



Name of the file.



### Function



What does this file do?



### Relationship with PEDAGOGY.md



Which section of **PEDAGOGY.md** does it expand?



### Recommended contents



List the main sections or fields.



### Example use case



Describe when a teacher would use this file.



### AI relevance



How would an AI system use this file?



Examples of possible complementary files:



- `assessment.md`;

- `activities.md`;

- `content.md`;

- `ai-policy.md`;

- `feedback.md`;

- `cases.md`;

- `analytics.md`;

- `ethics.md`;

- `teacher-guide.md`;

- `developer-guide.md`.



---



## 7. How to contribute an example



Examples are especially valuable.



An example should show how **PEDAGOGY.md** can be completed in a specific educational context.



Examples may represent:



- primary education;

- secondary education;

- vocational education and training;

- higher education;

- teacher education;

- online learning;

- blended learning;

- microcredentials;

- professional training;

- AI-supported courses.



### Example requirements



A good example should:



- be realistic;

- be complete enough to be useful;

- avoid unnecessary personal data;

- avoid identifying real students;

- avoid confidential institutional information;

- show alignment between outcomes, methodology, assessment and feedback;

- include an AI use policy if AI is relevant;

- include versioning information.



### Recommended file location



Examples should usually be placed in:



```text

examples/

```



Recommended naming:



```text

examples/university-course.md

examples/primary-education.md

examples/teacher-training.md

```



---



## 8. How to contribute documentation



Documentation contributions may include:



- clearer explanations;

- better examples;

- improved tables;

- FAQ entries;

- teacher guidance;

- AI usage guidance;

- file ecosystem explanations;

- research background;

- translations.



Documentation should be concise, readable and directly useful.



Avoid turning documentation into a theoretical essay unless the file is explicitly intended as research background.



---



## 9. Style guidelines



Use clear Markdown.



Recommended style:



- use descriptive headings;

- use short paragraphs;

- use lists for fields;

- use tables when comparing files or levels;

- use examples where useful;

- avoid unnecessary jargon;

- define technical terms;

- write for teachers first;

- keep AI-related guidance explicit and operational.



Avoid:



- overly abstract language;

- unexplained acronyms;

- platform-specific assumptions;

- excessive technical metadata;

- duplicated content;

- very long sections without structure.



---



## 10. Language



The main repository language is English.



Translations may be added in separate files or folders.



Recommended translation structure:



```text

translations/

├── es/

│   ├── README.md

│   ├── PEDAGOGY.template.md

│   └── getting-started.md

├── eu/

│   ├── README.md

│   ├── PEDAGOGY.template.md

│   └── getting-started.md

```



Translations should preserve the meaning of the standard, not only translate the words.



---



## 11. Ethical and privacy requirements



Do not include:



- identifiable student data;

- sensitive personal information;

- confidential school data;

- private assessment records;

- unpublished institutional documents without permission;

- AI interaction logs containing personal data;

- examples that expose real learners, families or teachers.



When using examples, anonymize or fictionalize details.



---



## 12. Pull request process



When submitting a pull request:



1. Describe the change clearly.

2. Explain the pedagogical problem it solves.

3. Identify the affected file or section.

4. Explain whether the change affects the core standard or a complementary file.

5. Include examples if the change introduces a new field or section.

6. Check for consistency with existing documentation.

7. Update `CHANGELOG.md` if the change is significant.

8. Update `ROADMAP.md` if the change affects planned development.



---



## 13. Pull request checklist



Before submitting a pull request, check:



- The change is understandable for non-technical teachers.

- The change improves pedagogical clarity.

- The change supports instructional alignment.

- The change preserves modularity.

- The change is relevant for AI-supported educational use.

- The change respects privacy and ethical boundaries.

- The change does not duplicate information already present elsewhere.

- The change includes an example when needed.

- The change is consistent with the current version of the standard.

- The change does not make the core file unnecessarily complex.



---



## 14. Issue types



Use issues to report problems or propose changes.



### 14.1 Ambiguity or inconsistency



Use this when a field, section or document is unclear or contradictory.



Include:



- affected file;

- affected section;

- description of the ambiguity;

- proposed clarification, if available.



### 14.2 New field proposal



Use this when proposing a new field.



Include:



- field name;

- pedagogical purpose;

- proposed location;

- completion level;

- AI relevance;

- example content.



### 14.3 New example



Use this when contributing a completed example.



Include:



- educational level;

- course type;

- language;

- whether the example is real, anonymized or fictional;

- what the example demonstrates.



### 14.4 Documentation improvement



Use this when improving explanation, wording, structure or usability.



Include:



- affected document;

- current problem;

- proposed improvement.



### 14.5 Ethical or AI policy concern



Use this when a part of the standard may create risks related to AI use, privacy, academic integrity, accessibility or human oversight.



Include:



- risk description;

- affected section;

- proposed mitigation.



---



## 15. Versioning



The project uses versioning to track changes.



Recommended version logic:



| Version | Meaning |

|---|---|

| `0.x` | Experimental drafts |

| `1.0` | First stable public specification |

| `1.x` | Backward-compatible improvements |

| `2.0` | Major structural revision |



Changes to the core structure of **PEDAGOGY.md** should be documented carefully.



Examples of major changes:



- adding or removing a core section;

- redefining required fields;

- changing the completion levels;

- changing the AI interpretation rules;

- changing the modular file ecosystem.



---



## 16. Decision criteria for maintainers



Maintainers should evaluate contributions according to:



| Criterion | Guiding question |

|---|---|

| Pedagogical value | Does this improve course design documentation? |

| Teacher usability | Can teachers understand and use it? |

| AI relevance | Does it help AI systems act more coherently? |

| Modularity | Is this in the right file? |

| Ethical robustness | Does it respect privacy, fairness and human oversight? |

| Interoperability | Can it work across contexts and platforms? |

| Maintainability | Will it remain manageable over time? |



---



## 17. Citation



If you use or adapt **PEDAGOGY.md**, please cite the project as:



> Arce, A., Portillo, J. and Tejada, E. (2026). *PEDAGOGY.md: An open documentation standard for pedagogical design and AI-supported education*. GitHub repository.



---



## 18. Summary



Good contributions to **PEDAGOGY.md** should make pedagogical intent more explicit, structured, reusable and actionable.



The project should remain:



- clear for teachers;

- rigorous in pedagogical terms;

- modular in structure;

- useful for AI-supported education;

- ethically responsible;

- adaptable across institutions and educational levels.

