# AGENTS.md - Notes Template Rules

## Purpose
Use this folder as a reusable LaTeX notes template. It contains the shared
design system, preamble, starter chapter, figure folder, and required assets.

## Build Rules
- Compile `main.tex` with XeLaTeX.
- Do not compile `preamble.tex` directly.
- Do not compile chapter files directly unless using the `subfiles` workflow.
- Edit the metadata commands near the top of `main.tex` for each new note.

## Editing Rules
- Keep notes in English unless the user asks otherwise.
- Use the existing LaTeX template and environments.
- Do not change `preamble.tex` unless a design or template-level change is
  explicitly requested.
- Put each chapter in `Chapters/`.
- Put reusable figures in `Figures/`.
- Do not dump new content at the end of a chapter; integrate it in the correct
  section.

## Box Usage
- Use `definitionbox` only for formal definitions.
- Use `formulabox` only for formulas or important structures.
- Use `summarybox` only at the end of a major section.
- Use normal paragraphs, `itemize`, and `enumerate` for ordinary explanation.
- Avoid duplicate headings.

## Files
- `main.tex`: project driver and course metadata.
- `preamble.tex`: shared design system, packages, boxes, colors, headers.
- `Chapters/Chapter1.tex`: starter chapter.
- `Figures/`: place chapter images here.
- `assets/`: required template assets used by the preamble.
