# Scaling Guide

## Goal

Describe how Agent Memory Matrix scales from personal memory to project, team, and organization memory systems.

## Level 1: Personal

Suitable for:
- one user
- one agent
- a small number of active projects

Focus:
- identity
- preferences
- active work
- local devices and tools

## Level 2: Project

Suitable for:
- one project with multiple resources
- one or more agents supporting a focused workstream

Focus:
- project goals
- project status
- project resources
- project decisions
- project recovery

## Level 3: Team

Suitable for:
- multiple people
- multiple agents
- shared resources across multiple projects

Focus:
- team membership
- team rules
- team-shared resources
- cross-project coordination

## Level 4: Organization

Suitable for:
- many teams
- many active projects
- organization-level governance and shared assets

Focus:
- policies
- inheritance rules
- scope boundaries
- cross-team structure
- organizational memory governance

## Scaling Recommendations

1. Start with markdown and templates
2. Add explicit scopes early
3. Add mapping files before adding automation
4. Introduce schemas when object count grows
5. Add search and RAG after structure becomes stable
6. Add databases only when markdown-only maintenance becomes insufficient

## Migration Path

- markdown-only
- markdown + metadata schemas
- markdown + vector retrieval
- markdown + structured database
- hybrid memory platform with scoped governance
