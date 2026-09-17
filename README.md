# Brisart Institutional

A repository of complete, ready-to-teach curriculum packages for frameworks developed within the Brisart ecosystem.

Each package in this repository is a full teaching kit for a single framework — instructor guides, leveled lesson plans, micro-lessons, and assessments with answer keys — built so an instructor with no prior background in the framework can pick it up and teach it.

## What's Here

| Package | Framework | Levels Covered | Status |
|---|---|---|---|
| `TFL_K12_Curriculum/` | Temporal Feedback Loop (TFL) | K-12 (four bands: K-2, 3-5, 6-8, 9-12) | First package uploaded |

More framework curricula will be added over time, each in its own top-level folder following the same structure.

## Standard Package Structure

Every curriculum package in this repository follows the same layout, regardless of which framework it teaches:

```
<Framework>_<LevelRange>_Curriculum/
├── 00_START_HERE/          Instructor orientation — how to teach, not what to teach
├── Band_or_Level_1/
│   ├── lessons/            One full lesson plan per teaching day
│   ├── micro_lessons/      Short standalone segments (5-12 min)
│   └── assessments/        Homework, quizzes, tests, rubrics, answer keys
├── Band_or_Level_2/
│   └── ...
└── CURRICULUM_INDEX.md     Complete file listing and quick-reference for the package
```

The `00_START_HERE/` folder is always the entry point for a new instructor and typically includes:

- A method guide (how to teach the framework)
- A statement of teaching principles
- A scope-and-boundaries document (what the framework does *not* cover)
- A common-misconceptions guide
- A vocabulary reference by level
- Study methods for students
- An assessment philosophy overview
- Accommodations and differentiation guidance
- Materials and setup requirements

## Design Principles Across Packages

Regardless of the framework being taught, every package in this repository is built around the same instructional commitments:

- **Experience before vocabulary.** Concepts are taught through activity first, then named.
- **Assessment never grades prediction/outcome correctness where applicable** — only recording, reasoning, and completeness.
- **Scope is explicit content, not a disclaimer.** Every package states plainly what its framework does *not* model.
- **Self-contained levels.** Any level or band can be taught independently without requiring the others.
- **No specialized equipment required.** Packages are designed to run with paper, a whiteboard, and basic classroom materials.

## Licensing

See `LICENSE.md`. Licensing terms, participation policies, and ecosystem-wide programs for all Brisart frameworks and tooling are maintained centrally in the BrisartLicensing repository.

## Adding a New Package

New framework curricula should be added as a new top-level folder following the standard package structure above, with its own `00_START_HERE/` and `CURRICULUM_INDEX.md`. This README should be updated to list the new package in the table above.
