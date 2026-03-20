# AI Bootcamp

## What
- Project: AI agent development bootcamp — learning to build, deploy, and manage AI agents for business automation
- Owner: Ethan Morgan, FLYT Media (AI automation agency for home service businesses)
- Stack: HTML/CSS/JS (vanilla), Node.js, Python, Supabase, n8n, Vercel
- Repo: github.com/flytmedia/ai-bootcamp

## Structure
- `day-XX/` — Daily project files and builds
- `lessons/` — Key concepts and notes per lesson
- `BOOTCAMP.md` — Master reference document (updated each lesson)

## Rules
1. Always use vanilla HTML/CSS/JS unless a lesson specifically requires a framework
2. Use conventional commits: `day X: description of what was built`
3. Never hardcode secrets — use .env.agents (gitignored)
4. Push to GitHub after every completed lesson or challenge
5. Write all community posts from Ethan's first-person perspective

## Don'ts
- Don't skip challenges — complete every task in every lesson
- Don't install unnecessary dependencies — keep it lean

## Style
- White backgrounds, clean minimal design, Inter font stack
- Black and white aesthetic (FLYT Media brand: #000 primary, #fff background)
- Mobile responsive by default

## Security
- All credentials in `.env.agents` — never in code, never in chat
- `.gitignore` covers `.env*`
- Pre-commit hook blocks secret patterns

## Decision Protocol
- Simple tasks: just do it
- Moderate tasks: brief plan, then execute
- Complex tasks: present options, wait for Ethan's approval

@lessons/day-00-ai-foundations.md
@lessons/day-01-environment-setup.md
@lessons/day-02-claude-code-mastery.md
