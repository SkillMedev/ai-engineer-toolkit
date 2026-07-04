# AI Engineer Toolkit

**When an AI feature has to survive production, not just demo: prompts, evals, agents, MCP.** — built in-house by [Skill&nbsp;Me](https://skillme.dev).

Reach for this when you're putting an AI feature into production, not just prototyping one. It carries you through the real build loop: write prompts that hold up under edge cases, prove they work with rigorous evals before you ship, orchestrate multi-step agents when one call isn't enough, and expose your own tools as MCP servers Claude can call. It also covers the surrounding engineering work — deep multi-source research, sound ML feature design, and recoverable, observable error handling — so the system holds together end to end. The outcome is an AI feature you can defend in code review and trust in front of users.

⭐ **If this is useful, star the repo** — it's how we gauge what to build next.

## Install

- **From the catalog:** [skillme.dev/pack/ai-engineer-toolkit](https://skillme.dev/pack/ai-engineer-toolkit) — install the whole pack into Claude in one step.
- **With the skills CLI:** `npx skills add SkillMedev/ai-engineer-toolkit`
- **Manually:** copy any `skills/<slug>/SKILL.md` into your Claude skills directory.

## Skills in this pack

- **[Prompt Engineer](skills/prompt-engineer/SKILL.md)** — Writes structured prompts with role, context, format, and examples for any LLM task.
- **[MCP Server Builder](aouellets)** — Builds MCP servers with proper tool definitions, error handling, and auth patterns. _(external — see source)_
- **[LLM Evaluation](skills/llm-evaluation/SKILL.md)** — Designs eval frameworks for LLM outputs — correctness, faithfulness, and human preference.
- **[Agent Orchestration](skills/agent-orchestration/SKILL.md)** — Designs multi-agent systems with task routing, context passing, and failure recovery.
- **[Deep Research](skills/deep-research/SKILL.md)** — Comprehensive research synthesis across many sources with structured findings and citations.
- **[Feature Engineering](skills/ml-feature-engineering/SKILL.md)** — Designs ML features: encoding, scaling, interaction terms, and leakage prevention.
- **[Error Handling](skills/error-handling/SKILL.md)** — Designs robust error handling strategies — typed errors, error boundaries, observability hooks.

## License

MIT — see [LICENSE](LICENSE). Skills are portable `SKILL.md` files; the canonical
copies live in the [Skill&nbsp;Me catalog](https://skillme.dev).
