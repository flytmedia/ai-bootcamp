# Day 2 — Claude Code Mastery (In Progress)

## Lessons Covered
1. How Claude Code Works
2. Effective Prompting

## Key Concepts

### Claude Code Architecture
- **Not a chatbot — an agent.** It doesn't just talk, it does things on your computer.
- Flow: You type → Claude reads context → picks tools → asks permission → executes → shows results
- Context window: ~200K tokens (~500 pages). Auto-compresses when full.

### The 9 Tools
| Tool | What It Does |
|---|---|
| Read | Read any file on your computer |
| Write | Create new files from scratch |
| Edit | Surgical modifications to existing files |
| Bash | Run terminal commands (git, npm, anything) |
| Glob | Find files by name pattern |
| Grep | Search for text inside files |
| Agent | Spawn sub-agents for parallel work |
| WebSearch | Search the internet |
| WebFetch | Download and read a webpage |

### The 4 Levels of Prompting

**Level 1 — Simple:** One-line instruction. Gets bare minimum.
> "Build me a to-do list app."

**Level 2 — Contextual:** Add context about your setup and goals.
> "I have a folder at day-01/todo-app/. Create a to-do list with clean design, add/delete tasks. Save as level2.html."

**Level 3 — Multi-Step:** Numbered steps, each one clear action.
> "1. Create HTML to-do app, white background, centered, responsive
> 2. Add tasks, mark complete, delete
> 3. localStorage persistence
> 4. Task counter 'X of Y completed'
> 5. Enter key to add"

**Level 4 — Role-Based:** Persona + constraints + output format.
> "You are a senior frontend developer. Build a to-do app:
> 1. Vanilla HTML/CSS/JS only — no frameworks
> 2. White background, Inter font, minimal aesthetic
> [10 specific requirements + constraints]"

### The 5 Power Moves
1. **Be specific about paths** — say `src/config/database.ts`, not "the config file"
2. **State what you DON'T want** — "no external libraries" prevents bloat
3. **Break big tasks into steps** — numbered lists beat essays
4. **Iterate, don't restart** — refine the output, don't throw it away
5. **Show examples** — one example of expected output = perfect results

### Prompting Formula (Reinforced)
- **Context** → What's the situation?
- **Task** → What do you want?
- **Constraints** → What are the rules?
- More specific = fewer wrong assumptions = better output
- Clarity > length. 3 bullet points > 500-word paragraph.

## Challenges Completed
- [x] Architecture Speed Run — identified tools, read package.json, checked permission mode
- [x] Prompt Level-Up Ladder — built same to-do app at 4 prompt levels
- [x] Boss Level — Level 4 with no-frameworks constraint, vanilla JS only
