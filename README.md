# 100hires-portfolio
Portfolio project for 100Hires application

## Overview
This repository documents the setup process completed as part of the 
100Hires application process. It covers tool installation, environment 
configuration, and reflections on the experience.

---

## Tools Installed

| Tool | Purpose |
|------|---------|
| [Cursor IDE](https://cursor.com) | AI-powered code editor |
| Claude Code *(Cursor Extension)* | AI coding assistant by Anthropic |
| Codex *(Cursor Extension)* | AI code completion tool by Openai |

---

## Steps Completed

1. **Created a GitHub account** — [View detailed steps](GITHUB-SETUP.md)
2. **Installed Cursor IDE and extensions** — [View detailed steps](CURSOR-SETUP.md)
4. **Learned and used Git commands** — [View reference](GIT-COMMANDS.md)
5. **Created this public repository** and cloned it locally
6. **Wrote and committed this README.md**

---

## Challenges & How I Solved Them

**Challenge 1: Rusty knowledge of Git commands**
I had used Git before, but due to a long gap in practice, I had forgotten
most of the workflow. I refreshed my knowledge by searching through
developer documentation websites and consulting an AI assistant to clarify
each step. After that, the `git add`, `git commit`, and `git push` commands
came back to me quickly.

**Challenge 2: Finding the correct extensions in Cursor**
The search results showed multiple similar extensions. I resolved 
this by following the exact names provided in the instructions.

**Challenge 3: Author identity unknown when running git commit**
When running `git commit` for the first time, Git returned a fatal error
stating it could not detect my identity. The terminal showed:
`fatal: unable to auto-detect email address`

![Cursor IDE](screenshots/author-identify-unknown.png)

I solved this by configuring my Git identity using the following commands:
```bash
git config --global user.email "anggilenovo7@gmail.com"
git config --global user.name "Anggiawan"
```

After running both commands, the commit and push completed successfully.

---

## Screenshots

### Cursor IDE
![Cursor IDE](screenshots/cursor-ide.png)

### Extensions Installed (Claude Code & Codex)
![Cursor Extensions](screenshots/cursor-extensions.png)

### GitHub Repository
![GitHub Repo](screenshots/github-repo.png)

### Git Push Success
![Git Push](screenshots/git-push-success.png)

---

## Reflection
This process pushed me to learn by doing rather than waiting for 
instructions. I now have a basic understanding of Git, GitHub, and 
AI-powered development tools — and I'm ready for the next step.

---

*Submitted as part of the 100Hires application process.*