# System Directives & Engineering Standards

Enforce the following system directives across this codebase and all future tasks:

## [Process & Execution]
- **GSD**: Break tasks into small, structured sub-tasks to prevent context overload.
- **Ralph Loop**: Iteratively test and self-correct code logic before delivering final output.

## [Code Quality & Efficiency]
- **Anti-Slop Policy**: Zero filler, zero boilerplate wrappers, and zero placeholder comments (e.g., `// TODO`). Deliver fully functional, production-ready code.
- **Ponytail (The Lazy Senior Dev)**: "The best code is the code you never wrote." Enforce the 6-Step Decision Ladder:
  1. *YAGNI*: Drop speculative features and future-proofing.
  2. *Reuse*: Re-use existing patterns and code in the project first.
  3. *Stdlib*: Rely on language/runtime built-ins.
  4. *Native Platform*: Prefer browser/OS native features before custom code.
  5. *Existing Deps*: Zero unnecessary external packages or heavy wrappers.
  6. *Minimum Code*: Deliver the shortest, cleanest functional solution.
- **Reticle & Chisle**: Execute precise, targeted modifications rather than full-file overwrites.

## [Review & Standards]
- **SkillSpector & CodeRabbit**: Audit code for bugs, typing errors, and functional reliability.
- **UI & UX First**: Prioritize modern, clean, user-centric design with modern emoji accents (no legacy/outdated styling). Responsive layout, accessible controls, and polished interactions.

## [Environment & Tooling]
- **IDE Integration**: Tailor output specifically for modern IDE environments (VS Code, Cursor, Windsurf, Antigravity).
- **Terminal Operations**: Rely on direct CLI commands for running scripts, testing, and managing dependencies.
- **GitHub Standards**: Maintain clean version control practices with descriptive commit messages and modular edits.
- **MCP (Model Context Protocol)**: Leverage connected tools, databases, and APIs (GitHub, Figma, Supabase) for live context and secure workflow execution.

