# Optional ontology module

An ontology module organizes the conceptual vocabulary of a course. It can document stable concept identities, preferred terms, definitions, relationships and locations in learning materials. Adopt it when those functions help the course; its absence is not unfinished work.

## When it can help

An ontology may help when several materials or assistants need consistent meanings, similar terms need distinguishing, or a concept develops in several places. A small vocabulary can be enough. A teacher can keep this information in PEDAGOGY.md or content notes rather than create a separate file.

The module can provide context for AI-assisted work even when the teacher does not consult individual entries directly. Its presence does not establish that the AI retrieved or applied every entry, or demonstrate improved learning or AI performance. Traceability should identify the sources actually used when that matters.

## A minimal concept record

| Field | Purpose |
|---|---|
| Identifier | Preserve concept identity across revisions and locations. |
| Preferred term | Name used consistently in the course. |
| Definition | Delimit the meaning relevant to the course. |
| Main location | Point to the material where the meaning is developed. |
| Main relationships | Make relevant distinctions, membership or dependencies explicit. |

Sources, alternative terms, category, translations, status and history can be added when needed. Identifiers are a local convention; a machine-readable schema or graph database is not required.

## Small illustrative example

The following records illustrate the format. Locations refer to a hypothetical course, not files supplied by this repository.

| Identifier | Preferred term | Definition | Main location | Main relationships |
|---|---|---|---|---|
| CON_01 | Indicator | A measure or signal used to represent a relevant aspect of a situation. | Topic 2, section 2.1 | IS DISTINGUISHED FROM evidence. |
| CON_02 | Evidence | Information used with an explicit justification to support an interpretation or decision. | Topic 2, section 2.2 | MAY USE indicators; SUPPORTS a judgement. |

Relationships should express their meaning clearly. Distinguish association, conditions and contribution from demonstrated causation. A repeated concept can retain one identity while later applications are recorded as extensions or additional locations.

## Responsibilities and authority

The course-level PEDAGOGY.md maintains general pedagogical decisions. Content materials develop disciplinary meaning. The ontology provides access definitions and relationships and should point to that developed meaning. An adopted resource inventory maintains source metadata and justified uses.

If materials diverge, identify the scope, check approved decisions and development states, and update the affected records. A more recent file is not automatically an approved change. An ontology should not establish a competing syllabus.

## Maintenance

- Compare a proposed concept with existing entries before creating another identity.
- Keep one identity for compatible reformulations and record meaningful variants.
- Distinguish homonyms or nearby concepts when their meanings differ.
- Preserve identities when the timetable or main location changes.
- Record mergers, splits, replacements and withdrawals; do not reuse retired identifiers.
- Keep uncertain definitions, unverified sources and unvalidated translations explicitly provisional.
- Review related content, activities, cases, resources or assistants when a semantic change affects them.

Lightweight checks can detect duplicate identifiers, empty definitions and missing targets. Structural checks do not validate every definition or replace disciplinary review. Legal references and live resources still need appropriate currency checks.

## Experience from Ant 26.27

The school organization implementation consolidated 555 concepts from four blocks, using unique identifiers, access definitions, sources and relationships. Connections to all activities, sessions and other products were still being integrated in the supplied documentation.

The teacher reports that the ontology was not used through direct manual consultation and considers its availability useful as context for work with AI and alignment of materials. This is perceived usefulness, not an evaluation of its effects on learning or a verification of model retrieval.

Its size is specific to that course. See the [Ant example](../examples/school-organization.md) and [file ecosystem guide](file-ecosystem.md). Neither cases nor an ontology is required in every course.

