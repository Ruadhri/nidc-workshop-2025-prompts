# Plan Prompt

Use a minimal-local architecture: a lightweight local backend process (HTTP API) paired with a simple frontend SPA.

- For the backend, use a small, widely-supported runtime and ecosystem (e-g., Node-js) with a minimal HTTP framework to keep the surface area small
- Implement the constraint engine as a modular library within the backend (so it can be reused or extracted later).
- Persist puzzles and user state directly to the developer's file system (JSON files for MVP, with an optional local DB file such as SQLite as a later migration) - no cloud storage or remote uploads.
- Keep dependencies minimal and favor vanilla HTML/CSS/JavaScript in the UI; do not require containers or external services.
- The thin-slice first: load a sample puzzle from disk -> open grid -> mark a cell -> observe one propagation/symmetric change -> save and reload to verify persistence.
