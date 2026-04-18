# SYSTEM

## Positioning

Agent Memory Matrix is a reference implementation and framework example for a matrix-based memory system.

It is not a container for all business projects. Instead, it provides:

- concepts
- directory patterns
- templates
- recovery rules
- inheritance rules
- mapping structures

that can be adopted by independent projects, teams, and organizations.

## Scope Levels

The framework is designed to support the following levels:

1. Personal
2. Project
3. Team
4. Organization

## Core Object Types

- People
- Agents
- Projects
- Teams
- Organizations
- Devices
- Tools
- Repositories
- Datasets
- Services
- Policies

## Core Design Principles

1. Separate framework from business projects
2. Separate work-unit memory from resource memory
3. Keep files human-readable and git-friendly
4. Support hierarchical inheritance
5. Allow future migration to structured storage and RAG systems
6. Preserve recovery paths for new agents and new machines

## Matrix Model

The system uses:

- a work-unit axis, representing personal/project/team/organization scopes
- a resource axis, representing reusable entities and assets
- mapping files that define relationships across scopes

## What This Repository Should Contain

- framework documentation
- templates
- schemas
- example structures
- recovery protocol
- inheritance model
- mapping examples

## What This Repository Should Not Contain

- arbitrary unrelated project data
- raw private secrets
- uncontrolled chat dumps
- production credentials

## Scaling Path

Phase 1: personal and project memory framework
Phase 2: team-level shared memory
Phase 3: organizational inheritance and governance
Phase 4: hybrid markdown + database + vector retrieval architecture
