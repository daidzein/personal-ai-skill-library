# Start Here — Personal AI Skill Library

## Universal Session Initialization Prompt

Use this prompt at the beginning of every new AI session.

---

### Initialization

Initialize using my Personal AI Skill Library:

**Repository:**
https://github.com/username/personal-ai-skill-library

Read the `README.md` and `AGENTS.md` first.

Identify the relevant skills and tools for my current task.

Do not assume tools are installed.

Follow the documented methodology.

Report the relevant capabilities and dependencies before proceeding.

### My Task

[DESCRIBE YOUR TASK]

---

## Agent Instructions

Before executing the task:

1. Identify the task category.
2. Locate relevant entries in `catalog/`.
3. Read only the relevant skill documentation.
4. Check actual tool availability.
5. Identify missing dependencies.
6. Report capabilities and limitations.
7. Follow applicable engineering and security rules.

## Important Rules

- Do not load every skill unnecessarily.
- Do not fabricate tool availability.
- Do not execute untrusted scripts without inspection.
- Preserve existing project files.
- Verify results before reporting completion.
- Prefer original upstream documentation.

## Expected Initial Response

The agent should briefly report:

- Relevant skills identified.
- Tools currently available.
- Missing dependencies.
- Proposed execution methodology.

Then proceed with the task.

---

**Purpose:** This document is the universal starting point for ChatGPT, Codex, OpenCode, and other compatible AI agents.
