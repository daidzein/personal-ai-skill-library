# Agent Reach

## Overview

Category: Research & Information Retrieval
Type: CLI Tool / Agent Capability
Source: https://github.com/Panniantong/Agent-Reach
License: MIT

### Purpose

Agent Reach extends AI agent information retrieval
capabilities across multiple internet platforms.

It provides a unified CLI interface for searching,
reading, and retrieving information from supported
websites and social platforms.

The objective is to reduce the limitations of
standard web search and page-fetching capabilities.

---

## Core Capabilities

### 1. Web Research

- Search websites.
- Read webpage content.
- Retrieve information from URLs.
- Use alternative retrieval tools when necessary.

### 2. GitHub Research

- Search repositories.
- Read repository documentation.
- Explore issues.
- Explore pull requests and comments.

### 3. YouTube Research

- Search videos.
- Retrieve video information.
- Retrieve subtitles.
- Perform speech-to-text where configured.

### 4. Social Research

Depending on installed channels and authentication:

- Reddit
- X / Twitter
- LinkedIn
- Xiaohongshu
- Bilibili
- V2EX
- Xueqiu

Platform availability and authentication
requirements may change.

---

## Installation

Official repository:

https://github.com/Panniantong/Agent-Reach

Official installation instructions:

https://raw.githubusercontent.com/Panniantong/Agent-Reach/main/docs/install.md

### Installation Policy

Do not install similarly named packages from
unverified package registries.

The upstream project explicitly warns that
the PyPI package named `agent-reach` is not
the official project.

Use the official GitHub installation instructions.

The agent must:

1. Inspect the installation instructions.
2. Identify required dependencies.
3. Explain installation changes.
4. Request permission for command execution.
5. Install using the official procedure.
6. Run the official diagnostics.
7. Report available channels.

### Requirements

The environment may require:

- Python
- uv
- Git
- Browser-related dependencies
- Optional API keys
- Platform authentication

Check the upstream documentation for current
requirements.

---

## Basic Usage

Check available channels:

    agent-reach channels

Search YouTube:

    agent-reach youtube search "AI agents"

Read a webpage:

    agent-reach read https://example.com

General command pattern:

    agent-reach <channel> <action> [arguments]

Refer to the upstream documentation for
supported commands and arguments.

---

## Research Workflow

When performing research:

1. Identify the information required.
2. Identify the most relevant platform.
3. Check whether its channel is available.
4. Search for relevant information.
5. Retrieve original content.
6. Extract relevant findings.
7. Cross-check important claims.
8. Provide source links and findings.

Never treat search snippets as sufficient evidence
for important technical or business decisions.

Prefer original sources over secondary summaries.

---

## Security Considerations

### Authentication

Some platforms require authentication.

Agent Reach may reuse an existing browser session
for supported platforms.

Recommended practices:

- Prefer secondary accounts for automation.
- Never provide account passwords to an AI agent.
- Authenticate personally when required.
- Review browser session permissions.
- Never expose authentication cookies.

### API Keys

Never paste API keys into shared conversations.

Configure keys locally using the official
Agent Reach configuration procedure.

### Data Collection

Use the tool responsibly.

Respect:
- Platform terms of service.
- Privacy requirements.
- Copyright restrictions.
- Applicable data protection laws.

Agent Reach documents its primary functionality
as read-only retrieval, not posting or messaging.

---

## Maintenance

Everything installed by Agent Reach is managed
through its own local configuration directory.

Ask the agent to:

- Check installation status.
- Add or remove channels.
- Update Agent Reach.
- Diagnose broken channels.
- Uninstall Agent Reach.

Refer to upstream documentation before
performing maintenance operations.

---

## Integration Instructions

### Codex

Agent Reach can be installed as a local CLI
capability and used by Codex.

### OpenCode

Use the official installation instructions
and configure command execution permissions.

### ChatGPT

This catalog entry is a reference, not an
automatic installation.

ChatGPT can use the documentation to understand
the tool, but cannot directly execute a CLI
installed on the user's computer through
an ordinary browser conversation.

---

## Maintenance

Upstream:
https://github.com/Panniantong/Agent-Reach

Last verified: 2026-11-10

Verify supported platforms and installation
requirements against upstream before use.
