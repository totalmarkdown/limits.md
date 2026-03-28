# LIMITS.md

> *Defines the absolute boundaries an AI agent will never cross*

[![License: CC0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
[![Part of agent-md-specs](https://img.shields.io/badge/part%20of-agent--md--specs-blue)](https://github.com/totalmarkdown/agent-md-specs)
[![Maintained by TotalMarkdown](https://img.shields.io/badge/maintained%20by-TotalMarkdown.ai-8B5CF6)](https://totalmarkdown.ai)

**Maintained by TotalMarkdown.ai**
· License: CC0 1.0 Universal — Public Domain
· Part of [agent-md-specs](https://github.com/totalmarkdown/agent-md-specs)
· [Discussions](https://github.com/totalmarkdown/limits.md/discussions)

> TotalMarkdown.ai is currently in development. Star this repo to follow progress.

---

> **Canonical Source:** This spec is maintained in the main
> [agent-md-specs](https://github.com/totalmarkdown/agent-md-specs) repository.
> This repo is an auto-synced mirror for easy discovery and download.
> To report issues or submit changes, please open a PR or issue on the
> [main repository](https://github.com/totalmarkdown/agent-md-specs).

## What is LIMITS.md?

LIMITS.md is the safety specification. It defines hard stops — things the agent will NEVER do regardless of instructions, delegation, or context — and soft limits that can be overridden with explicit approval.

Every enterprise buyer's first question about an AI agent is: "What will it never do?" LIMITS.md provides the structured, auditable answer.

Create a LIMITS.md for any agent deployed in production, handling sensitive data, or with access to systems where mistakes have real consequences.

---

## Quick Start

```bash
curl -O https://raw.githubusercontent.com/totalmarkdown/limits.md/main/LIMITS.md
```

Add to your project root and customize for your agent.

---

## When to use LIMITS.md

- Any agent deployed in production environments
- Agents with access to sensitive data, financial systems, or external APIs
- Solo developers who want to prevent their coding agent from destructive actions

---

## Where it fits

Works alongside GUARDRAILS.md (runtime safety boundaries), PERMISSIONS.md (what the agent CAN access), ESCALATION.md (what happens when limits are hit), ENFORCEMENT.md (how limits are verified), and DELEGATION.md (limits constrain delegated authority).

---

## The Full Spec

→ [LIMITS.md](./LIMITS.md)

---

## Part of agent-md-specs

One of 178 specs in [agent-md-specs](https://github.com/totalmarkdown/agent-md-specs)
— the open standard library covering every dimension of AI agent configuration.

---

## Contributing

1. Open an issue describing your proposed change
2. Fork and make your edit
3. Open a PR — all contributions must be CC0

---

## License

[CC0 1.0 Universal](./LICENSE) — Public Domain.
Use freely for any purpose, no attribution required.

---

*Maintained by TotalMarkdown.ai*
*Part of [agent-md-specs](https://github.com/totalmarkdown/agent-md-specs)*
