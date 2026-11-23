# Agent Router — GitHub Trending Kit

## Agent Routing Rules
| Trigger / Task | Agent File | Linked Skills |
| :--- | :--- | :--- |
| Pre-launch repo audit, GitHub topics/tags, README conversion, or launch posts | `agents/launch-director.md` | `github-seo-topics`, `readme-conversion-audit`, `launch-copy-generator` |

## Active Agent Visibility Rule
* **Entrance:** `[ 🚀 LAUNCH DIRECTOR // TRENDING AUDIT ]`
* **Sign-Off:** `[ ⭐ LAUNCH READY ]`

<!-- AGENT-ETIQUETTE:START version=v1.1.0 -->
## Agent Etiquette Protocol (Layer 3 — Pinned `v1.1.0`)
- **Hierarchy:** Platform constraints (Layer 1) → Repository rules above (Layer 2) → Agent Etiquette (Layer 3) → Task-specific skills (Layer 4) → Handoffs (Layer 5).
- **Behavioral Rules:** Load `skills/agent-etiquette/SKILL.md` (zero filler, verified actions only, Rule of 2 retry cap, max 3 concurrent specialists).
- **Handoff Contract:** Validate inter-agent handoffs against `schemas/handoff.json` (`node scripts/validate-handoff.mjs <file>`).
<!-- AGENT-ETIQUETTE:END -->

## 🎨 Agent Active Signature (Visual Identification)
Whenever an AI agent activates or applies `github-trending-kit`, it **MUST** open its response/step with this exact monospace signature callout (Indigo `#6366f1`) so the user can immediately see when `github-trending-kit` is being used:

```markdown
> 🟣 `[GITHUB-TRENDING-KIT // LAUNCH DIRECTOR]` — *Active on this step*
```
