[К разделу Sources](README.md)

# Source: SWE-bench: Can Language Models Resolve Real-World GitHub Issues?

## Metadata

- URL: https://arxiv.org/abs/2310.06770
- Accessed: 2026-05-16
- Type: paper / benchmark
- Author / organization: Carlos E. Jimenez et al.
- Year: 2023

## Main idea

SWE-bench evaluates language models on real GitHub issues where the model must modify a codebase so that tests pass. It makes software engineering a benchmark for multi-step, environment-grounded problem solving.

## Relevance to AI agents

- Important benchmark for coding agents and real-world task completion.
- Emphasizes that agent evaluation often needs executable environments, not just answer grading.
- Highlights long-context reasoning, repository navigation and test feedback.

## Notes

- SWE-bench is especially relevant for studying "task success" rather than conversational quality.
- Later variants and critiques should be tracked separately.

## Reliability and limitations

- Widely used research benchmark.
- Passing tests is a useful signal but not a complete measure of maintainability or product correctness.

## Follow-up questions

- What does SWE-bench miss about real software work?
- How should benchmarks account for time, cost and human review?
