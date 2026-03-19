---
name: gstu-gost
description: Use when the user asks to write, edit, structure, or format a report, practice report, explanatory note, diploma-like text, or other academic document according to GSTU requirements, GSTU GOST rules, or the local methodical guide. Trigger especially on phrases like "по ГОСТам ГГТУ", "по требованиям ГГТУ", "оформи по ГГТУ", or requests for GSTU-specific bibliography, appendices, figures, tables, and page layout.
---

# GSTU GOST

## When to use

- Draft any academic report or similar document according to GSTU GOST rules.
- Build or fix the structure of a report section by section.
- Rewrite informal or weak text into formal academic Russian.
- Apply formatting and bibliography rules from `references/gost-summary.md`.
- Prepare appendices, source lists, figure captions, table titles, and references.

## Quick start

1. Read `references/gost-summary.md` when formatting, citations, appendices, figures, tables, or page layout matter.
2. Collect the minimum missing inputs before drafting.
3. If the user has a faculty template or separate practice-methodical guide, follow that document over this skill where they conflict.
4. If the user asks for writing "по ГОСТам ГГТУ", interpret that as a direct instruction to apply the rules summarized in `references/gost-summary.md`.
5. If there is no separate document-specific guide, use the formatting rules from the diploma guide and adapt the structure to the requested document type.
6. Write in neutral academic Russian with clear logic, explicit transitions, and no colloquial phrasing.

## Required inputs

Ask only for what is truly missing. Prefer this intake set:

- University, faculty, department, specialty, group.
- Full student name.
- Practice type and exact title of the report.
- Practice base or organization.
- Practice dates.
- Supervisor name and position.
- Individual assignment or goals of practice.
- What was actually done during practice.
- Technologies, tools, and artifacts created.
- Required structure from the department, if it exists.
- List of sources already used.

If the user does not have some of these yet, draft with explicit placeholders like `{{организация практики}}` and continue.

## Recommended workflow

### 1. Determine the task mode

- Full report from scratch.
- One section or subsection.
- Academic rewrite of existing text.
- Formatting and compliance pass.
- Bibliography or appendices pass.

### 2. Build the report structure

Use the department template if available. Otherwise, adapt the structure to the requested GSTU document type. For a report, the following safe default structure is suitable:

1. Title page.
2. Assignment or individual task, if required by the department.
3. Contents.
4. List of symbols and abbreviations, if needed.
5. Introduction.
6. General characteristics of the practice base or project context.
7. Analysis of the subject area, tools, processes, or existing solutions.
8. Description of completed work during practice.
9. Results, testing, evaluation, or implementation outcomes.
10. Occupational safety, economics, or energy/resource saving sections if explicitly required.
11. Conclusion.
12. List of used sources.
13. Appendices.

### 3. Write in academic style

- Use formal, objective phrasing.
- Keep paragraphs logically focused.
- Prefer cause-effect and problem-solution transitions.
- Avoid conversational language, unsupported claims, and filler.
- Use precise terms consistently.
- When stating mandatory rules, use wording like `следует`, `необходимо`, `должен`.
- When describing completed work, use restrained formulations such as `в ходе практики были выполнены`, `проведен анализ`, `разработан`, `реализован`, `получены результаты`.

### 4. Apply formatting rules

Always normalize the draft against `references/gost-summary.md`:

- Page setup and pagination.
- Headings and numbering.
- Figures, tables, formulas, and appendices.
- Source list and in-text citations.
- Program code placement in appendices.

### 5. Run the final check

- Every section is present and titled consistently.
- All figures, tables, formulas, and appendices are referenced in text.
- The bibliography contains only cited sources.
- Internet sources are official when possible.
- No colloquial phrases, duplicate claims, or abrupt section endings remain.

## Academic writing patterns

Use patterns like:

- `Актуальность темы обусловлена...`
- `В ходе выполнения работы была поставлена задача...`
- `Для достижения поставленной цели необходимо решить следующие задачи...`
- `В рамках выполненной работы был проведен анализ...`
- `На основании проведенного исследования можно сделать вывод...`
- `Практическая значимость результатов заключается в...`

Avoid patterns like:

- `я сделал`
- `мне удалось`
- `классное решение`
- `удобный и простой`
- empty praise without evidence
- unsupported claims of novelty or efficiency

## Reference usage

Load `references/gost-summary.md` when:

- the user asks for GOST requirements;
- you need formatting values or citation rules;
- you need to justify a structural or layout choice;
- you are checking whether a draft complies with the local methodical guide.

## Important note

This skill is based on the local file `Оформление дипломных работ.pdf`, which is a diploma-work guide. Its formatting and citation rules are treated here as the working GSTU ruleset. If the user says "по ГОСТам ГГТУ", apply this ruleset by default. If the user later provides a narrower faculty, department, or document-specific guide, that guide overrides the inferred structure here.
