# Inheritance Model

## Principle

Lower scopes inherit context from higher scopes, while being allowed to add or override local details.

## Scope Order

1. Organization
2. Team
3. Project
4. Personal / local task context

## Rules

- Higher scopes define shared policy and common context
- Lower scopes refine operational detail
- Local scope may override local behavior, but should not silently contradict higher-level policy
- When in conflict, the nearest valid scope wins unless an explicit global constraint forbids override

## Examples

- An organization may define security and documentation policies
- A team may define collaboration and review rules
- A project may define milestones and resource allocation
- A local agent task may define the immediate next action

## Design Intention

This model allows the same framework to scale from one person to a whole organization without flattening all memory into a single undifferentiated space.
