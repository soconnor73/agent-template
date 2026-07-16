# Stack
Languages, frameworks, versions — pin these, don't let Claude infer from lockfiles alone.

# Patterns to follow
- Where new code of type X goes
- Naming/error-handling/logging conventions

# Patterns to avoid
- Things tried and reverted, with why (saves Claude from repeating the experiment).

# Git & Branching Conventions
- Branch naming: `feature/`, `bugfix/`, `chore/` followed by issue ID or short description.
- Commits: Use Conventional Commits (e.g. `feat:`, `fix:`, `docs:`, `test:`). Keep commits atomic.
- Pull Requests: Always create a PR for human review; do not push directly to `main` unless configured otherwise.

# Versioning
- This project adheres to Semantic Versioning (SemVer) (`MAJOR.MINOR.PATCH`).
- Git tags must match release versions (e.g., `v1.2.3`).

# Module map
One line per top-level dir: what it owns, what it must not import from.
