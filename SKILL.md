---
name: vps-backup-recovery-skill
description: "description: Recover SSH access to a VPS after the client key is lost/wiped, and set up automated VPS data backup to a private GitHub repo with daily restore capability."
version: 1.0.0
author: Community
license: MIT
platforms: [linux, macos, windows]
tags: [devops]
---

# Vps Backup Recovery - Skill

description: Recover SSH access to a VPS after the client key is lost/wiped, and set up automated VPS data backup to a private GitHub repo with daily restore capability.

## Install

```bash
cp -r <skill-name> ~/.hermes/skills/devops/vps-backup-recovery/
```

## Usage

Invoke your AI agent with a clear instruction matching this skill's purpose. Examples:

- *"Use this skill to <primary task>"*
- *"Load devops/vps-backup-recovery and <do something>"*

Replace `<primary task>` with the actual task this skill performs.

## Safety & data rules

- Never commit private keys, seed phrases, API tokens, or personal data to version control.
- Use placeholders (`<YOUR_...>`) in all examples.
- Read the full README.md in this repo for advanced usage, API reference, and step-by-step workflows.

## Notes

- Keep credentials out of chat history and source control.
- Validate all outputs before acting on them.
