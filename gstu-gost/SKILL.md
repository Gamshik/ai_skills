---
name: gstu-gost
description: Use when the user asks to write, edit, structure, or format a diploma work, report, practice report, explanatory note, bibliography, appendix, presentation outline, or academic text according to GSTU requirements, GSTU GOST rules, or the local GSTU methodical guide. Trigger especially on phrases like "по ГОСТам ГГТУ", "по требованиям ГГТУ", "оформи по ГГТУ", "диплом ГГТУ", "пояснительная записка", or requests for GSTU-specific sources, figures, tables, formulas, appendices, page layout, and academic Russian.
---

# GSTU GOST

## Operating Principle

This skill must be usable on its own for ordinary GSTU diploma/report drafting and formatting. Use the rules below directly. Open `references/gost-summary.md` only when a task needs deeper detail, exact examples, or a compliance audit beyond the condensed rules here.

If the user provides a department template, supervisor requirement, assignment sheet, or newer methodical guide, follow that document where it conflicts with this skill.

## When To Use

- Draft or revise a diploma work, practice report, course report, explanatory note, abstract, resume, presentation outline, bibliography, appendix, or manual according to GSTU rules.
- Rewrite informal text into formal academic Russian.
- Check document structure, headings, pagination, figures, tables, formulas, sources, references, program-code appendices, or defense materials.
- Prepare GSTU-specific sections such as economic justification, occupational safety, resource and energy saving, software architecture, testing, and user/programmer manuals.

## Minimum Intake

Ask only for what is needed for the current task. Use placeholders like `{{кафедра}}` and continue if data is missing.

- Document type: diploma work, practice report, course work, explanatory note, or another report.
- University, faculty, department, specialty, group.
- Full student name.
- Exact approved topic/title. For diploma work, do not rewrite an approved title unless the user asks for title selection help.
- Supervisor name and position; consultant names and sections when required.
- Practice base, organization, dates, individual assignment, or project context when relevant.
- What was actually done, technologies used, artifacts created, tests/results obtained.
- Department-required structure, if provided.
- Sources already used and citation order, if known.
- Originality/anti-plagiarism data when preparing the diploma abstract.

## Task Modes

- Full diploma/report from scratch.
- One section or subsection.
- Academic rewrite of existing text.
- Formatting and compliance pass.
- Bibliography, citation, figure, table, formula, or appendix pass.
- Defense materials: abstract, resume, presentation outline, review response, system programmer manual, programmer manual, or user manual.

## Diploma Topic Rules

- The topic should be one sentence and reasonably short.
- The approved topic must be reproduced exactly.
- Avoid punctuation marks in the topic: commas, colons, brackets, and similar marks.
- Prefer starting with the developed system/product type: `система`, `подсистема`, `автоматизированная система`, `программа`, `программный комплекс`, `программный модуль`, `веб-узел`.
- Do not use `метод`, `алгоритм`, `модель` and similar items as the development object.
- Do not start with `разработка`, `проектирование`, `решение задачи`.
- State the purpose of the developed information system or software clearly.
- Do not include foreign words, abbreviations, programming languages, DBMS names, corporate systems, technologies, or mathematical methods unless they are part of an organization name or approved title.

## Diploma Structure

For GSTU diploma work, use this order unless a department template overrides it:

1. Title page.
2. Abstract.
3. Diploma assignment.
4. Resume in Russian, Belarusian, and a foreign language, preferably English.
5. Contents.
6. List of symbols and abbreviations, if needed.
7. Introduction.
8. Section 1: task description, analytical review of existing methods and tools, analogues, advantages/disadvantages of known solutions, requirements or technical assignment.
9. Section 2: software architecture, domain model, functional requirements, data model, database structure if needed, and internal/external interfaces.
10. Section 3: software structure, implementation, main algorithms, user interface, input/output formats.
11. Section 4: testing, verification, validation, trial operation, computational experiment, and result analysis.
12. Section 5: economic justification.
13. Section 6: occupational safety.
14. Section 7: resource and energy saving.
15. Conclusion.
16. List of used sources.
17. Appendices.

Approximate diploma volumes:

- Explanatory note without appendices: at least `75-85` sheets.
- Introduction: `1-3` pages.
- Section 1: `12-15` sheets.
- Sections 2, 3, and 4: `10-12` sheets each.
- Section 5: `5-7` sheets.
- Sections 6 and 7: `3-5` sheets each.
- Conclusion: `1-2` pages.

For non-diploma reports, adapt the structure conservatively:

1. Title page.
2. Assignment or individual task, if required.
3. Contents.
4. List of symbols and abbreviations, if needed.
5. Introduction.
6. Organization/project context.
7. Subject-area, tools, process, or analogue analysis.
8. Description of completed work.
9. Results, testing, evaluation, or implementation outcomes.
10. Economics, occupational safety, or resource/energy saving only when required.
11. Conclusion.
12. List of used sources.
13. Appendices.

## Front Matter

- Title page: faculty and department names without abbreviations; topic in uppercase; title page counts in total pagination but has no visible page number.
- Abstract: not more than `1` page, recommended `1000-1200` characters. Include work volume, illustrations, tables, appendices, sources, `5-10` keywords, object, purpose, method, results/novelty, application area, implementation or practical-use proposals.
- Diploma abstract must include the originality statement: work completed independently, checked in the named anti-plagiarism system, originality percentage stated, citations linked to the source list.
- Assignment: issued by supervisor, signed by supervisor and student, approved by department head, bound into the work, counts as one sheet, no visible page number.
- Resume: Russian, Belarusian, and a foreign language, preferably English; includes topic, object and research tools, main independently obtained conclusions; all three together not more than `1` page.
- Contents: includes introduction, abbreviations list if present, sections, subsections, conclusion, source list, and appendices with starting page numbers.
- Abbreviations list starts with wording like `В настоящей пояснительной записке применяются следующие термины, обозначения и сокращения...`; Russian terms go first alphabetically, then English terms alphabetically, then other languages.

## Page Layout

- Paper: `A4`, one-sided printing. A3 is allowed for large tables/illustrations.
- Margins: top `20 mm`, bottom `20 mm`, left `30 mm`, right `10 mm`.
- Font: `Times New Roman`, `14 pt`, black.
- Line spacing: `40 +/- 3` lines per page; in Word use single spacing or multiplier `1.1`.
- Alignment: justified.
- First-line indent: `1.25 cm`.
- Automatic hyphenation is allowed in body text, not in headings.
- Page numbers: Arabic numerals, bottom right, `Times New Roman`, `12 pt`.
- Title page, abstract, assignment, resume, and first contents sheet count in pagination but have no visible number.
- Visible numbering starts from the second contents sheet, or from the abbreviations list, or from the introduction if earlier elements fit on one sheet.
- Appendices are included in common pagination.

## Typography And Language

- Write in formal, objective academic Russian with precise terminology and consistent terms.
- Avoid colloquial phrasing, professional slang, arbitrary word formation, unsupported claims, and filler.
- Use requirement wording such as `должен`, `следует`, `необходимо`, `требуется`, `не допускается`, `запрещается`.
- Do not use foreign terms where a Russian equivalent exists.
- Do not shorten words except by accepted rules and standards.
- Use standardized units per `ГОСТ 8.417-2002`.
- Numbers with units are written in digits; numbers from one to nine without units are written in words.
- Latin letters, variables, and symbolic designations in Russian body text are italicized. Do not automatically italicize whole English names or terms unless they function as symbols/designations.
- In formulas, Latin variables are italic; Greek symbols are upright.
- Distinguish hyphen and dash: hyphen has no surrounding spaces, dash is separated by spaces in Russian explanatory text.
- Do not use mathematical signs, the minus sign, diameter sign, `№`, or `%` without numeric values; write words in running text when no numeric value follows.
- Do not cite standards or technical documents by index without their registration number.

## Headings And Numbering

- Main text is divided into sections, subsections, and points.
- Sections use Arabic numerals without trailing dot: `1`.
- Subsections use `1.1`; points use `1.1.1`; no trailing dot.
- Sections and subsections must have headings; points usually do not.
- Section headings: uppercase, bold, from paragraph indent.
- Subsection headings: sentence case, bold, from paragraph indent.
- Point numbers: bold italic.
- No period at the end of headings, no underline, no hyphenation inside headings.
- If a heading has two sentences, separate them with a period.
- If a heading wraps, align following lines with the first letter of the first line.
- Every section starts on a new page.
- Do not leave a subsection heading at the bottom of a page without text under it.
- Do not move the last line of a section or subsection to a separate page.
- Separate headings from surrounding text with a blank line.
- If a section has subsections, do not leave body text outside subsections.
- A subsection should be about one page or more and should not contain only figures, tables, or formulas.
- Center unnumbered headings `Реферат`, `Перечень условных обозначений и сокращений`, and `Список использованных источников`; use bold.
- Use uppercase bold centered headings for `СОДЕРЖАНИЕ`, `ВВЕДЕНИЕ`, and `ЗАКЛЮЧЕНИЕ`.

## Lists

- Unnumbered list items start from paragraph indent with a dash, start with a lowercase letter, and end with a semicolon except the final item.
- Referenced list items use lowercase Russian or Latin letters with a closing parenthesis: `а)`, `б)`, `в)`.
- Deeper detail uses Arabic numerals with a closing parenthesis: `1)`, `2)`.
- A list item should not contain several independent sentences separated by periods.
- In text references, write `в пункте б` or `в пункте б.3`, omitting the closing parenthesis.

## Figures

- Place each figure immediately after the first textual reference or on the next page.
- Every figure must be referenced in text.
- Number within each section: `Рисунок 3.4`; if only one in a section, still use `Рисунок 1.1`.
- Appendix figures use appendix letter: `Рисунок А.2`.
- Caption is centered under the figure; separate figure, caption, and surrounding text with blank lines.
- Figures may be in text, on separate sheets, or rotated `90` degrees counterclockwise along the long side.
- Use uniform style, notation, labels, and callouts. Color is allowed.
- Minor inline illustrations without later references may remain unnumbered.
- If a figure continues, keep the title on the first page and mark following pages as continuation sheets.

## Formulas

- Use a formula editor or equivalent formatting that preserves visual quality.
- Separate formulas from text with blank lines.
- Explain symbols directly under the formula in the order they appear.
- First explanation line starts with `где` without a colon.
- Number formulas within each section as `(3.1)`; if only one in a section, still number it.
- Put formula number at the right margin.
- All formulas must be referenced in text with wording such as `по формуле (2.1)` or `уравнением (2.1)`.
- Break formulas only at operation signs and repeat the sign at the start of the next line; use `×` when breaking at multiplication.
- Do not break at division signs or inside root, integral, logarithm, trigonometric, or similar expressions.
- Short similar formulas may be placed on one line separated by semicolons.

## Tables

- Place each table after the first textual reference or on the next page.
- Every table must be referenced in text.
- Table title goes above the table, left aligned from paragraph indent.
- Number within each section: `Таблица 4.2`; if only one in a section, still use `Таблица 1.1`.
- Appendix tables use appendix letter: `Таблица В.1`.
- Title should be concise and informative.
- Text above and below the table is separated by a blank line.
- Column headings start with capital letters; subheadings start lowercase if they continue the heading meaning.
- No periods in headings/subheadings; use singular form; center heading text.
- Do not add a default `No.`/`Номер по порядку` column.
- Table header must be separated by a line; row height should be at least `8 mm`.
- Diagonal lines in table headings are not allowed.
- Internal lines may be omitted only if readability remains clear.
- On continuation pages use `Продолжение таблицы ...` or equivalent automated continuation style.
- Numeric values in one column should align by digit place and usually keep the same number of decimal places.

## Sources And Citations

- Source list title: `Список использованных источников`.
- Place the source list before appendices.
- Include only sources actually cited in the text.
- Prefer ordering by first appearance in text; alphabetical order is allowed.
- Number sources with Arabic numerals and a period from paragraph indent.
- In-text citations use square brackets: `[1]`.
- For large sources, page/figure уточнение is allowed: `[1, с. 386]`, `[1, с. 386, рисунок 3.6]`.
- Internet sources should be official organization, authority, language, technology, or documentation resources where possible.
- The same source appears in the source list only once.
- Bibliographic formatting follows `ГОСТ 7.1-2003`.
- Bibliographic description areas are separated by `. -`; the description ends with a period.
- For one to three authors, record the first author first and list authors after the slash. For four or more authors, start with the title and use the first author plus `[и др.]` after the slash.
- Abbreviate `Москва`, `Санкт-Петербург`, and `Ростов-на-Дону` as `М.`, `СПб.`, and `Ростов н/Д`; write other cities fully.
- Do not write `год` or `г` after the publication year.

## Appendices And Program Code

- Appendices may be mandatory, recommended, or reference.
- Every appendix starts on a new page.
- Top center: `ПРИЛОЖЕНИЕ` plus its letter.
- Next line in parentheses: `обязательное`, `рекомендуемое`, or `справочное`.
- Next line: appendix title, centered.
- Appendices are ordered by first reference in the text and must all be referenced.
- Use Russian capital letters starting from `А`, excluding `Е`, `З`, `Й`, `О`, `Ч`, `Ъ`, `Ы`, `Ь`.
- Reduced font `10-12 pt` is allowed in appendices if readable.
- Figures, tables, and formulas in appendices replace section number with appendix letter.
- Program code belongs in appendices, not in main text.
- Program text follows `ГОСТ 19.401-78`, includes meaningful comments, and follows language code conventions.
- Use `Times` `10-12 pt`, single spacing for code appendices.
- Small code fragments up to about half a page may appear in the main text only as figures when needed for explanation.
- Functionally independent program components may be split across separate appendices or parts of one appendix.

## Software Manuals

For diploma software appendices, prepare these when applicable:

- System programmer manual: general information, program structure, setup, program check, additional capabilities if justified, messages to the system programmer.
- Programmer manual: purpose and conditions of use, program characteristics, program invocation, input and output data, messages.
- User manual: introduction, purpose and conditions of use, preparation for work, operation description, emergency situations, learning recommendations.

## Presentation

The defense presentation should contain at least `15` slides and cover:

- task statement and research goals;
- information model of the researched system;
- software functional diagram;
- data schema;
- database schema;
- main algorithms, preferably graphical algorithm schemes;
- input data description;
- program results;
- result analysis;
- conclusions.

The report plus software demonstration is up to `15` minutes; the full defense is up to `30` minutes.

## Academic Writing Patterns

Use patterns like:

- `Актуальность темы обусловлена...`
- `Целью работы является...`
- `Для достижения поставленной цели необходимо решить следующие задачи...`
- `В рамках выполненной работы был проведен анализ...`
- `В ходе работы разработан...`
- `На основании проведенного исследования можно сделать вывод...`
- `Практическая значимость результатов заключается в...`

Avoid patterns like:

- `я сделал`
- `мне удалось`
- `классное решение`
- `удобный и простой`
- empty praise without evidence
- unsupported claims of novelty or efficiency

## Final Compliance Check

- Required structure is present and ordered correctly.
- Diploma sections match expected content and approximate volume.
- Headings, lists, pagination, margins, font, spacing, and typography follow the rules above.
- Latin letters and symbolic designations in Russian body text are italicized where they function as symbols.
- All figures, tables, formulas, and appendices are referenced in text and numbered correctly.
- Source list contains only cited sources, preferably ordered by first appearance.
- Internet sources are official where possible.
- Program code is in appendices unless a short explanatory fragment is formatted as a figure.
- No colloquial phrasing, duplicate claims, unsupported claims, or abrupt section endings remain.
