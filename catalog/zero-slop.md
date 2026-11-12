# Zero Slop

## Overview

Category: Writing Quality / Agent Engineering
Type: AI Agent Skill / Writing Linter / CLI
Source: https://github.com/manavmishra/ZeroSlop
License: MIT

### Purpose

Zero Slop is an open-source agent skill designed
to identify and remove common AI-generated writing
patterns without compromising the original meaning.

It helps AI agents produce writing that is:

- More natural.
- Less formulaic.
- More concise.
- Less promotional.
- More consistent with the author's voice.
- Factually faithful to the original draft.

The tool should improve writing quality rather
than simply make text sound more human.

---

## Core Capabilities

### 1. AI Writing Pattern Detection

Identifies common writing patterns associated
with AI-generated text.

Examples:

- Canned introductions.
- Generic conclusions.
- Excessive transitions.
- Significance inflation.
- Promotional vocabulary.
- Repetitive sentence structures.
- Artificially balanced contrasts.
- Overuse of formatting.

### 2. Writing Score

Provides a numerical writing score from 0 to 100.

The score identifies patterns worth reviewing.

Important:
The score is NOT proof that a human or AI
authored a particular text.

It must not be used as an authorship detector.

### 3. Guided Rewriting

Helps agents revise flagged passages while
preserving:

- Original meaning.
- Technical accuracy.
- Important details.
- Author's intended tone.
- Relevant qualifications.
- Numerical values.
- Citations and references.

### 4. Source Detail Verification

Checks whether important information survives
the rewriting process.

Examples:

- Names.
- Numbers.
- Quotations.
- URLs.
- Code.
- Tables.
- File paths.
- Document structure.

### 5. Private Writing Preferences

Supports learning from user-provided examples:

- Original AI draft.
- User-edited version.
- Explanation of the preferred change.

Private learning data is stored locally
under the configured ZERO_SLOP_HOME directory.

---

## Eight-Stage Editing Workflow

Zero Slop uses eight editing stages.

| Stage | Function |
|---|---|
| 1. Scorer | Identify writing patterns |
| 2. Interpreter | Understand meaning and audience |
| 3. Rewriter | Remove unnecessary patterns |
| 4. Fact Gate | Verify important details |
| 5. Copy Desk | Correct grammar and consistency |
| 6. Read-Aloud Editor | Improve readability |
| 7. Verifier | Compare against original |
| 8. Finalizer | Apply safe final improvements |

These are workflow stages, not eight separate
AI models.

---

## Installation

Official repository:

https://github.com/manavmishra/ZeroSlop

### Codex / Compatible Skill Agents

Official installation command:

    npx skills add manavmishra/ZeroSlop --global

Main command:

    /zero-slop your writing

Inspect without rewriting:

    /zero-slop inspect your writing

### Local CLI

Score a document:

    npx zero-slop score draft.md

Run batch scoring from a cloned repository:

    python3 scripts/slopscore.py --batch drafts/ --gate 25

The CLI editing workflow has additional
requirements documented upstream.

### Browser Editor

https://zero-slop.ai

### MCP

Official endpoint:

https://mcp.zero-slop.ai/mcp

MCP usage requires a compatible client
and appropriate configuration.

---

## Recommended Usage

Apply Zero Slop when producing:

- LinkedIn posts.
- Professional emails.
- Technical reports.
- Research summaries.
- Business proposals.
- Documentation.
- Product descriptions.
- Educational materials.
- Public-facing articles.

Do not automatically apply it to every
technical or structured output.

---

## Personal Writing Policy

The following rules apply when using Zero Slop
within this Personal AI Skill Library.

### Preserve the Author

Do not replace the author's personality
with generic conversational language.

Do not force every sentence to sound informal.

### Preserve Technical Precision

Never remove important technical terminology,
scientific qualifications, measurements,
or regulatory references merely to reduce
the writing score.

### Preserve Meaning

Never invent details to improve readability.

Never remove important caveats.

Never change numerical values without evidence.

### Avoid Artificial Humanization

The objective is not to trick AI detectors.

The objective is to improve clarity, precision,
readability, and authentic communication.

### Respect Language Context

Adapt editing to the language of the original text.

For Indonesian writing, preserve natural Indonesian
expression rather than mechanically translating
English writing conventions.

For technical English, preserve standard
scientific and industrial terminology.

---

## Integration Instructions

### Codex

Install the upstream skill using the official
Skills CLI.

### OpenCode

Use the official skill installation mechanism
supported by the current OpenCode version.

Verify compatibility before installation.

### ChatGPT

Use the uploaded SKILL.md or relevant documentation
as a writing methodology reference.

For direct browser-based access, the upstream
browser editor or compatible MCP integration
may be used.

A catalog entry alone does not install the tool.

---

## Security and Privacy

- Review scripts before execution.
- Understand whether an operation is local
  or uses a hosted service.
- Do not send confidential documents to
  hosted endpoints without approval.
- Keep private writing preferences local.
- Never commit private learning data.
- Disable optional update checks if required
  by local policy.

Optional update-check setting:

    ZS_NO_UPDATE_CHECK=1

---

## Limitations

1. A low writing score does not guarantee
   good writing.
2. A high score does not prove AI authorship.
3. Automated rewriting can still introduce errors.
4. Technical accuracy must be independently verified.
5. Language-specific patterns may require
   additional human review.

---

## Maintenance

Upstream:
https://github.com/manavmishra/ZeroSlop

Last verified: 2026-11-12

Check upstream documentation before installation
or updating.
