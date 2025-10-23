Create a concise, technology-agnostic set of project principles that will govern how the team works.
Focus on practical, high-impact rules for ways of working, code quality, testing standards, UX consistency, and performance expectations. Keep this document short and usable - a living constitution the team can follow day-to-day.
Required content and tone

- Core philosophy (one paragraph): test-first mindset, small iterative deliveries, and defendable simplicity (YAGNI).
- Testing & development discipline: mandate Red-Green-Refactor, prefer writing tests before code, prioritize contract/integration tests then EZE and unit tests, and require documenting any use of mocks or emulators when real dependencies aren't feasible.
- Branching & code-review rules: never push directly to main; use short-lived feature branches with clear prefixes (feature/, fix/, chore/, etc.); one logical change per branch; require at least one reviewer; include a concise PR checklist (tests, docs, run instructions, constitutional compliance note); discourage bypassing checks - if used, require written rationale.
- Merge gates & acceptance: merges require passing available automated checks, updated documentation, and reviewer sign-off; mark any approved deviations in the PR with justification and remediation plan.
- Quality expectations (non-prescriptive): encourage pre-commit hooks, linting, and type checks where available; specify "if available" for particular tools and require documented fallbacks; set goal-oriented targets (e-g., reasonable test coverage and complexity limits) rather than rigid numbers.
- Simplicity & maintainability: favor smallest-possible changes, readable code over cleverness, remove temporary/debug code before merge, and avoid unneeded abstraction layers unless documented and justified.
- Observability & versioning expectations: prefer structured logs and semantic versioning; if centralized tooling isn't available, require local equivalents and documentation.
- Governance & exceptions; all deviations must be documented with "why needed" and "simpler alternatives considered"
