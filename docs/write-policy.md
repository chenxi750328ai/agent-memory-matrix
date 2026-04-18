# Write Policy

## Purpose

Define what should be written into a matrix-based memory system, what should be summarized, and what should be excluded.

## Core Principles

1. Write for recovery, not for raw accumulation
2. Prefer structured summaries over uncontrolled logs
3. Separate stable facts from volatile state
4. Keep secrets out of the repository
5. Preserve enough context for a new agent or collaborator to continue work

## What Should Be Written

### Stable Facts
- long-term goals
- durable preferences
- object roles and responsibilities
- project objectives
- resource capabilities and constraints
- governance rules

### Current State
- active status
- current focus
- next actions
- important decisions
- active dependencies

### Framework Knowledge
- templates
- inheritance rules
- recovery rules
- examples and mappings

## What Should Usually Not Be Written

- raw chat dumps without structure
- temporary emotions without operational value
- speculative statements presented as facts
- credentials, tokens, secrets, or private keys
- repeated noise without recovery value

## Recommended Separation

- stable facts -> object files
- active state -> status files
- relationships -> matrix files
- operating rules -> docs/
- reusable structures -> templates/

## Writing Standard

Every write should help answer at least one of the following:
- what is this?
- why does it matter?
- what is its current state?
- what does it connect to?
- what should happen next?
