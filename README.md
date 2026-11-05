# Agent Eval Knowledge

A growing collection of practical knowledge, evaluation methods, and reusable templates for evaluating AI agents.

Maintained by [yimi528](https://github.com/yimi528) under [atomhub-building](https://github.com/atomhub-building).

## Purpose

Build evaluations that answer a clear question: **does this agent reliably complete the intended task, within the constraints that matter?**

This repository covers task outcomes, execution traces, tool use, reliability, cost, and latency. It is a learning and reference library; runnable evaluation code lives in the companion [Agent Eval Framework](https://github.com/atomhub-building/agent-eval-framework).

## Start here

1. Read [Foundations](docs/foundations/README.md) to define the evaluation boundary.
2. Use [Evaluation Design](docs/evaluation-design/README.md) to choose tasks, graders, and controls.
3. Copy the [Evaluation Plan](templates/evaluation-plan.md) and fill in a concrete experiment.
4. Choose [Metrics](docs/metrics/README.md), then follow the [Practical Guide](docs/practical-guides/README.md).
5. Record findings using the [Case Study](templates/case-study.md) template.

## Repository map

| Path | Contents |
| --- | --- |
| [docs/](docs/README.md) | Topic index and reading path |
| [docs/foundations/](docs/foundations/README.md) | Agent evaluation concepts and boundaries |
| [docs/evaluation-design/](docs/evaluation-design/README.md) | Task selection, controls, and grading |
| [docs/metrics/](docs/metrics/README.md) | Outcome, reliability, efficiency, and process metrics |
| [docs/benchmarks/](docs/benchmarks/README.md) | How to review and compare benchmarks |
| [docs/practical-guides/](docs/practical-guides/README.md) | A small end-to-end evaluation workflow |
| [docs/case-studies/](docs/case-studies/README.md) | Structure for future experiment write-ups |
| [docs/glossary.md](docs/glossary.md) | Shared terminology |
| [resources/](resources/README.md) | Criteria for adding papers, tools, and datasets |
| [templates/](templates/README.md) | Copyable evaluation and review templates |

## Scope and status

The initial content provides a foundation for organizing evaluations. There are no completed benchmark reviews, published experiment results, or leaderboard claims yet. Add evidence and runnable references as the library grows.

Planned additions:

- Evidence-backed benchmark reviews using a consistent comparison format.
- Worked examples connected to the companion framework.
- Case studies describing failures, grader limitations, and lessons learned.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). Small corrections, practical examples, and well-sourced notes are welcome. Clearly separate measured findings from hypotheses and recommendations.

## License

A license has not been selected yet. Contact the maintainer before redistributing or reusing substantial content.
