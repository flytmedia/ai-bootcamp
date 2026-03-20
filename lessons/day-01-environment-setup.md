# Day 1 — Environment Setup

## Lessons Covered
1. Terminal Basics
2. Node.js, Git & GitHub
3. Installing Claude Code
4. IDEs (VS Code / Cursor)

## Key Concepts

### Terminal Commands
| Command | What It Does |
|---|---|
| `pwd` | Print current directory (where am I?) |
| `ls` / `ls -la` | List files (including hidden with -la) |
| `cd folder` | Move into a folder |
| `cd ..` | Go back one level |
| `cd ~` | Jump to home directory |
| `mkdir name` | Create a folder |
| `touch file` | Create an empty file |
| `rm file` | Delete a file (NO UNDO) |
| `rm -r folder` | Delete a folder and contents (NO UNDO) |

**Pro tips:** Up arrow = previous commands. Tab = auto-complete names.

### Node.js & npm
- **Node.js** = JavaScript engine outside the browser. Powers Claude Code and most AI tools.
- **npm** = Package manager (app store for code). `npm install` downloads dependencies.
- Verify: `node --version` (v20+), `npm --version` (10+)

### Git (Version Control)
- Tracks every change to your files over time. "Undo history on steroids."
- **Daily workflow:** `git add .` → `git commit -m "message"` → `git push`
- Configure once: `git config --global user.name` + `user.email`

### GitHub
- Where your code lives online. Portfolio + collaboration + backup.
- Create repos, push code, track history.

### Claude Code
- AI agent that lives in your terminal. Reads files, writes code, runs commands, builds projects.
- Install: `npm install -g @anthropic-ai/claude-code`
- Launch: `claude` in any project folder
- Key commands: `/help`, `/clear`, `/compact`, `/cost`, Ctrl+C (cancel), Ctrl+D (exit)

### Permission Modes
| Mode | Behavior | When to Use |
|---|---|---|
| Default | Asks before every action | Learning / unfamiliar code |
| Auto-accept | Approves file edits, asks for bash | Routine builds you trust |
| `--dangerously-skip-permissions` | Approves everything | Background workers, well-understood tasks |
| Plan mode (`/plan`) | Plans first, you approve, then executes | Complex multi-step tasks |

**Alias set up:** `yolo` = `claude --dangerously-skip-permissions`

### VS Code Extensions
| Extension | Purpose |
|---|---|
| Claude Dev (Anti-Gravity) | Claude AI chat inside the editor |
| ESLint | Catches code quality issues as you type |
| Prettier | Auto-formats code consistently |
| GitLens | Enhanced git — who changed what and when |

## Challenges Completed
- [x] Terminal commands — created project structure
- [x] Node.js + Git installed and configured
- [x] GitHub repo created, first commit pushed (github.com/flytmedia/ai-bootcamp)
- [x] Claude Code verified (v2.1.80)
- [x] VS Code extensions installed (all 4)
- [x] Hello World page built and pushed to GitHub
