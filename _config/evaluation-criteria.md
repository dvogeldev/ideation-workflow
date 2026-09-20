# Evaluation Criteria & Weights

These weights determine how the five scoring dimensions combine into a composite priority score. They reflect strategic priorities set during onboarding.

**This fork is configured for Clief Notes using the Community-first profile.**

## Scoring Dimensions

| Dimension | Weight | What It Measures |
|-----------|--------|-----------------|
| Impact | 0.40 | How many people this serves and how deeply |
| Feasibility | 0.25 | How quickly and realistically this can be delivered |
| Channel Alignment | 0.15 | How well this reinforces content pillars and brand |
| Research Alignment | 0.10 | How well this demonstrates or advances the MWP/ICM thesis |
| Novelty | 0.10 | How differentiated this is from existing solutions |

## Weight Guidelines

Weights must sum to 1.0. Available profiles (reference):

| Priority Profile | Impact | Feasibility | Channel | Research | Novelty |
|-----------------|--------|-------------|---------|----------|---------|
| **Balanced** | 0.30 | 0.20 | 0.20 | 0.20 | 0.10 |
| **Community-first** (active) | 0.40 | 0.25 | 0.15 | 0.10 | 0.10 |
| **Research-driven** | 0.20 | 0.15 | 0.20 | 0.35 | 0.10 |
| **Content-driven** | 0.25 | 0.15 | 0.35 | 0.15 | 0.10 |
| **Ship fast** | 0.25 | 0.35 | 0.20 | 0.10 | 0.10 |

Why Community-first for Clief Notes: prioritize ideas that help many members ship usable ICM workspaces quickly, while still keeping enough weight on channel fit and research alignment to stay on-thesis.

## How Weights Are Applied

```
Composite = (Impact × W_impact) + (Feasibility × W_feasibility) + (Channel × W_channel) + (Research × W_research) + (Novelty × W_novelty)
```

Maximum possible composite score: 5.0
Minimum: 1.0

## Strategic Override

The user can override any ranking at the Stage 04 checkpoint. Overrides are noted in the output with rationale. The scoring provides a starting point for discussion, not a final answer.
