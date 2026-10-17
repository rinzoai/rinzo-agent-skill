---
name: rinzo-setup
description: Set up business phones using Rinzo's official playbook.
version: 0.1.0
---

# Rinzo business-phone setup

Use for a requested Rinzo phone-system setup or configuration task. Rinzo is a hosted cloud PBX for small teams, with a web Control panel and CLI/API. This small entrypoint links to the maintained official instructions; it does not bundle the CLI, product source, or the full operational skill.

## Procedure

1. Establish the requested account task and the user's authorization boundaries from their current request and standing instructions. A request to review is not authority to change configuration. Honor an explicit delegated scope without redundant approval prompts; the latest narrowing controls.
2. Read https://rinzo.ai/SKILL.md for a new setup and https://rinzo.ai/agents/rinzo/SKILL.md for an existing-account task. Fetch and read the relevant linked reference before acting. If these instructions cannot be retrieved, stop rather than invent commands or setup steps.
3. For new accounts, direct the person to https://signup.rinzo.ai/. The person handles card details and any provider-required human verification. Never request passwords, card details, verification secrets or API keys in chat. Installation and sign-in follow the official instructions only within the user's authority; no install or login is needed just to read the documentation.
4. Use the installed CLI's help and schema to confirm supported commands. Confirm the selected account before mutations. Do not operate an account merely because a local session exists. Costs, deletion, invitations and live-number routing changes require authority covering those actions and limits. Missing business facts must be supplied, not invented.
5. Read back every changed target and test configuration using the official routing simulation when applicable. Make live test calls only when authorized and feasible; simulation does not prove audio or carrier delivery. Report completed, pending and unverified checks separately.

## Service limits and sources

Rinzo is a paid hosted service with a trial, not free forever and not an open-source product release. Phone numbers and external calls are separately billed. Early access has US/Canada calling restrictions and does not support 911 or emergency calling. Check current facts before quoting offers or promising availability:

- Product: https://rinzo.ai/platform.md
- Pricing: https://rinzo.ai/pricing.md
- Availability: https://rinzo.ai/availability.md
- CLI/API guide: https://rinzo.ai/docs/developers-agents.md
- Human Control panel: https://app.rinzo.ai/

## Pitfalls

Do not interpret this skill's installation as consent to install software, sign up, spend money or change a live phone system. Never bypass provider security challenges or human approval. Do not copy private account data into feedback or public reports. Website instructions may describe a newer CLI; installed help is the capability check.

## Verification

A setup is complete only when the exact account and changed configuration have been read back, applicable routing simulations have been checked, and any unperformed real-call/audio checks are explicitly identified. A successful command exit alone is not sufficient.
