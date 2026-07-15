\# PEDAGOGY.md



\*\*Version:\*\* 1.0  

\*\*Status:\*\* Advanced standard specification  

\*\*Authors:\*\* Arce, A., Portillo, J., \& Tejada, E.  



\*\*Citation:\*\*  

Arce, A., Portillo, J., and Tejada, E. (2026). \*PEDAGOGY.md: An open documentation standard for pedagogical design and AI-supported education\*. GitHub repository.



\---



\## 1. Definition



\*\*PEDAGOGY.md\*\* is an open documentation standard for describing the pedagogical, methodological, assessment, organizational, ethical and AI-related design of a course, subject, module or learning experience.



It is designed as the core pedagogical specification file of a learning context.



Its purpose is to make the pedagogical design of a course explicit, structured, reusable and actionable so that teachers, teaching teams, AI systems, educational assistants, learning agents, rubrics, activities, feedback processes and complementary documentation can operate coherently within the course.



\*\*PEDAGOGY.md\*\* does not replace the professional judgement of teachers. It makes that judgement more explicit, shareable and usable by educational technologies.



\---



\## 2. Purpose of the standard



The purpose of \*\*PEDAGOGY.md\*\* is to provide a structured representation of the pedagogical intent of a course.



This representation should help answer the following questions:



\- What is the course?

\- What educational context shapes it?

\- Who are the learners?

\- What are learners expected to know, understand and be able to do?

\- What pedagogical principles guide the course?

\- How are contents, activities, assessment and feedback organized?

\- What counts as quality student work?

\- What roles do teachers, learners and AI systems play?

\- What uses of AI are allowed, recommended, restricted or prohibited?

\- How should an AI assistant behave in this specific course?

\- What ethical, accessibility, privacy and institutional boundaries must be respected?

\- How should the file be maintained across course editions?



The standard is based on a simple premise:



> AI-supported education requires explicit pedagogical context.



Without such context, AI-generated outputs risk being generic, inconsistent, poorly aligned with assessment, insensitive to learner needs or disconnected from the actual teaching approach of the course.



\---



\## 3. Scope



\*\*PEDAGOGY.md\*\* can be used to describe:



\- a university course;

\- a school subject;

\- a training module;

\- a professional development programme;

\- a microcredential;

\- a blended, online or face-to-face learning experience;

\- a project-based learning sequence;

\- a teacher-designed AI-supported learning environment.



The standard can be used with or without AI.



When used without AI, it functions as a structured course design document.



When used with AI, it functions as a pedagogical context file for generating, evaluating or constraining educational outputs.



\---



\## 4. What PEDAGOGY.md is not



\*\*PEDAGOGY.md\*\* is not:



\- a conventional syllabus;

\- a complete lesson plan;

\- a list of contents only;

\- a grading spreadsheet;

\- a prompt collection;

\- a learning management system export;

\- a replacement for institutional course guides;

\- a substitute for teacher responsibility;

\- a fully automated teaching system.



It may connect with these elements, but its function is different.



\*\*PEDAGOGY.md\*\* describes the pedagogical logic that should guide them.



\---



\## 5. Design principles



The standard follows eight design principles.



\### 5.1 Pedagogical clarity



The file should make the course design explicit enough for another teacher, educational designer or AI system to understand how the course works pedagogically.



\### 5.2 Practical usability



The file should be understandable and usable by teachers without requiring advanced technical knowledge.



\### 5.3 Instructional alignment



The file should support coherence between learning outcomes, contents, activities, assessment, feedback, quality criteria and AI use.



\### 5.4 Contextualization



The file should describe the actual educational, institutional, curricular, organizational and learner context in which the course takes place.



\### 5.5 Modularity



The core file should remain manageable. More detailed information may be moved to complementary files such as `assessment.md`, `activities.md`, `ai-policy.md`, `feedback.md`, `cases.md` or `analytics.md`.



\### 5.6 AI-readability



The file should be structured in a way that allows AI systems to interpret the pedagogical context and use it to produce aligned outputs.



\### 5.7 Pedagogical traceability



Outputs generated from \*\*PEDAGOGY.md\*\* should be justifiable from the information contained in the file. The file should make it possible to explain why a given activity, rubric, explanation or feedback response is pedagogically appropriate.



\### 5.8 Ethical responsibility



The file should define boundaries related to privacy, transparency, inclusion, academic integrity, bias, learner autonomy, human oversight and responsible AI use.



\---



\## 6. File format



\*\*PEDAGOGY.md\*\* is written in Markdown.



Markdown is used because it is:



\- readable by humans;

\- easy to edit;

\- compatible with version control systems;

\- suitable for GitHub repositories;

\- interpretable by AI systems;

\- adaptable to different educational contexts;

\- easy to transform into other formats.



\### Recommended file name



```text

PEDAGOGY.md

```



\### Recommended complementary files



```text

assessment.md

activities.md

content.md

ai-policy.md

feedback.md

cases.md

analytics.md

ethics.md

```



\### Recommended folders



```text

rubrics/

resources/

skills/

prompts/

agents/

examples/

docs/

schemas/

```



\---



\## 7. Levels of completion



A \*\*PEDAGOGY.md\*\* file may be completed at three levels.



\### 7.1 Minimum level



The minimum level provides enough information to understand the basic pedagogical context of the course.



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



\### 7.2 Recommended level



The recommended level provides enough information to generate coherent teaching resources, learning activities, assessment criteria and feedback.



Recommended additional sections:



11\. Content Organization

12\. Learning Activities

13\. Quality Criteria for Student Work

14\. Roles and Responsibilities

15\. Inclusion and Accessibility



\### 7.3 Advanced level



The advanced level provides enough information to configure AI assistants, educational agents, analytics-informed support and modular documentation ecosystems.



Advanced additional sections:



16\. AI Agent Behaviour

17\. Learning Evidence and Analytics

18\. Related Files and Modular Extensions



The advanced level is the reference structure for version 1.0 of the standard.



\---



\## 8. Standard structure



The official advanced structure of \*\*PEDAGOGY.md\*\* consists of 18 sections.



\---



\### 8.1 Course Identity



\#### Purpose



Identify the course and define its basic educational scope.



\#### Fields



```markdown

\## 1. Course Identity



\- Course name:

\- Course code:

\- Educational level:

\- Programme / degree:

\- Institution:

\- Faculty / department:

\- Teacher(s):

\- Language(s):

\- Duration:

\- Credits / workload:

\- Modality:

\- Academic year / edition:

\- Short description:

```



\#### Expected content



This section should provide a concise description of the course, its institutional location and its general purpose.



\#### AI relevance



AI systems should use this section to identify the educational setting, level, language, workload and general scope of the course.



\---



\### 8.2 Educational Context



\#### Purpose



Describe the institutional, curricular and organizational context in which the course takes place.



\#### Fields



```markdown

\## 2. Educational Context



\- Programme context:

\- Curriculum requirements:

\- Institutional constraints:

\- Regulatory framework:

\- Available spaces:

\- Available digital environments:

\- Available resources:

\- Timetable or organizational constraints:

\- Coordination with other courses:

\- Relevant contextual factors:

```



\#### Expected content



This section should explain the conditions that shape the pedagogical design of the course.



\#### AI relevance



AI systems should use this section to avoid generating proposals that are incompatible with institutional, curricular, organizational or resource constraints.



\---



\### 8.3 Learner Profile



\#### Purpose



Describe the expected characteristics, needs and conditions of the learners.



\#### Fields



```markdown

\## 3. Learner Profile



\- Typical learner profile:

\- Number of learners:

\- Prior knowledge:

\- Prior skills:

\- Digital competence level:

\- Language competence:

\- Expected motivations:

\- Expected difficulties:

\- Diversity considerations:

\- Accessibility needs:

\- Common misconceptions:

\- Support needs:

```



\#### Expected content



This section should help adapt explanations, tasks, feedback, scaffolding and resources to the learners’ actual context.



\#### AI relevance



AI systems should use this section to adapt tone, depth, scaffolding, examples, accessibility and assumptions about prior knowledge.



\---



\### 8.4 Learning Outcomes and Competences



\#### Purpose



Define what learners are expected to know, understand and be able to do by the end of the course.



\#### Fields



```markdown

\## 4. Learning Outcomes and Competences



\- General competences:

\- Specific competences:

\- Learning outcomes:

\- Knowledge outcomes:

\- Skill outcomes:

\- Attitudinal / dispositional outcomes:

\- Professional or practical outcomes:

\- Minimum expected performance:

\- Advanced expected performance:

\- Relationship with curriculum requirements:

```



\#### Expected content



This section should make explicit the target learning achievements that guide teaching, activities, assessment and feedback.



\#### AI relevance



AI systems should use this section as the main reference for aligning activities, explanations, feedback, rubrics and assessment-related outputs.



\---



\### 8.5 Pedagogical Principles



\#### Purpose



State the pedagogical foundations that guide the course design.



\#### Fields



```markdown

\## 5. Pedagogical Principles



\- Core pedagogical principles:

\- Learning theory orientation:

\- Conception of learning:

\- Conception of teaching:

\- What good learning looks like in this course:

\- What good teaching looks like in this course:

\- Pedagogical priorities:

\- Pedagogical boundaries:

\- Practices to avoid:

```



\#### Expected content



This section should define the pedagogical identity of the course. It explains the rationale behind the methodological, evaluative and technological choices.



\#### AI relevance



AI systems should use this section to avoid producing outputs that are formally correct but pedagogically inconsistent with the course.



\---



\### 8.6 Methodological Approach



\#### Purpose



Describe how teaching and learning are organized in practice.



\#### Fields



```markdown

\## 6. Methodological Approach



\- Main methodologies:

\- Teaching strategies:

\- Learning strategies:

\- Typical session structure:

\- Theory-practice relationship:

\- Individual work:

\- Collaborative work:

\- Inquiry / problem-solving work:

\- Project-based work:

\- Classroom interaction:

\- Out-of-class work:

\- Use of educational technology:

\- Use of AI:

```



\#### Expected content



This section should translate the pedagogical principles into recognizable teaching and learning practices.



\#### AI relevance



AI systems should use this section to generate activities, explanations and resources that match the actual instructional approach of the course.



\---



\### 8.7 Content Organization



\#### Purpose



Describe the conceptual structure of the course.



\#### Fields



```markdown

\## 7. Content Organization



\- Main topics:

\- Conceptual blocks:

\- Sequence of contents:

\- Key concepts:

\- Threshold concepts:

\- Foundational concepts:

\- Advanced concepts:

\- Common misconceptions:

\- Required readings:

\- Recommended readings:

\- Complementary resources:

\- Relationship between contents and learning outcomes:

```



\#### Expected content



This section should provide enough conceptual orientation for an AI or teaching assistant to understand the intellectual structure of the course.



\#### AI relevance



AI systems should use this section to avoid fragmented, decontextualized or conceptually misordered explanations and resources.



\---



\### 8.8 Learning Activities



\#### Purpose



Describe the types, structure and pedagogical function of the learning activities used in the course.



\#### Fields



```markdown

\## 8. Learning Activities



\- Main activity types:

\- Individual activities:

\- Group activities:

\- Case-based activities:

\- Project-based activities:

\- Practice-based activities:

\- Reflection activities:

\- Discussion activities:

\- Creation / production activities:

\- Research or inquiry activities:

\- Typical activity structure:

\- Activity instructions style:

\- Expected student outputs:

\- Relationship with learning outcomes:

\- Relationship with assessment:

```



\#### Expected content



This section should define the activity ecosystem of the course, not necessarily every individual task.



\#### AI relevance



AI systems should use this section to generate activities that are aligned with the course methodology, learning outcomes and assessment model.



\---



\### 8.9 Assessment Design



\#### Purpose



Describe the assessment model of the course and its alignment with learning outcomes.



\#### Fields



```markdown

\## 9. Assessment Design



\- Assessment approach:

\- Formative assessment:

\- Summative assessment:

\- Diagnostic assessment:

\- Assessment tasks:

\- Weighting:

\- Minimum requirements:

\- Assessment criteria:

\- Evidence of learning:

\- Relationship with learning outcomes:

\- Relationship with activities:

\- Reassessment / recovery rules:

\- Academic integrity expectations:

\- Role of AI in assessment:

```



\#### Expected content



This section should explain how learning is evaluated and what evidence is considered valid.



\#### AI relevance



AI systems should use this section to support assessment-related tasks only within the limits defined by the teacher and institution.



\---



\### 8.10 Feedback Model



\#### Purpose



Define how feedback should be provided to learners.



\#### Fields



```markdown

\## 10. Feedback Model



\- Feedback purpose:

\- Feedback timing:

\- Feedback tone:

\- Feedback depth:

\- Feedback structure:

\- Feedback focus:

\- Task-level feedback:

\- Process-level feedback:

\- Self-regulation feedback:

\- Feedforward:

\- When to provide direct correction:

\- When to provide hints:

\- When to ask guiding questions:

\- What feedback should avoid:

\- AI feedback rules:

```



\#### Expected content



This section should guide teachers, assistants and AI systems in giving coherent, formative and pedagogically aligned feedback.



\#### AI relevance



AI systems should use this section to decide whether to correct, explain, question, scaffold, give hints, model improvement or defer to the teacher.



\---



\### 8.11 Quality Criteria for Student Work



\#### Purpose



Define what counts as quality work in the course.



\#### Fields



```markdown

\## 11. Quality Criteria for Student Work



\- General quality criteria:

\- Disciplinary quality criteria:

\- Methodological quality criteria:

\- Conceptual quality criteria:

\- Analytical quality criteria:

\- Practical quality criteria:

\- Communication quality criteria:

\- Ethical quality criteria:

\- Use of evidence:

\- Use of references:

\- Expected level of originality:

\- Common weaknesses:

\- Examples of strong work:

\- Examples of insufficient work:

```



\#### Expected content



This section should make explicit the standards used to judge student productions, beyond formal grading rubrics.



\#### AI relevance



AI systems should use this section to provide feedback, generate examples, identify weaknesses and support improvement without inventing criteria.



\---



\### 8.12 Roles and Responsibilities



\#### Purpose



Define the expected roles of teachers, learners, AI systems and other relevant actors.



\#### Fields



```markdown

\## 12. Roles and Responsibilities



\### Teacher role



\- Main responsibilities:

\- Teaching role:

\- Facilitation role:

\- Assessment role:

\- Feedback role:

\- AI supervision role:



\### Learner role



\- Main responsibilities:

\- Participation expectations:

\- Autonomy expectations:

\- Collaboration expectations:

\- Reflection expectations:

\- Responsible AI use:



\### AI role



\- Main responsibilities:

\- Support functions:

\- Tutoring functions:

\- Feedback functions:

\- Content generation functions:

\- Prohibited functions:



\### Other roles



\- Teaching assistants:

\- External collaborators:

\- Institution:

\- Families / guardians, if relevant:

```



\#### Expected content



This section should prevent role confusion and clarify what each actor may and may not do.



\#### AI relevance



AI systems should use this section to remain within their assigned role and avoid replacing responsibilities that belong to teachers, learners or institutions.



\---



\### 8.13 AI Use Policy



\#### Purpose



Define how AI may be used in the course by learners, teachers and support systems.



\#### Fields



```markdown

\## 13. AI Use Policy



\- General AI policy:

\- Allowed uses:

\- Recommended uses:

\- Restricted uses:

\- Prohibited uses:

\- AI use by learners:

\- AI use by teachers:

\- AI use in assessment:

\- AI use in feedback:

\- AI use in content creation:

\- AI use in tutoring:

\- Transparency requirements:

\- Citation / acknowledgement requirements:

\- Data privacy requirements:

\- Human responsibility:

\- Consequences of misuse:

```



\#### Expected content



This section should establish clear boundaries for responsible, transparent and pedagogically valid AI use.



\#### AI relevance



AI systems should use this section as a policy layer that constrains all AI-supported actions in the course.



\---



\### 8.14 AI Agent Behaviour



\#### Purpose



Specify how an AI assistant or educational agent should behave when operating within the course.



\#### Fields



```markdown

\## 14. AI Agent Behaviour



\- Agent role:

\- Primary purpose:

\- Permitted actions:

\- Non-permitted actions:

\- Explanation style:

\- Tone:

\- Level of detail:

\- Language policy:

\- Scaffolding strategy:

\- Hint strategy:

\- Questioning strategy:

\- Feedback strategy:

\- Adaptation to learner level:

\- Handling of uncertainty:

\- Handling of errors:

\- Handling of sensitive data:

\- Escalation to teacher:

\- Refusal rules:

\- Examples of appropriate responses:

\- Examples of inappropriate responses:

```



\#### Expected content



This section should function as the behavioural specification for AI agents connected to the course.



\#### AI relevance



AI systems should use this section as their behavioural guide when interacting with teachers, learners or other users.



\---



\### 8.15 Inclusion and Accessibility



\#### Purpose



Define how the course addresses learner diversity, accessibility and inclusive participation.



\#### Fields



```markdown

\## 15. Inclusion and Accessibility



\- Accessibility principles:

\- Universal Design for Learning considerations:

\- Multiple means of engagement:

\- Multiple means of representation:

\- Multiple means of action and expression:

\- Language accessibility:

\- Digital accessibility:

\- Cognitive accessibility:

\- Socioeconomic accessibility:

\- Cultural considerations:

\- Adaptation rules:

\- Barriers to avoid:

\- AI-supported accessibility:

\- Limits of adaptation:

```



\#### Expected content



This section should guide inclusive design without lowering essential learning expectations.



\#### AI relevance



AI systems should use this section to adapt formats, explanations and support strategies while respecting the essential requirements of the course.



\---



\### 8.16 Learning Evidence and Analytics



\#### Purpose



Define what learning evidence may be collected, interpreted and used to improve teaching and learning.



\#### Fields



```markdown

\## 16. Learning Evidence and Analytics



\- Relevant evidence of learning:

\- Observable indicators:

\- Trackable events:

\- Data sources:

\- LMS data:

\- Activity data:

\- Assessment data:

\- Feedback data:

\- Self-reflection data:

\- AI interaction data:

\- Interpretation rules:

\- Interpretation cautions:

\- Data that should not be collected:

\- Data privacy requirements:

\- Use of analytics for teaching improvement:

\- Use of analytics for learner support:

\- Human oversight:

```



\#### Expected content



This section should connect learning analytics to pedagogical intention and prevent inappropriate data interpretation.



\#### AI relevance



AI systems should use this section only within the defined limits for evidence, interpretation, privacy and human oversight.



\---



\### 8.17 Related Files and Modular Extensions



\#### Purpose



Define the relationship between \*\*PEDAGOGY.md\*\* and other complementary files.



\#### Fields



```markdown

\## 17. Related Files and Modular Extensions



\- assessment.md:

\- activities.md:

\- content.md:

\- ai-policy.md:

\- feedback.md:

\- cases.md:

\- rubrics/:

\- resources/:

\- skills/:

\- prompts/:

\- agents/:

\- analytics.md:

\- ethics.md:

\- Other related files:

```



\#### Expected content



This section should keep \*\*PEDAGOGY.md\*\* as the matrix file while allowing more detailed information to be modularized elsewhere.



\#### Recommended interpretation



\- `assessment.md` develops the assessment system of the course.

\- `activities.md` details learning activities, sequences, timings and expected outputs.

\- `content.md` organizes course topics, readings, concepts and resources.

\- `ai-policy.md` expands the rules for AI use.

\- `feedback.md` specifies feedback templates, levels, tone and examples.

\- `cases.md` collects practical cases, problems, scenarios and simulations.

\- `rubrics/` stores specific rubrics.

\- `resources/` stores teaching and learning resources.

\- `skills/` defines specific actions that an AI can execute.

\- `prompts/` stores reusable prompts.

\- `agents/` describes educational agents derived from the course design.

\- `analytics.md` defines learning evidence and interpretation rules.

\- `ethics.md` develops ethical principles and boundaries.



\#### AI relevance



AI systems should use this section to identify where more detailed information is stored and avoid overloading the core file.



\---



\### 8.18 Versioning and Maintenance



\#### Purpose



Ensure that the file remains updated, traceable and usable across course editions.



\#### Fields



```markdown

\## 18. Versioning and Maintenance



\- Version:

\- Last updated:

\- Updated by:

\- Reviewed by:

\- Course edition:

\- Change log:

\- Sections updated:

\- Reason for update:

\- Review frequency:

\- Planned next review:

\- Known limitations:

\- Pending improvements:

```



\#### Expected content



This section should document the evolution of the course design and maintain the reliability of all AI systems or materials derived from it.



\#### AI relevance



AI systems should use this section to identify whether the pedagogical specification is current, provisional, outdated or under revision.



\---



\## 9. Quality criteria for a valid PEDAGOGY.md file



A \*\*PEDAGOGY.md\*\* file should be evaluated according to the following quality criteria.



\### 9.1 Completeness



The file includes the necessary sections for its intended level of use: minimum, recommended or advanced.



\### 9.2 Coherence



The file does not contain contradictions between outcomes, methodology, assessment, feedback, AI use and learner expectations.



\### 9.3 Alignment



Learning outcomes, activities, assessment evidence, feedback criteria and quality standards are explicitly connected.



\### 9.4 Contextual adequacy



The file reflects the real institutional, curricular, learner and organizational context.



\### 9.5 Pedagogical specificity



The file avoids generic statements and provides enough detail to guide actual educational decisions.



\### 9.6 AI usability



The file contains enough structured information for AI systems to generate coherent outputs and respect pedagogical boundaries.



\### 9.7 Ethical robustness



The file defines limits related to privacy, academic integrity, transparency, inclusion, accessibility and human oversight.



\### 9.8 Maintainability



The file includes versioning information and can be updated across course editions.



\---



\## 10. Rules for AI systems using PEDAGOGY.md



An AI system using \*\*PEDAGOGY.md\*\* should follow these rules.



\### 10.1 General rules



The AI system should:



\- treat \*\*PEDAGOGY.md\*\* as the primary pedagogical context;

\- align outputs with the course identity, context, learner profile and learning outcomes;

\- respect the methodological approach and assessment design;

\- use the feedback model when providing feedback;

\- apply the quality criteria defined for student work;

\- follow the AI use policy and agent behaviour rules;

\- respect accessibility and inclusion requirements;

\- comply with privacy, transparency and human oversight constraints;

\- ask for clarification when essential pedagogical information is missing.



\### 10.2 Prohibited behaviour



The AI system should not:



\- replace teacher judgement;

\- make grading decisions unless explicitly authorized and supervised;

\- invent assessment criteria not present in the file;

\- ignore the learner profile or accessibility needs;

\- request or infer unnecessary sensitive data;

\- contradict the stated AI use policy;

\- generate outputs that undermine academic integrity;

\- act beyond the role defined for the AI agent;

\- present uncertain interpretations as facts;

\- treat analytics or interaction data as direct evidence of learning without caution.



\### 10.3 Traceability



When possible, AI-generated outputs should be traceable to specific sections of \*\*PEDAGOGY.md\*\*.



For example:



\- an activity should be traceable to learning outcomes, methodology and assessment;

\- feedback should be traceable to the feedback model and quality criteria;

\- an AI refusal should be traceable to the AI use policy or agent behaviour rules;

\- an adaptation should be traceable to the learner profile or accessibility section.



\---



\## 11. Relationship with complementary files



\*\*PEDAGOGY.md\*\* should remain the matrix file.



It should contain the core pedagogical design, but it should not contain every operational detail. When a section becomes too long or too specific, it should be moved to a complementary file and referenced from section 17.



Recommended modular logic:



| Type of information | Recommended location |

|---|---|

| Core pedagogical identity | `PEDAGOGY.md` |

| Detailed assessment system | `assessment.md` |

| Detailed activity designs | `activities.md` |

| Detailed AI policy | `ai-policy.md` |

| Feedback examples and templates | `feedback.md` |

| Case banks and simulations | `cases.md` |

| Specific rubrics | `rubrics/` |

| Teaching materials | `resources/` |

| AI actions and workflows | `skills/` |

| Reusable prompts | `prompts/` |

| Agent specifications | `agents/` |

| Analytics and evidence rules | `analytics.md` |

| Ethical governance | `ethics.md` |



\---



\## 12. Versioning



The standard follows semantic versioning principles.



Recommended version labels:



| Version | Meaning |

|---|---|

| `0.x` | Experimental versions |

| `1.0` | First stable public specification |

| `1.x` | Backward-compatible improvements |

| `2.0` | Major structural revision |



Each version of a course-level \*\*PEDAGOGY.md\*\* file should include:



\- version number;

\- last update date;

\- author or maintainer;

\- course edition;

\- sections updated;

\- reason for update;

\- known limitations;

\- pending improvements.



\---



\## 13. Recommended citation



If you use or adapt this standard, please cite it as:



> Arce, A., Portillo, J. and Tejada, E. (2026). \*PEDAGOGY.md: An open documentation standard for pedagogical design and AI-supported education\*. GitHub repository.



\---



\## 14. License



Recommended license:



\*\*Creative Commons Attribution 4.0 International — CC BY 4.0\*\*



This allows others to use, adapt and redistribute the standard, provided that appropriate credit is given.



\---



\## 15. Summary



\*\*PEDAGOGY.md\*\* is a structured standard for making pedagogical intent explicit.



Its function is to connect human pedagogical design with AI-supported educational action.



It helps ensure that educational resources, feedback, rubrics, activities, analytics and AI agents are not generated in isolation, but grounded in a coherent representation of the course.



The central aim of the standard is to make teaching design:



\- explicit;

\- structured;

\- reusable;

\- aligned;

\- contextualized;

\- traceable;

\- ethically bounded;

\- usable by both humans and AI systems.

