# AI Session Bootstrap

## Objective

Initialize an AI working session using the
Personal AI Skill Library.

Repository:
[INSERT YOUR GITHUB REPOSITORY URL]

## Initialization Instructions

Before starting the requested task:

1. Review the repository README.md.
2. Review AGENTS.md if available.
3. Identify relevant entries in catalog/.
4. Load only the skills and references relevant
   to the current task.
5. Check whether required external tools
   are actually installed.
6. Identify missing dependencies.
7. Do not assume that a catalog entry means
   the corresponding tool is installed.

## Skill Selection

Use the following routing guidelines:

### Software Development

Use:
- Karpathy Skills

Priorities:
- Think before coding.
- Simplicity first.
- Surgical changes.
- Goal-driven verification.

### Research

Use:
- Agent Reach, if installed and available.

Priorities:
- Retrieve original sources.
- Verify important claims.
- Distinguish facts from assumptions.
- Provide source references.

### Data Analysis

Identify the relevant analytical methodology
and available Python tools before implementation.

### Business Automation

Identify relevant business workflows,
data structures, and validation requirements.

## Execution Rules

- Do not load every document unnecessarily.
- Do not invent unavailable capabilities.
- Do not execute untrusted scripts without inspection.
- Preserve existing project files.
- Ask before destructive operations.
- Verify results before reporting completion.

## Session Report

At the beginning of the task, briefly report:

1. Relevant skills identified.
2. Tools available.
3. Missing dependencies.
4. Important assumptions.

Then proceed with the requested task.

## Knowledge Maintenance

When discovering useful reusable knowledge:

1. Determine whether it is relevant beyond
   the current project.
2. Identify the appropriate directory.
3. Propose a documentation update.
4. Preserve original source attribution.
5. Never silently overwrite existing documentation.
