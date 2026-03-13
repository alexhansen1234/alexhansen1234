# CLAUDE.md

This file provides guidance to AI assistants (Claude and others) working in this repository.

## Repository Overview

This is a **GitHub Profile README repository** for the user `alexhansen1234`. GitHub automatically displays the `README.md` of a repository that matches the owner's username as their public profile page.

- **Type:** Personal profile repository (static content)
- **Language:** Markdown only
- **Purpose:** Display profile information on the GitHub user page at `github.com/alexhansen1234`
- **No code, no build system, no dependencies**

## Repository Structure

```
alexhansen1234/
├── README.md     # Profile content shown on github.com/alexhansen1234
└── CLAUDE.md     # This file
```

## Development Workflow

### Making Changes

Since this is a static Markdown repository, the workflow is simple:

1. Edit `README.md` with the desired profile content
2. Commit with a descriptive message
3. Push to the `master` or `main` branch — GitHub will immediately reflect the change on the profile page

### Branch Strategy

- **`master`** — main branch; content here is live on the GitHub profile
- Feature/AI branches (e.g., `claude/...`) are used for drafting changes before merging

### No Build or Test Steps

There are no build commands, test suites, linters, or CI/CD pipelines. Changes go directly from editing to committing.

## Key Conventions

- **Markdown only** — all content is plain GitHub-flavored Markdown (GFM)
- **Keep `README.md` concise** — GitHub profile READMEs are most effective when short and scannable
- **No trailing whitespace** — keep the file clean
- **Commit messages** — use short, descriptive imperative messages (e.g., `Update contact info`, `Add GitHub stats badge`)

## Content Guidelines

The README is a personal profile page. Appropriate content includes:
- Contact information (Discord, email, social links)
- Brief bio or interests
- GitHub stats widgets/badges
- Links to notable projects or work

Current content is minimal — just a Discord handle (`hanz#7927`).

## AI Assistant Notes

- There is no code to analyze, refactor, or test in this repository
- Changes should only be made to `README.md` (or documentation like this file)
- No commands need to be run before or after edits
- When updating `README.md`, preserve valid Markdown formatting and the existing HTML comment block explaining the special repository feature
