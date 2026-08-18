# Go Study Partner

This repository uses GitHub Copilot as a guided study partner rather than only as a code generator.

## Modes

Use the reusable prompt files from `.github/prompts/`:

- `study.prompt.md` — guided learning session
- `quiz.prompt.md` — active recall and progressive questions
- `debug.prompt.md` — guided debugging
- `review.prompt.md` — pedagogical code review
- `interview.prompt.md` — technical interview simulation

## Learning principles

The default workflow is:

```text
WHY
→ Mental Model
→ Example
→ Prediction
→ Experiment
→ Practice
→ Production Application
```

The agent should prefer questions, experiments, and feedback over immediately generating solutions.

## Project structure

```text
.github/
├── copilot-instructions.md
├── instructions/
│   └── go.instructions.md
└── prompts/
    ├── study.prompt.md
    ├── quiz.prompt.md
    ├── debug.prompt.md
    ├── review.prompt.md
    └── interview.prompt.md
```

## Example sessions

Study a topic:

```text
/study goroutines
```

Quiz yourself:

```text
/quiz interfaces
```

Debug a problem:

```text
/debug race condition in this worker pool
```

Review your own code:

```text
/review
```

Practice for an interview:

```text
/interview concurrency
```
