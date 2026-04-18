# Agent Memory Matrix

A scalable matrix-based memory framework example for personal, project, team, and organizational memory management.

## Purpose

Agent Memory Matrix is a reference framework for building persistent memory systems that can scale across:

- personal assistants
- project copilots
- team knowledge systems
- organizational memory platforms

It is designed to support recovery by new machines, new agents, and new collaborators through a GitHub-native, structured memory layout.

## Core Idea

The framework organizes memory using two main dimensions:

- Work-unit dimension: personal, project, team, organization
- Resource dimension: people, agents, devices, tools, repositories, datasets, services, policies

The relationship between these dimensions is captured through matrix mapping files and layered recovery rules.

## Design Goals

- Persistent and portable memory
- Git-friendly and human-readable
- Agent-readable and recoverable
- Hierarchical expansion from individual to organization
- Extensible to RAG, databases, permissions, and automation later

## Suggested Reading Order

1. `SYSTEM.md`
2. `INDEX.md`
3. `docs/recovery-protocol.md`
4. `docs/inheritance-model.md`
5. `templates/`
6. `matrix/`

## Repository Structure

See `INDEX.md` and `SYSTEM.md` for structure and roles.
