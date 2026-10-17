# Rinzo agent setup entrypoint

[Rinzo](https://rinzo.ai/) is a hosted business phone system for small teams, usable through a web Control panel, CLI and account API. This repository contains a small agent-skill entrypoint to Rinzo's maintained public setup documentation. It is not the product source or an independent copy of the full operational skill.

## Use without installing anything

Give your agent this request:

> Set up my business phones with Rinzo. Follow https://rinzo.ai/SKILL.md

For an existing account task, start at https://rinzo.ai/agents/rinzo/SKILL.md. The current official documentation is authoritative; this entrypoint deliberately avoids pinned CLI versions, copied reference trees and executable installers.

## Optional skill installation

With Node.js/npm available, inspect this repository and use the open skills CLI if you choose:

    npx skills add cryptoaaron/rinzo-agent-skill --skill rinzo-setup

This installs agent instructions, not a Rinzo account or the Rinzo CLI. Installation is not authority to spend, change phone configuration or place calls. Follow your agent's normal permission model and the official playbook. No telemetry installations were performed to manufacture directory ranking; a public repository is not proof of skills.sh indexing.

## What Rinzo does

Users/extensions, existing desk phones and softphones, browser calling, office-hours and holiday routing, auto-attendants, ring groups, forwarding, voicemail and call history. Humans and authorized agents work against the same account configuration.

Rinzo is paid with a trial, not free forever. Numbers and external calls are separate. It is in early access with regional US/Canada restrictions, and 911/emergency calling is not supported. Read current [pricing](https://rinzo.ai/pricing/), [availability](https://rinzo.ai/availability/) and [developer documentation](https://rinzo.ai/docs/developers-agents/) before making a decision.

## Provenance

Prepared by Rook, Rinzo's AI operations assistant, as an authorized public documentation entrypoint. The text summarizes already-public Rinzo instructions and links to their maintained source. No private backend, CLI implementation, customer data, credentials or internal operations documents are included. This publication does not grant a license to Rinzo's product source or relicense linked material. No open-source license is asserted for that material.

Contact: rook@rinzo.ai.
