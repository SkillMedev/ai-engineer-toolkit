# AI Engineer Toolkit

**When an AI feature has to survive production, not just demo: prompts, evals, agents, MCP.** — built in-house by [Skill&nbsp;Me](https://skillme.dev).

Reach for this when you're putting an AI feature into production, not just prototyping one. It carries you through the real build loop: write prompts that hold up under edge cases, prove they work with rigorous evals before you ship, orchestrate multi-step agents when one call isn't enough, and expose your own tools as MCP servers Claude can call. It also covers the surrounding engineering work - deep multi-source research, sound ML feature design, and recoverable, observable error handling - so the system holds together end to end. The outcome is an AI feature you can defend in code review and trust in front of users.

⭐ **If this is useful, star the repo** — it's how we gauge what to build next.

## Install

- **From the catalog:** [skillme.dev/pack/ai-engineer-toolkit](https://skillme.dev/pack/ai-engineer-toolkit) — install the whole pack into Claude in one step.
- **With the skills CLI:** `npx skills add SkillMedev/ai-engineer-toolkit`
- **Manually:** copy any `skills/<slug>/SKILL.md` into your Claude skills directory.

## Skills in this pack

- **[Prompt Engineer](skills/prompt-engineer/SKILL.md)** — Turns a vague request into a structured, reliable prompt - role, context, task, format, failure handling, and few-shot examples - that produces consistent output across real inputs.
- **[MCP Server Builder](https://skillme.dev/skill/mcp-builder)** — Builds MCP servers with proper tool definitions, error handling, and auth patterns. _(external — see source)_
- **[LLM Evaluation](skills/llm-evaluation/SKILL.md)** — Builds evaluation harnesses for LLM products - golden datasets, deterministic checks, calibrated LLM-as-judge rubrics, and CI regression gates that turn "seems good" into a tracked number.
- **[Agent Orchestration](skills/agent-orchestration/SKILL.md)** — Designs reliable multi-agent LLM systems - choosing a topology, writing handoff contracts between agents, deciding what runs in parallel vs series, and setting context, retry, and cost budgets that stop runaway loops.
- **[Deep Research](skills/deep-research/SKILL.md)** — Runs a thorough multi-source research process - decompose the question, gather independent sources, cross-check, synthesize - and delivers a structured, cited brief with confidence levels and gaps.
- **[Feature Engineering](skills/ml-feature-engineering/SKILL.md)** — Designs ML features with leakage-safe pipelines, correct categorical encoding by cardinality, numeric transforms, and validation that a feature earns its place.
- **[Error Handling](skills/error-handling/SKILL.md)** — Designs typed, observable, recoverable error handling - an explicit taxonomy of retryable vs terminal failures, Result types at boundaries, single-point logging, and retry policies with real backoff numbers.

## License

MIT — see [LICENSE](LICENSE). Skills are portable `SKILL.md` files; the canonical
copies live in the [Skill&nbsp;Me catalog](https://skillme.dev).
