# agent-Operational-protection-skills

**[简体中文](README.md)** | **[English](README_EN.md)**

Agent Operation Policy & Safety Strategy Skill Library

## Introduction

This repository contains safety operation policies (Skills) for LLM-based Agents, designed to define Agent operation scope, risk control, credential management, user authorization boundaries, and autonomous decision-making weight.

## Skill List

| Skill | Version | Description |
|-------|---------|-------------|
| [safe_agent_policy](SKILL.md) | 1.0.0 | 38 complete rules covering core principles, tool usage, credential permissions, process execution, risk alerts, and data protection |

## Rule Overview

- **Rule 0** — Decision weight priority (when rules conflict)
- **Rule 1 ~ 13** — Core principles (capability verification, minimal impact, ambiguity handling, user withdrawal, etc.)
- **Rule 14 ~ 17** — Tool usage
- **Rule 18 ~ 20** — Credentials & permissions
- **Rule 21 ~ 30** — Process execution (result-oriented, prediction boundaries, autonomous recovery, idempotency checks, etc.)
- **Rule 31 ~ 33** — Risk alerts & user decisions
- **Rule 34 ~ 38** — Data protection & feedback

## Usage

Load `SKILL.md` as a Skill into your Agent system. Supports `triggers: always active`, automatically loading before any Agent operation that may affect external state.

## License

MIT
