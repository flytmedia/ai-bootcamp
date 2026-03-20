# AI Bootcamp — Master Reference

> Everything I've learned, organized for quick reference after the bootcamp.
> Updated after each lesson. Lesson details in `lessons/` folder.

## Progress

| Day | Topic | Status |
|---|---|---|
| 0 | AI Foundations | Done |
| 1 | Environment Setup | Done |
| 2 | Claude Code Mastery | In Progress |
| 3 | — | — |
| 4 | — | — |
| 5 | — | — |
| 6 | — | — |
| 7 | — | — |
| 8 | — | — |
| 9 | — | — |
| 10 | — | — |

## Quick Reference

### Prompting Formula
```
Context (who/what/where) + Task (what to do) + Constraints (rules/format)
```

### Prompt Levels
1. **Simple** — one line, bare minimum output
2. **Contextual** — add file paths, tech stack, features
3. **Multi-step** — numbered list, one action per step
4. **Role-based** — persona + constraints + output format = production quality

### Automation Pattern
1. IDENTIFY — find the repetitive task
2. MAP — write down every step
3. AUTOMATE — pick the right tools
4. HUMAN-IN-THE-LOOP — AI drafts, you approve
5. ITERATE — 80% → 95% over time

### Claude Code Tools
Read, Write, Edit, Bash, Glob, Grep, Agent, WebSearch, WebFetch

### Permission Modes
- **Default** — asks before everything (learning)
- **Auto-accept** — approves file edits (routine work)
- **YOLO** (`--dangerously-skip-permissions`) — approves everything (background workers)

### Terminal Cheat Sheet
```
pwd          — where am I?
ls -la       — list everything including hidden
cd dir       — move into directory
cd ..        — go back
mkdir name   — create folder
touch file   — create file
rm file      — delete (NO UNDO)
```

### Git Daily Workflow
```
git add .
git commit -m "what I did"
git push
```

### Token Math
- 1 token ≈ 0.75 words
- Claude context: ~200K tokens (~150K words)
- More context = better output

### Temperature Guide
- 0.0–0.3 = precision (code, data)
- 0.3–0.7 = balanced (business writing)
- 0.7–1.0 = creative (brainstorming, content)

### Tool Stack Layers
1. **IDE** — VS Code (visual workspace)
2. **CLI** — Claude Code (AI in terminal)
3. **APIs** — Software-to-software connections
4. **MCPs** — AI auto-connects to external tools

## Security Foundation (Pre-Bootcamp)

Built before starting the bootcamp — security-first workspace:

- `.env.agents` pattern — single source of truth for all credentials
- Credential hierarchy: L1 Critical → L2 Sensitive → L3 Restricted → L4 Public
- Pre-commit hook blocks 14 secret patterns from ever being committed
- MCP wrapper script loads credentials at runtime (zero secrets in config)
- Credential registry with rotation tracking + automated expiry alerts
- Health check script monitors live services, alerts via Telegram
- Incident response playbook (P1-P4 severity, 5-step recovery)
- Client provisioning: one command creates isolated env per client
- Data Processing Agreement template for client work

Details: `../` (parent workspace — DEPLOY_CHECKLIST.md, INCIDENT_RESPONSE.md, credentials.md, scripts/)

## My Automation Targets

1. **Daily lead prep** — Apify scrape → Claude dedup → GHL import → Telegram approval (7-10 hrs/week saved)
2. **Client onboarding** — Stripe webhook → GHL setup → portal code → welcome email → kickoff link (2-3 hrs/client saved)
3. **Morning briefing** — GHL pipeline + Stripe payments + calendar + email → one Telegram message
4. **Post-call logging** — voice note → transcribe → GHL update + pipeline move + notes
5. **Website builds** — intake form → Claude generates site → Cloudflare deploy → client preview link

## Lesson Files

- `lessons/day-00-ai-foundations.md`
- `lessons/day-01-environment-setup.md`
- `lessons/day-02-claude-code-mastery.md`
