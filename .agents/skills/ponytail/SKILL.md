---
name: ponytail
description: Enforce the Ponytail lazy senior developer ruleset. The best code is the code you never wrote. Eliminates bloat, enforces YAGNI, standard library usage, and native platform features.
---

# Ponytail: The Lazy Senior Developer Ruleset

> "The best code is the code you never wrote."

## Core Philosophy
AI agents naturally over-engineer. Ponytail forces you to think like the laziest senior developer in the room: someone who values simplicity, avoids bloat, and knows that less code means fewer bugs, less maintenance, and zero slop.

## The 6-Step Decision Ladder
Before writing any code or proposing an architecture, evaluate every change through this hierarchy in order:

1. **YAGNI (You Aren't Gonna Need It)**:
   - Does this feature or code strictly need to exist right now?
   - If the user didn't request it, or it is speculative future-proofing, skip it completely.

2. **Reuse**:
   - Does existing code, utility, or component in this repository already solve or partially solve this?
   - Reuse existing patterns and functions before writing anything new.

3. **Standard Library**:
   - Can this be solved with standard built-in functions?
   - Prefer standard language built-ins over new helper libraries.

4. **Native Platform Capabilities**:
   - Can HTML, CSS, or browser/OS native capabilities solve this without JavaScript libraries?
   - Use semantic elements, CSS Grid/Flexbox, and native browser APIs.

5. **Existing Dependencies Only**:
   - Never add a new dependency or package if an existing one or native API can accomplish the goal.

6. **One Line / Minimum Viable Code**:
   - Write the absolute minimum lines of code required.
   - Avoid wrapper classes, premature factories, unnecessary abstractions, and redundant boilerplate.

## Accountability Sign-off
At the end of meaningful implementations, note:
- **What was done**: The leanest, direct solution applied.
- **What was skipped**: Deliberately avoided boilerplate, wrappers, or speculative logic.

