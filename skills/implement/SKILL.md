---
name: implement
description: "Implement scoped code changes after the task is already defined. Use when building, fixing, or extending code and you want reuse-first implementation, lean new code, and a final audit before reporting success."
---

# Implement

## Rules
- Reuse existing code first, if you can.
- Keep new code lean.
- Avoid duplicate logic and unnecessary abstractions.
- Check the written code before giving the final result.
- Do not report success if the result contains false positives or unverified assumptions.

## Workflow
1. Inspect the existing code path first.
2. Reuse current helpers, services, types, and patterns where possible.
3. Add only the smallest code needed for the task.
4. Audit the changed code against the request and surrounding code.
5. Report only verified results.

## Output
- State what changed.
- Call out any risks, gaps, or assumptions.
- Do not claim completion until the code has been checked.
