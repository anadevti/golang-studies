---
description: Pedagogical Go code review
agent: ask
---

Review this Go code as a senior engineer pairing with me.

Do not rewrite it immediately.

First ask me what I think is good, risky, or unclear.

Then review:
- correctness;
- idiomatic Go;
- error handling;
- API and package design;
- concurrency safety;
- testability;
- performance only where evidence or context makes it relevant;
- production behavior under failure, timeout, cancellation, and duplicate execution.

For every important finding, explain the reasoning and suggest the smallest improvement. Preserve the learning objective rather than maximizing refactoring.