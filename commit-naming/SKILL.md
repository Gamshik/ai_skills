---
name: commit-naming
description: Use when the user asks to name a git commit, write or rewrite a commit message, choose a commit type such as feat, fix, docs, refactor, test, ci, build, chore, or format one commit message for single or multiple changes.
---

# Commit Naming

## When to use

- The user asks how to name a commit.
- The user wants a commit message from a diff, summary, or list of changes.
- The user wants to rewrite a vague commit like `update`, `fix stuff`, or `changes`.
- The user asks which type to use: `feat`, `fix`, `perf`, `docs`, `style`, `refactor`, `ci`, `chore`, `build`, `test`, and similar labels.
- The user wants one commit message that cleanly lists several changes.

## Quick start

1. Determine whether the commit contains one change or several changes.
2. Choose the best commit type.
3. Format the message using one of the two approved patterns.
4. Return only the ready commit message unless the user explicitly asks for an explanation.

## Required format

For one change, use a single line:

```text
type: short description of the change
```

For several changes, use the type, then a colon, then an empty line, then a list:

```text
type:

- first change;
- second change;
- last change.
```

Rules:

- Do not use icons or emoji.
- Use a lowercase type such as `feat`, `fix`, `docs`, or `refactor`.
- After the type, use only one colon.
- For a single change, place one space after the colon and continue on the same line.
- For multiple changes, put only `type:` on the first line.
- Leave one empty line between `type:` and the bullet list.
- Start each list item with `- `.
- End every list item with `;`, but end the last item with `.`.
- Keep the wording concrete and specific about what changed.

## Commit types

Use the closest matching type:

- `feat` for new functionality.
- `fix` for bug fixes.
- `perf` for performance improvements.
- `docs` for documentation-only changes.
- `style` for formatting or style-only changes that do not change behavior.
- `refactor` for code restructuring without behavior changes.
- `test` for adding or updating tests.
- `build` for build system or dependency build changes.
- `ci` for CI or automation pipeline changes.
- `chore` for maintenance work that does not fit the main feature categories.

If several change types are mixed, choose the dominant type. If there is no clear dominant type, use `chore`. If the changes are clearly unrelated, prefer suggesting separate commits.

## Writing rules

- Use English by default.
- Use another language only if the user explicitly asks for it or the repository clearly requires it.
- Describe the result of the change, not the intention to maybe do something later.
- Avoid generic descriptions like `update`, `changes`, `small fixes`, or `misc`.
- Do not add scopes like `feat(api): ...` unless the user or repository explicitly asks for scopes.
- Keep the message concise, but still informative enough to understand the change without opening the diff.

## Examples

Single change:

```text
feat: add PDF export for reports
```

```text
fix: handle empty API responses correctly
```

```text
docs: update local setup instructions
```

Multiple changes:

```text
refactor:

- move validation logic into a dedicated service;
- simplify the form handler;
- remove duplicated code.
```

```text
ci:

- add lint checks to the pipeline;
- update the test execution step;
- fix artifact publishing.
```

## Response behavior

When the user asks for a commit name:

- infer the best type from the described changes;
- produce the commit message directly in the required format;
- use the multi-line format whenever there are several meaningful changes;
- mention commit splitting only when it materially improves clarity.
