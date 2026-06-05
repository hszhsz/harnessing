# Appendix D: Contribution Guide

Welcome to the open-source repository for *Harnessing: A History of Human Productivity*. This guide explains how to contribute corrections, translations, new research, illustrations, and structural improvements to the English edition and its Chinese parallel text.

---

## How to Fork and Submit Pull Requests

### Getting Started

1. **Fork the repository** -- Click the "Fork" button on the project's main page to create your own copy.
2. **Clone your fork locally:**
   ```bash
   git clone https://github.com/<your-username>/harnessing.git
   cd harnessing
   ```
3. **Create a feature branch** from `main`:
   ```bash
   git checkout -b contrib/<short-description>
   ```
4. **Make your changes** following the writing style guide below.
5. **Commit with a clear message:**
   ```bash
   git add .
   git commit -m "appendix-a: correct per-capita wattage for 1850 CE entry"
   ```
6. **Push to your fork and open a Pull Request:**
   ```bash
   git push origin contrib/<short-description>
   ```
   Then open a PR against `main` on the upstream repository.

### Pull Request Requirements

- Each PR should address a single logical change (one correction, one new section, one translation batch).
- Include a brief description of **what** you changed and **why**.
- Reference any related Issue numbers (e.g., `Fixes #42`).
- For factual corrections, include a citation or source.
- For new content, include at least one scholarly reference.
- All PRs require at least one maintainer review before merge.

---

## Writing Style Guide

The main text of *Harnessing* follows a narrative non-fiction style. Contributions should match these conventions:

### Voice and Tone

- **Third-person narrative** with occasional first-person plural ("we") when drawing the reader into shared human experience.
- **Active voice preferred.** Avoid passive constructions except when the agent is genuinely unknown or unimportant.
- **Present tense for ongoing truths** ("Fire transforms raw starch into digestible glucose"), **past tense for historical events** ("Newcomen installed his first engine in 1712").

### Structure

- Chapters open with a concrete scene or anecdote, then widen to systemic analysis.
- Each chapter ends with a transitional paragraph that bridges to the next era.
- Subsections are headed with descriptive noun phrases, not questions.
- Footnotes are used for citations and brief asides; extended digressions belong in sidebars or appendices.

### Technical Conventions

- Units: SI units preferred, with imperial equivalents in parentheses where helpful for anglophone readers.
- Numbers: Spell out one through nine; use numerals for 10 and above. Always use numerals with units (e.g., "5 watts", "3 km").
- Dates: Use CE/BCE rather than AD/BC. Write "~10,000 BP" for deep prehistory.
- Abbreviations: Define on first use in each chapter.

### Citations

- Use author-date style in running text: (Smil 2017, p. 43).
- Full references appear in the Bibliography, organized alphabetically by author surname.
- For online sources, include access date and archived URL where possible.

---

## Translation Conventions (Chinese-English Parallel)

This project maintains a bilingual structure with Chinese (`/zh/`) and English (`/en/`) directories mirroring each other.

### Parallel Structure Rules

- Every file in `/en/chapters/` must have a corresponding file in `/zh/chapters/` and vice versa.
- File names are identical across languages (e.g., `chapter-03.md` in both directories).
- Section headings must correspond one-to-one between languages to enable cross-referencing.

### Translation Principles

| Principle | Guideline |
|---|---|
| Fidelity | Translate meaning and tone, not word-for-word. Preserve the narrative rhythm. |
| Technical terms | Use established translations from Chinese-language history of science literature. Provide the English original in parentheses on first occurrence. |
| Proper nouns | Use standard Romanization (Pinyin for Chinese names, conventional English forms for Western names). |
| Units and numbers | Maintain SI units in both languages. Chinese text may add Chinese-unit equivalents where culturally relevant. |
| Cultural references | When an analogy is culture-specific, adapt rather than transliterate. Add a translator's note if the adaptation significantly changes the illustration. |
| Translator's notes | Mark with `[TN: ...]` inline. Keep brief; extended notes go in a dedicated `translator-notes.md` file per chapter. |

### Translation Workflow

1. Open an Issue labeled `translation` specifying which chapter/section and target language.
2. Assign yourself (or request assignment from maintainers).
3. Submit the translation as a PR with both the new translated file and any updates to the parallel-language cross-reference index.
4. A bilingual reviewer must approve before merge.

---

## Issue Label Descriptions

| Label | Color | Description |
|---|---|---|
| `correction` | Red | Factual errors, incorrect dates, wrong figures, or misattributions in existing text. |
| `translation` | Blue | Requests or submissions for translating content between Chinese and English. |
| `new-content` | Green | Proposals for new sections, sidebars, or appendix entries not currently in the text. |
| `style` | Yellow | Writing style issues: tone inconsistencies, passive voice, unclear prose. |
| `citation-needed` | Orange | Claims in the text that lack adequate sourcing. |
| `illustration` | Purple | Requests for diagrams, charts, maps, or photographs to accompany text. |
| `data-update` | Teal | Figures or statistics that need updating due to new research or revised datasets. |
| `infrastructure` | Gray | Repository tooling, CI/CD, build scripts, formatting automation. |
| `good-first-issue` | Light green | Simple, well-scoped tasks suitable for first-time contributors. |
| `discussion` | White | Open-ended questions about scope, framing, or interpretation--not actionable yet. |

---

## Code of Conduct

### Our Pledge

We are committed to making participation in this project a harassment-free experience for everyone, regardless of age, body size, disability, ethnicity, sex characteristics, gender identity and expression, level of experience, education, socio-economic status, nationality, personal appearance, race, religion, or sexual identity and orientation.

### Our Standards

**Behaviors that contribute to a positive environment:**

- Using welcoming and inclusive language.
- Respecting differing viewpoints and experiences.
- Gracefully accepting constructive criticism.
- Focusing on what is best for the scholarly quality of the work.
- Showing empathy toward other community members.

**Unacceptable behaviors:**

- The use of sexualized language or imagery.
- Trolling, insulting/derogatory comments, and personal attacks.
- Public or private harassment.
- Publishing others' private information without explicit permission.
- Deliberately introducing misinformation or fabricated citations.
- Other conduct that would be considered inappropriate in a professional academic setting.

### Scope

This Code of Conduct applies within all project spaces (issues, PRs, discussions, project chat channels) and in public spaces when an individual is representing the project.

### Enforcement

Instances of abusive, harassing, or otherwise unacceptable behavior may be reported to the project maintainers at `conduct@harnessing-book.org`. All complaints will be reviewed and investigated promptly and fairly. Maintainers are obligated to maintain confidentiality with regard to the reporter.

### Attribution

This Code of Conduct is adapted from the [Contributor Covenant](https://www.contributor-covenant.org/), version 2.1.
