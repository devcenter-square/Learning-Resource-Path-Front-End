# CLAUDE.md — AI Assistant Guide for Learning-Resource-Path-Front-End

## Repository Overview

This is a **documentation-only** curated learning roadmap for front-end developers. It contains no source code, build system, or runtime dependencies — only markdown files. The primary purpose is to aggregate and organize high-quality learning resources by skill level and topic.

**Repository:** `akinfals/learning-resource-path-front-end`
**Development branch:** `claude/add-claude-documentation-KStwX`

## Repository Structure

```
/
├── README.md          # Main roadmap — 337 lines of curated resources
├── contributing.md    # Contribution guidelines and Code of Conduct
└── CLAUDE.md          # This file
```

There are no build files, package managers, CI/CD pipelines, test suites, or source code directories.

## Content Organization

The `README.md` is structured into three skill tiers:

| Level | Topics Covered |
|-------|---------------|
| **Beginner** | HTML, CSS, JavaScript, Git |
| **Mid-Level** | Advanced CSS (Grid, Flexbox, Responsive, Preprocessors), ES6+ JS, React, Vue, Angular, Testing, Web Animations, Developer Tools, Web Fonts, UI/UX |
| **Advanced** | Web Security, GraphQL/REST, Serverless, Computer Science, State Management (Redux/MobX), Web Typography, Responsive/Mobile Design, PWA, Web Performance, Web Accessibility, IDE/VSCode |

Each level section ends with a **Exercises & Challenges** subsection (🏆) for hands-on practice.

## Resource Classification System

Every resource link uses a consistent emoji tagging system:

| Emoji | Meaning |
|-------|---------|
| 🎮 | Interactive |
| 📚 | Book |
| 📹 | Video |
| 📝 | Article |
| 🎤 | Podcast |
| 👩‍💻 | Community |
| 💰 | Paid Resource |
| 🎁 | Free Resource |
| 🏆 | Exercises |

## Contribution Conventions

These rules are enforced for all changes to `README.md` (from `contributing.md`):

- **Link format:** `[Resource Name](URL) emoji emoji`
- **Placement:** New entries go at the **bottom** of the relevant section
- **Casing:** Use Title Case for resource names
- **No bold or italics** unless contextually appropriate
- **No duplicates:** Search existing entries before adding
- **Individual PRs:** One pull request per resource addition
- **Spelling and grammar** must be correct
- **Trailing whitespace** must be removed

### When Adding a New Resource

1. Identify the correct skill level and topic section
2. Create a new section if no appropriate one exists
3. Append the entry at the bottom of that section
4. Classify it with the appropriate emojis (type + cost)
5. Use Title Case for the resource name
6. Verify no duplicate entry exists

### When Adding a New Section

- Place it within the appropriate skill level (Beginner / Mid-Level / Advanced)
- Match the heading style (`###`) of existing sections

## Git Workflow

This repo uses a standard fork-and-PR community workflow.

- **Main branch:** `master`
- **Feature/AI branches:** `claude/*` (e.g., `claude/add-claude-documentation-KStwX`)
- **Push target for this session:** `claude/add-claude-documentation-KStwX`

```bash
# Standard push
git push -u origin claude/add-claude-documentation-KStwX
```

Commit messages should:
- Have a descriptive title summarizing the change
- Include a link to the repository in the commit body

## What AI Assistants Should and Should Not Do

### Safe operations
- Add new learning resources following the emoji and formatting conventions
- Fix typos, grammar, or broken links in `README.md`
- Restructure or improve `CLAUDE.md`
- Create new topic sections in `README.md` if a clear gap exists

### Requires confirmation
- Removing or significantly altering existing resource entries
- Reorganizing the skill-level structure of `README.md`
- Any changes to `contributing.md` or the Code of Conduct

### Do not do
- Add build tooling, package.json, or source code — this is intentionally a docs-only repo
- Create new markdown files beyond those that already exist without a clear user request
- Push directly to `master`

## No Build or Test Commands

This repository has no build process, test runner, linter, or formatter. There is nothing to install or run. Changes are made directly to markdown files and reviewed via pull requests.
