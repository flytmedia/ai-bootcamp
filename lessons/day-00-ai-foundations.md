# Day 0 — AI Foundations

## Lessons Covered
1. Welcome & What You'll Learn
2. The AI Landscape
3. How AI Thinks
4. The Tool Stack
5. Business Case Studies
6. The Mindset Shift & Exercise

## Key Concepts

### LLMs (Large Language Models)
- Predict the next word based on patterns learned from billions of pages of text
- Not a database lookup — statistical pattern matching at massive scale
- Big players: Claude (Anthropic), GPT-4 (OpenAI), Gemini (Google), Llama (Meta)

### Chatbot vs Agent
- **Chatbot:** Answers questions. You ask, it responds. One turn.
- **Agent:** Takes actions. Checks weather → reschedules meeting → notifies attendees → updates calendar. Multi-step, autonomous execution.
- Most people are stuck at chatbot level. The goal is agent level.

### Tokens & Context Windows
- AI reads **tokens** (chunks of text), not words. ~1 token = 0.75 words
- **Context window** = how much AI can "see" at once (its working memory)
- Claude: ~200K tokens (~150K words). GPT-4: ~128K. Gemini: up to 1M.
- More context = more accurate responses. Give AI MORE info, not less.

### Prompting Formula
- **Context** — What's the situation? Who is this for?
- **Task** — What exactly do you want done?
- **Constraints** — What are the rules? Format? Length? Style?

### Temperature
- 0.0 = Maximum precision (coding, data analysis)
- 0.3–0.7 = Balanced (business writing, emails)
- 0.7–1.0 = Maximum creativity (brainstorming, content)

### The 4-Layer Tool Stack
1. **IDE** (Layer 1) — Visual workspace (VS Code, Cursor)
2. **CLI** (Layer 2) — Terminal commands (Claude Code)
3. **APIs** (Layer 3) — Software-to-software communication
4. **MCPs** (Layer 4) — AI connects to external tools automatically (USB ports for AI)

### The 5-Step Automation Pattern
1. **IDENTIFY** — Find a repetitive task
2. **MAP** — Write down every step
3. **AUTOMATE** — Use the right tool combo
4. **HUMAN-IN-THE-LOOP** — AI drafts, you approve
5. **ITERATE** — Start at 80%, reach 95% over time

### Mindset
- You're not becoming a developer. You're becoming an **AI operator**.
- AI replaces **tasks**, not jobs. People who direct AI replace people who don't.
- Iterate, don't give up after one bad prompt. Every bad output is data.

## Challenges Completed
- [x] AI Spotter — identified 3 AI-powered tools I already use
- [x] Prompt Transformer — rewrote a vague prompt using Context → Task → Constraints
- [x] First Automation — mapped my daily lead prep using the 5-step pattern
- [x] Boss Level: Automation Audit — 5 candidates, top 2 mapped, mission declared
