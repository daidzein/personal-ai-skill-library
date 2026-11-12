# Karpathy Skills

## Overview

Category: Agent Engineering
Type: Coding Methodology / Agent Instructions
Source: https://github.com/duolahypercho/andrej-karpathy-skills
Original Inspiration: Andrej Karpathy
License: MIT (upstream repository)

### Purpose

Karpathy Skills provides a set of engineering principles
designed to improve the way AI agents approach software
development.

Its main objective is to prevent common AI coding failures:

- Making assumptions without clarification.
- Overengineering simple tasks.
- Modifying unrelated parts of a codebase.
- Producing code without verifying its correctness.

This library adopts the four core principles as a
cross-agent engineering standard.

---

## Core Principles

### 1. Think Before Coding

The agent must understand the problem before implementing
a solution.

Requirements:

- Identify the actual problem.
- State important assumptions.
- Identify missing information.
- Explain relevant trade-offs.
- Consider simpler alternatives.
- Ask for clarification when ambiguity affects
  implementation.

Do not silently guess when the decision could
materially affect the result.

### 2. Simplicity First

Implement the smallest solution that correctly solves
the requested problem.

Requirements:

- Avoid unnecessary abstractions.
- Avoid speculative features.
- Avoid excessive dependencies.
- Avoid unnecessary configuration options.
- Prefer standard libraries when sufficient.
- Do not build infrastructure without a real need.

The objective is maintainable software, not
maximum code volume.

### 3. Surgical Changes

Modify only what is necessary.

Requirements:

- Inspect the existing project before editing.
- Preserve existing architecture where practical.
- Avoid unrelated refactoring.
- Do not overwrite user work.
- Preserve existing behavior unless explicitly
  requested otherwise.
- Keep changes easy to review.

Every modification should have a clear reason.

### 4. Goal-Driven Execution

Every implementation task must have a verifiable
definition of success.

Requirements:

- Define expected behavior.
- Identify relevant tests.
- Run appropriate validation.
- Inspect errors and warnings.
- Report what was actually verified.
- Never claim completion without evidence.

If verification cannot be performed, explicitly
state the limitation.

---

## Standard Agent Workflow

For every coding task:

1. Understand
   - Inspect relevant files.
   - Understand project architecture.
   - Identify dependencies and constraints.

2. Plan
   - Define the expected result.
   - Identify the minimum required changes.
   - Explain important assumptions.

3. Implement
   - Make focused modifications.
   - Follow existing conventions.
   - Avoid unrelated changes.

4. Verify
   - Run relevant tests.
   - Check output.
   - Inspect the final diff.

5. Report
   - Summarize modifications.
   - List tests performed.
   - Identify unresolved issues.

---

## When To Use

Apply this methodology when:

- Developing Python applications.
- Building automation scripts.
- Modifying existing repositories.
- Debugging software.
- Refactoring code.
- Developing local AI tools.
- Building dashboards and GUIs.
- Maintaining production software.

---

## Integration Instructions

### Codex

Upstream repository provides a Codex-native plugin
and reusable skill.

Repository:
https://github.com/duolahypercho/andrej-karpathy-skills

Read its README for the current installation
and plugin-source instructions.

### OpenCode

Use this document as an instruction reference.
Adapt the principles into the project's AGENTS.md
or the relevant OpenCode configuration.

### ChatGPT

Use this document as a methodology reference.

Before coding, review the applicable principles
and use the session bootstrap instructions.

---

## Safety and Limitations

These guidelines do not replace:

- Software testing.
- Security reviews.
- Code review.
- Technical documentation.
- User approval for destructive operations.

The agent remains responsible for verifying
the correctness of its implementation.

---

## Maintenance

Upstream:
https://github.com/duolahypercho/andrej-karpathy-skills

Last verified: 2026-11-10

Check upstream for updates before relying on
installation instructions.
