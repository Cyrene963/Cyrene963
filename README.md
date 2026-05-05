# Hi, I'm Cyrene

CS student at ZJU. I build AI agent systems and contribute to open source.

## What I Work On

**[hermes-patches](https://github.com/Cyrene963/hermes-patches)** — Community patch collection for [Hermes Agent](https://github.com/NousResearch/hermes-agent)

- 39 patches covering security, performance, and multi-user isolation
- 99.2% token reduction per conversation (~12000 → ~200 tokens)
- 16-layer security hardening (SSRF, file safety, secret redaction, env protection)
- Multi-user session/memory isolation with CJK search support
- FTS5-based semantic skill retrieval
- One-command install, auto-detects merged upstream patches

## Open Source Contributions

Contributions to [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent):

| PR | Title | Status |
|----|-------|--------|
| [#17989](https://github.com/NousResearch/hermes-agent/pull/17989) | Multi-user session & memory isolation | Open |
| [#18316](https://github.com/NousResearch/hermes-agent/pull/18316) | Hybrid skill selector with FTS5 semantic retrieval | Open |
| [#18849](https://github.com/NousResearch/hermes-agent/pull/18849) | Skill enforcement framework & compliance plugin | Open |
| [#19064](https://github.com/NousResearch/hermes-agent/pull/19064) | Credential pool fix for /model switching (CLI path) | Open |
| [#19163](https://github.com/NousResearch/hermes-agent/pull/19163) | Cross-channel memory unification & auto-setup | Open |
| [#19682](https://github.com/NousResearch/hermes-agent/pull/19682) | Fix credential pool key ambiguity | Open |
| [#19686](https://github.com/NousResearch/hermes-agent/pull/19686) | Custom provider compatibility fixes | Open |

Also merged community PRs for: inference model empty response detection, FTS5 hyphen quoting, per-turn time injection, cost estimation fix, and memory safety hardening.

## Tech Stack

```
Languages    Python · Shell · JavaScript
AI/ML        LLM Agent Architecture · Prompt Engineering · Multi-user Systems
Infra        Linux · SQLite (FTS5) · systemd · Cloudflare
Tools        Git · GitHub Actions · Vercel
```

## Stats

![Cyrene963's GitHub stats](https://github-readme-stats.vercel.app/api?username=Cyrene963&show_icons=true&theme=radical&hide=stars)
