# MGTA01 study guide

A complete single-page study platform for **MGTA01H3, Introduction to Business** (University of
Toronto Scarborough, Summer 2026).

**Live:** https://aeripsen.github.io/mgta01-study-guide/

Written for the final exam: **Thursday August 13, 2 to 4pm, HL-170.** Two sections of 20 marks,
multiple choice and short answer, two hours, cumulative over ten lectures.

## The idea

The page is built in **two deliberately separate layers**.

**Orange boxes are for memorising.** Every one is a list the course states and numbers explicitly,
with the item count shown so you know when you have them all. Each box can be covered so you can
recite it back. There are 53 of them.

**Everything else is for understanding.** Prose, diagrams and definitions exist so the lists make
sense and so you have something to say in the short answer section, which is explicitly about
applying the course to case studies.

A **Full / Memorise only** switch at the top hides all the prose and leaves just the boxes, for the
last pass before the exam.

## What is in it

| | |
|---|---|
| Units | 10, in the order the course builds them |
| Memorise boxes | 53, one per itemised list |
| Diagrams | 13 hand-drawn SVGs, theme-aware |
| Glossary | 153 terms, searchable, generated from the page so it cannot drift |
| Flashcards | 51 decks, generated from the memorise boxes, filterable by unit, shuffleable |
| Practice exam | 30 scored multiple choice with explanations, plus 3 worked case studies |

Flashcards and the glossary are both **generated at runtime from the page content itself**, so they
can never fall out of sync with the notes.

## What it is not

**These are independent revision notes, not course material.** They are not endorsed by the
instructor or the university and reproduce no lecture slides, which are the instructor's copyrighted
work and are excluded from this repository by `.gitignore`. The concepts are standard
introduction-to-business material; the wording, groupings, mnemonics, diagrams and practice questions
are original.

The exam also names **textbook chapters 1 to 10**. Anything appearing only in the textbook and never
in a lecture will not be found here. Check everything that matters against your own notes.

## Running it

```
site/index.html
```

One self-contained file. No build step, no dependencies, no network requests. Open it directly, or
serve the folder:

```
python -m http.server 8000
```

Responsive, follows your system light or dark theme, and prints cleanly.
