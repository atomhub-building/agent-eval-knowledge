# Benchmark Reviews

This directory is reserved for evidence-backed reviews of agent benchmarks. No benchmark reviews have been added yet.

Before adopting a benchmark, check:

- Which tasks, environments, and agent capabilities it actually tests.
- How tasks are sampled, versioned, and distributed.
- Whether success is checked from final output, environment state, or a judgment rubric.
- Which tools, budgets, retries, and environment resets are allowed.
- Whether contamination, leakage, or public solutions could affect the comparison.
- Whether the harness and dependencies can be reproduced within your resources.
- Whether the task distribution resembles the intended application.

Use the [Benchmark Review](../../templates/benchmark-review.md) template and link the primary paper, dataset, and implementation. Record the exact version; avoid comparing scores produced under different rules without explaining the differences.
