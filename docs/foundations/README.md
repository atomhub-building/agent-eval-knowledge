# Foundations

An agent evaluation observes a system attempting tasks and judges whether its behavior meets a stated objective. Define the system boundary before assigning a score.

## Specify the boundary

- **Task:** the requested outcome and conditions for success.
- **Agent:** model, instructions, orchestration code, and configuration.
- **Environment:** tools, permissions, state, data, and external services.
- **Grader:** the rule or process used to judge the outcome.
- **Budget:** limits on time, model calls, tool calls, and cost.

## Evaluate outcomes and behavior

A final answer alone may miss an incorrect side effect or an excessive tool budget. Decide which observations matter: output, resulting environment state, execution trace, latency, and resource usage.

For example, an agent asked to update a record may produce a convincing confirmation while leaving the record unchanged. Checking the resulting record tests the intended outcome more directly.

## Distinguish evaluation levels

Component tests isolate a tool or grader. Scenario evaluations test the whole agent in a controlled environment. Production observations describe real usage but may be harder to reproduce. Label the level so readers understand what a result supports.

Next: [Evaluation Design](../evaluation-design/README.md).
