# Awesome Unique ID - Agent Guide

A curated awesome list of Unique ID libraries and resources. This is a documentation-only repository with no build system, tests, or executable code.

## Repository Structure

| Path | Purpose |
|---|---|
| `README.md` | The awesome list — primary content file |
| `CONTRIBUTING.md` | Contribution guidelines for new entries |
| `CODE_OF_CONDUCT.md` | Community standards |
| `AGENTS.md` | This file |

## Content Format

README.md is organised into sections. Each entry follows this pattern:

```
- [Library Name](repo-url) ([npm/PyPI/pkg](registry-url)) - One-sentence description.
```

Rules:
- Link text is the library name, URL points to the source repository
- Registry link (npm, PyPI, etc.) follows in parentheses where applicable
- Description is a single sentence ending with a period
- Deprecated entries include `[Deprecated]` at the start of the description

## Sections

| Section | Purpose |
|---|---|
| Generation | Libraries that generate unique IDs |
| Hash | Libraries/tools that hash or visualise IDs |
| CLI Tools | Command-line tools for working with IDs |
| Research | Articles, papers, and collision calculators |
| Contributors | Auto-managed by all-contributors bot |

The Generation section is subdivided by programming language (Polyglot, JavaScript, Python, Go, etc.).

## Adding Entries

When adding a new library or resource:

1. Place it in the correct section and language subsection
2. Match the existing entry format exactly
3. Preserve alphabetical or logical ordering within a subsection if one exists
4. Do not modify the Contributors section — it is managed by the all-contributors bot

When adding a new language subsection under Generation, use an `###` heading matching existing subsection style.

## Editing Guidelines

- Do not alter the all-contributors HTML block in README.md (lines between `ALL-CONTRIBUTORS-LIST:START` and `ALL-CONTRIBUTORS-LIST:END`)
- Do not add badges, images, or HTML outside the contributors block
- Keep descriptions factual and neutral — avoid marketing language
- Deprecated entries stay in the list with `[Deprecated]` noted; do not remove them

## Style

- CommonMark markdown only
- No bold, italic, or other inline formatting in list entries
- URLs must be real and resolvable
- One blank line between subsections, no consecutive blank lines
