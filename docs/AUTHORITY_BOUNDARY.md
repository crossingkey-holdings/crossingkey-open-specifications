# Authority Boundary

## Principle

A component can possess a capability without being authorized to use it.

## Public specification rule

When a system can perform consequential external actions, a specification should make clear:

1. who or what grants authority;
2. the scope of that authority;
3. how the scope is represented;
4. what state is checked before execution;
5. how completion is evidenced;
6. what happens when authority is absent, expired, or ambiguous.

## Why this matters

This distinction reduces a common failure mode in agentic and automated systems: treating tool availability as permission to act.
