# Conventions

Please read and adhere to our [coding standards](./coding_standards.md) for all work.

**Quick links**

- **IDEs** — recommended setups and plugins: [IDEs](./ides.md)
- **Processes** — how we work day-to-day: [Processes](./dev_processes.md)
- **Git** — branching, commits, PRs: [Git](./git.md)

---

## Project Conventions

- We follow SDLC / agile practices using scrum boards. See: [project processes](./project_processes.md)
- Use the project board for **issues**, **priorities**, and **status**.
- Every task has: problem, acceptance criteria, owner, due date.

---

## Language Conventions

> [“A foolish consistency is the hobgoblin of little minds.”](https://peps.python.org/pep-0008/#a-foolish-consistency-is-the-hobgoblin-of-little-minds)  
> Prefer readability and team standards over personal style.

### Python
- **Style:** PEP 8 where sensible (see coding standards).
- **Lint/Format:** _TBD_ (e.g., ruff/flake8 + black) — see [coding standards](./coding_standards.md).
- **Testing:** _TBD_ (e.g., pytest); aim for fast, isolated tests.
- **Packaging:** _TBD_ (e.g., uv/pip + pyproject.toml).

### JavaScript
- **Style:** Align with project baseline.
- **Lint/Format:** _TBD_ (e.g., eslint + prettier).
- **Testing:** _TBD_ (e.g., vitest/jest + testing-library).
- **Packages:** Lockfile committed; pinned major versions.

### C++

- **Style:** Follow the official **[QGIS C++ Coding Standards](https://docs.qgis.org/latest/en/docs/developers_guide/codingstandards.html)**
- **Lint/Format:** Use `clang-format` with the QGIS profile; run `clang-tidy` in CI aligned with QGIS checks.
- **Build/Test:** CMake; tests via QtTest/ctest.
- **Conventions:** Prefer Qt types where sensible, RAII and smart pointers, and Doxygen comments for public APIs.

---

## Minimal Working Agreements

- **Naming:** lowercase-hyphen for files; snake_case for Python; camelCase for JS variables; PascalCase for types/classes.
- **Docs:** one `# H1` per page; images in `docs/img/`; short alt text required.

---

## Tiny Checklists

**Commit message**
- `[scope]: concise summary`  
- Body: what/why, not just how. Link issue: `Fixes #123`.

**Pull request**
- Problem & approach explained
- Tests/Docs updated (if applicable)
- Checklist passes (lint/format/ci)

