# First Evaluation Workflow

## 1. Write a plan

Copy the [Evaluation Plan](../../templates/evaluation-plan.md). Choose one narrow task family and a small set of manually inspectable examples. Define success before running an agent.

## 2. Establish a baseline

Run a simple baseline with fixed inputs and budgets. Save outputs and errors. The companion [framework quickstart](https://github.com/atomhub-building/agent-eval-framework#quickstart) demonstrates the file flow using a local toy agent and exact-match scoring.

## 3. Inspect the grader

Manually review a sample of successes and failures. Add cases where the grader should accept or reject an output. Resolve ambiguous task requirements before comparing candidates.

## 4. Change one variable

Compare a candidate with the baseline on the same suite. Keep environment conditions and budgets consistent. Repeat runs if stochastic behavior affects the decision.

## 5. Report and iterate

Record results, failure categories, exclusions, and limitations in a [Case Study](../../templates/case-study.md). Keep held-out tasks separate from the examples used to improve the agent.
