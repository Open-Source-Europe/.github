# OSE .github Repository — Agent Instructions

This repository is the central governance hub for the Open Source Europe (OSE) GitHub organization. Files here are automatically surfaced by GitHub as community health files across all OSE repositories, and key governance files are replicated org-wide.

## Critical Rules

- Do NOT autonomously modify `CODE_OF_CONDUCT.md` or `AI-POLICY.md`. These require explicit maintainer instruction and human review before any change.

## Authorship Rules

- **NEVER add `Co-Authored-By:` with yourself as a co-author of any commit.** Agents are assistants and tools — they are not authors. Only humans can be authors of commits.
- AI assistance disclosure belongs in the pull request description using `Generated-by:`, not in commit authorship metadata.

## Commit Conventions

- Use conventional commits: `feat:`, `fix:`, `docs:`, `ci:`, `chore:`
- Keep commits focused — one logical change per commit