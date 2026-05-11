# The Evolution of Coding Agents

**From Copilot to self-evolving harnesses, 2021-2026 and beyond.**

A source-backed explanation of how coding agents evolved from autocomplete and prompt engineering to long-running agents, verifier loops, structured workflows, harness engineering, and model-harness co-design.

## TL;DR

Coding agents became useful for two reasons at once: models improved, and the systems around them improved. The important shift is not just better completions, but better execution environments: tools, context, workflows, verifiers, hooks, sub-agents, persistent state, and feedback loops.

This is not meant to be only a timeline. The full essay explains the concepts behind each transition, why they mattered technically, which references support them, and where the claims are still uncertain.

The document argues that the center of gravity moved through six eras:

| Era | Core idea |
|---|---|
| 2021-mid 2022 | Prompt as oracle: autocomplete and single-shot code generation |
| late 2022-2023 | Program as output: LLMs produce executable intermediate artifacts |
| 2023-early 2025 | Conversational pair programming and first agentic attempts |
| mid-2025 | Outer loops with verifiers: generation is cheap, verification is the bottleneck |
| mid-2025-early 2026 | Structured workflows with persistent artifacts |
| early 2026 | Harness engineering: agent = model + harness |

## Start Here

- Read the full essay: [docs/evolution-of-coding-agents.md](docs/evolution-of-coding-agents.md)
- Audit the source list: [docs/references.md](docs/references.md)
- Check verification status: [docs/verification-log.md](docs/verification-log.md)
- Contribute corrections or additions: [docs/contributing.md](docs/contributing.md)

## Conceptual Frame

The essay treats coding-agent evolution as movement across three mostly independent axes:

| Axis | Range |
|---|---|
| Autonomy | autocomplete -> IDE pair -> CLI agent -> unattended fleet |
| Training | prompted -> fine-tuned -> RL-from-execution -> self-play |
| Harness | none -> manual prompts -> structured workflow -> self-evolving |

The central throughline is where the intelligence of the system is understood to live: first in the prompt, then in generated programs, then in conversations, then in verifier loops, then in structured workflows, and finally in designed harnesses around the model.

## Repository Status

Last reviewed: 2026-05-11  
Scope: public sources through May 2026  
Source standard: primary sources and academic papers preferred; social posts, market reports, and secondary summaries should be treated as lower-confidence unless corroborated.

This is a living reference document. Corrections are welcome, especially for dates, benchmark numbers, source quality, attribution, and claims that depend on fast-moving 2025-2026 material.
