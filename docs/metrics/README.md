# Metrics

Select metrics from the evaluation objective. Record the numerator, denominator, unit, and treatment of missing or failed runs.

| Dimension | Example measurement | Interpretation caveat |
| --- | --- | --- |
| Outcome | Successful tasks / attempted tasks | Define success and count every attempted task |
| Reliability | Success frequency across repeated trials | Preserve per-task variation as well as the overall mean |
| Efficiency | Latency, tool calls, tokens, or monetary cost per task | State whether setup time and failed attempts are included |
| Process | Constraint violations or invalid tool calls | A clean trace does not guarantee a correct outcome |
| Grader quality | Agreement with a reviewed reference set | Report the reference set and disagreement categories |

## Aggregation

Report the task count and per-category results before relying on a single mean. Compare candidates on the same tasks. Keep raw trial results so changes in task mix do not masquerade as improvements.

Exact string match is appropriate for tightly constrained outputs. It can reject valid paraphrases, and it does not establish that an agent performed a requested side effect.

## Minimum result record

Capture task ID, run ID, agent configuration, output or state evidence, score, error category, duration, and resource usage when available. Mark unavailable measurements explicitly rather than substituting zero.
