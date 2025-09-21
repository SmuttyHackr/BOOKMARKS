# Copilot instructions for BOOKMARKS

This project is minimal — a single README at the repository root. Use these concise, repository-specific instructions to guide AI agents working on this repo.

Key facts discovered
- Repo root contains only `README.md` (content: "Fuckyabookmarks").
- No source code, build system, tests, or CI files detected.
- No existing agent instruction files (AGENT.md, .github/copilot-instructions.md, etc.).

What the agent should do first
1. If asked to add functionality, create a clear project structure (language, folder layout, build manifest).
   - Ask the user which language/tooling they prefer if not specified.
2. When editing `README.md`, preserve tone and author voice. The current text is one line; ask before changing content.

Repository-specific patterns and constraints
- There are no discoverable code-level conventions. Treat repository as content-only until new code is added.

When creating files
- Add a top-level README section explaining the new layout and how to build/run the project.
- Commit new files to a feature branch and open a PR describing the change.

Examples
- To start a Node.js project: add `package.json`, `src/`, and `README.md` with "npm install" / "npm start" docs.
- To start a Python project: add `pyproject.toml` or `requirements.txt`, `src/`, and a small `main.py` runner.

Signals to ask the user for clarification
- Preferred programming language and runtime.
- Desired feature set (web app, CLI, library, etc.).

If you can't proceed
- Explain what's missing (no code, no CI) and propose one concrete minimal scaffold option.

Contact
- Ask the repo owner for examples or intended architecture before making large changes.
