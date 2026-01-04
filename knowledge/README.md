# BonsAI Studio – Knowledge Base

This directory contains all operational knowledge used
to generate bonsai visualizations.

## Governance
`governance/` contains binding rules that define what is allowed
and forbidden. These rules override any individual prompt.

## Prompts
`prompts/` contains production-ready prompts per engine.
Each prompt:
- Is versioned
- Has been validated on real trees
- Trades control for realism (never fantasy)

Example:
- nano_banana_pro/conifer_best_possible_v1.yaml

## Tests
`tests/` contains exploratory runs, A/B comparisons,
and failed experiments kept for reference.

## Rule of Thumb
If a prompt conflicts with governance rules,
the prompt is wrong.

