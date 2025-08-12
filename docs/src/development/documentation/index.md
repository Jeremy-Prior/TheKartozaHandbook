# Project Documentation

This folder contains reusable templates for starting and maintaining project docs.

- **`mkdocs-base-template.yml`** – base MkDocs config to copy and adapt.
- **`repo-template/`** – a minimal repository scaffold, including a `docs/` layout.

## How to use

1. Copy **`mkdocs-base-template.yml`** to your project and rename it (e.g., `mkdocs-base.yml` or `mkdocs.yml`).
2. Update the **`nav`** section to point to your project’s actual docs paths.
3. If starting fresh, copy the contents of **`repo-template/`** into a new repo and rename files/folders as needed.

## Conventions

- Keep documentation in a top-level **`/docs`** directory.
- Use lowercase-hyphen file names (e.g., `getting-started.md`).
- One `# H1` per page; use `##` for subsequent sections.
- Store images in **`docs/img/`** or **`docs/**/img/`** with descriptive names.

## Quick start (local preview)

```bash
./build-docs-html.sh # build
mkdocs serve   # run locally
```

> **Tip:** Edit `site_name`, `repo_url`, and `edit_uri` in your MkDocs config for better navigation and "Edit this page" links.

