---
applyTo: "**/*.go"
---

# Go Study Guidelines

When working with Go code in this repository, prioritize learning and reasoning over implementation speed.

- Prefer idiomatic Go and the standard library.
- Explain why a construct is appropriate, not only how to write it.
- Preserve simple solutions; do not introduce abstractions without a concrete need.
- Use clear names, explicit error handling, and context propagation at I/O boundaries.
- When concurrency is involved, reason about goroutine ownership, cancellation, shared state, races, and lifecycle.
- When performance is discussed, measure before optimizing and use benchmarks or profiling where appropriate.
- When behavior depends on runtime internals, distinguish specification guarantees from implementation details.
- Prefer small experiments and tests that demonstrate one concept.
- Do not rewrite learner code unless requested; review it and explain the reasoning first.