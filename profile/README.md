# eval forge

### Note: Check Test #1 results and its prompt on our [website](https://eval-forge.github.io)

**Open evaluations for frontier AI models.**

Eval Forge is a collection of tests designed to measure, compare, and explore the capabilities of modern AI models.

Instead of relying only on aggregate benchmark scores, Eval Forge focuses on **direct model testing**: give models the same task, preserve their outputs, and compare how they reason, create, code, analyze, and follow instructions.

## What We Evaluate

Evaluations may cover areas such as:

- Reasoning and problem solving
- Mathematics
- Coding
- Scientific reasoning
- Writing and communication
- Instruction following
- Long-context understanding
- Multimodal understanding
- Tool use and agentic tasks
- Factual accuracy
- Creativity
- Edge cases and failure modes

The goal isn't to find a single model that's "best." Different models have different strengths, weaknesses, and behaviors. Eval Forge makes those differences easier to inspect.

## Repository Structure

```text
eval-forge/
├── evals/
│   ├── reasoning/
│   ├── coding/
│   ├── math/
│   ├── science/
│   ├── writing/
│   └── multimodal/
│
├── results/
│   ├── model-a/
│   ├── model-b/
│   └── ...
│
├── prompts/
├── scripts/
└── README.md
```

The structure may evolve as new evaluation types and models are added.

## Evaluation Philosophy

A useful evaluation should be:

**Reproducible** — prompts, relevant settings, and outputs should be preserved whenever possible.

**Comparable** — models should receive equivalent tasks and conditions when being compared.

**Transparent** — evaluation methodology and scoring criteria should be understandable.

**Challenging** — tests should reveal meaningful capability differences rather than reward trivial pattern matching.

**Practical** — evaluations should include tasks that resemble things people actually ask AI systems to do.

## Models

Eval Forge is designed to test frontier and emerging models from multiple providers, including models from:

- Anthropic
- OpenAI
- Google
- xAI
- Meta
- DeepSeek
- Mistral
- Other open and proprietary model developers

Model availability and tested versions will change over time.

## Results

Results should generally include:

```text
Prompt
↓
Model configuration
↓
Raw response
↓
Evaluation / scoring
↓
Comparison
```

Where possible, raw model outputs are preserved rather than replaced with summaries.

## Scoring

Not every evaluation needs the same scoring system.

Depending on the task, an evaluation may use:

- Exact-match scoring
- Pass/fail criteria
- Test suites
- Rubric-based scoring
- Automated graders
- Human evaluation
- Pairwise comparison
- Qualitative analysis

Evaluation methodology should be documented alongside the results.

## Contributing

Contributions are welcome.

Good contributions include:

- New evaluation prompts
- More difficult test cases
- Improved scoring methods
- Reproductions across additional models
- Evaluation tooling
- Bug fixes
- Documentation improvements

When adding an evaluation, try to include enough information for someone else to reproduce it.

## Disclaimer

Eval Forge is an independent evaluation project.

Results represent model behavior under the specific prompts, configurations, and conditions tested. They should not be treated as universal measurements of a model's capabilities.

Models change. Providers update systems. Outputs can vary between runs.

That's part of what makes evaluating them interesting.

---

**Forge the prompt. Test the model. Measure the result.**
