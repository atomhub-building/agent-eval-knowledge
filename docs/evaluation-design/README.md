# Evaluation Design

Start with a decision the evaluation should inform, such as whether a new prompt improves a specific workflow.

## Design checklist

1. Define the target users, task distribution, and success criteria.
2. Choose representative tasks, including edge cases and expected failures.
3. Separate development examples from held-out evaluation tasks. Track possible overlap with training or prompt examples.
4. Specify a grader for each task before examining candidate outputs.
5. Pin model identifiers where possible and record prompts, tool versions, dataset versions, budgets, and environment configuration.
6. Reset environment state between trials. Record stochastic settings and repeat trials when variability matters.
7. Compare against a baseline using the same tasks and resource constraints.
8. Report denominators, exclusions, failures, and uncertainty alongside aggregate scores.

## Grader choices

Prefer deterministic checks when the target can be checked directly. Use human review or model-based grading for judgments that cannot be reduced to a reliable rule. Document the rubric, calibrate against reviewed examples, and inspect disagreements.

Do not silently treat infrastructure failures as agent failures or exclude them from totals. Label them explicitly and explain the reporting policy.

Start with the [Evaluation Plan](../../templates/evaluation-plan.md).
