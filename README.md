# Self-Maintaining AI Agent Engineering System

A project-agnostic engineering framework for building AI coding agents that can understand, develop, test, review, and maintain software repositories over time.

## Overview

This project provides a master prompt for setting up a persistent AI coding-agent engineering system inside an existing repository.

Instead of relying on agents to repeatedly understand a codebase from scratch, it establishes a structured environment containing project knowledge, reusable skills, specialized agents, verification workflows, and evaluation mechanisms.

The goal is simple: **describe what you want to build, and let your coding agent handle the engineering workflow.**

## Key Features

- **Project-Agnostic:** Adapts to different project types, languages, frameworks, and runtime environments.
- **Repository Understanding:** Inspects the actual codebase, architecture, dependencies, and execution flows.
- **Persistent Knowledge:** Maintains architecture documentation, feature maps, conventions, and engineering decisions.
- **Reusable Skills:** Establishes specialized workflows for implementation, debugging, testing, code review, and maintenance.
- **Specialized Subagents:** Organizes engineering responsibilities across agents when supported.
- **Automated Verification:** Establishes appropriate testing and runtime verification procedures.
- **Agent Evaluation:** Evaluates agent behavior and identifies recurring weaknesses.
- **Self-Maintenance:** Updates project knowledge and improves agent workflows as the codebase evolves.
- **Quality Enforcement:** Uses automated checks and architectural constraints to prevent recurring mistakes.

## Supported Project Types

Designed to adapt to different software projects, including:

- Web and full-stack applications
- Backend services and APIs
- Android and iOS applications
- Desktop applications
- CLI tools
- Libraries and SDKs
- AI/ML systems
- Data pipelines
- Games and interactive applications
- Embedded systems and firmware
- Infrastructure and developer tools
- Compilers and other specialized software

These are examples, not restrictions. The system discovers the repository's actual architecture instead of assuming a particular technology stack.

## Compatible Coding Agents

The master prompt is designed to work with AI coding environments such as:

- OpenAI Codex
- Claude Code
- Cursor
- GitHub Copilot
- Other repository-aware coding agents

Actual configuration and feature support depend on the active coding environment.

## Getting Started

1. Clone or open your existing project repository.
2. Open it using your preferred AI coding agent.
3. Copy the master prompt from this repository.
4. Provide it to your coding agent.
5. Allow the agent to inspect the repository and establish the engineering infrastructure.
6. Review the generated configuration, documentation, and verification results.

The agent should inspect the existing project before making changes and adapt the system to its actual architecture.

## Design Philosophy

The system is built around a continuous engineering workflow:

**Discover → Understand → Plan → Implement → Test → Verify → Review → Maintain → Improve**

Its core principles are:

- Evidence over assumptions.
- Project discovery over predefined architecture.
- Verification over confidence.
- Automated enforcement over repeated reminders.
- Incremental improvement over unnecessary complexity.
- Persistent knowledge over repeated manual explanations.

## Important Notes

- This is an engineering framework and master prompt, not a standalone coding agent or application.
- The coding agent executes the setup inside your target repository.
- Generated skills, subagents, hooks, and configurations depend on the capabilities of your coding environment.
- Always review generated changes before using them in production.

## License

MIT License (if you choose to distribute this project under MIT).