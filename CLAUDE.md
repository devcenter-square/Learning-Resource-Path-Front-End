# CLAUDE.md — AI Assistant Guide

## Repository Overview

This is a **community-curated educational resource repository**, not a software application. It contains no source code, build tools, or runtime dependencies. The repository provides a structured learning roadmap for front-end development, organized by skill level.

**Repository:** `akinfals/learning-resource-path-front-end`
**Purpose:** Curated links to tutorials, books, videos, and interactive resources for front-end developers
**Primary content:** `README.md` (the roadmap), `contributing.md` (contribution guidelines)

## File Structure

```
Learning-Resource-Path-Front-End/
├── README.md         # Main learning roadmap — the primary content (~337 lines)
├── contributing.md   # Contribution guidelines and Code of Conduct
└── CLAUDE.md         # This file
```

There is no `package.json`, `src/`, test suite, CI/CD pipeline, or build configuration.

## Content Structure

`README.md` is organized into three skill tiers, each containing categorized resource lists:

### Beginner Level
- HTML
- CSS
- JavaScript
- GIT
- Exercises & Challenges

### Mid Level
- Advanced CSS (Grid, Flexbox, Responsive Design, Preprocessors/SASS)
- JavaScript (Design Patterns, ES6+, Functional Programming)
- React
- Vue.js
- Angular
- Testing (Jest, Mocha)
- Web Animations
- Developer Tools
- Web Fonts
- UI/UX Design

### Advanced Level
- Web Security
- Data Management (GraphQL, REST)
- Serverless Architecture
- Computer Science
- State Management (Redux, MobX)
- Web Typography
- Responsive and Mobile Design
- Progressive Web Apps (PWA)
- Web Performance
- Web Accessibility
- IDE/Text-Editor Productivity

## Resource Type Legend

All entries in `README.md` use emoji icons to classify resources:

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

When adding or modifying resources, follow these rules from `contributing.md`:

1. **No duplicates** — Search existing entries before adding
2. **Append only** — Add new resources at the end of the relevant section
3. **One PR per resource** — Make individual pull requests for each suggestion
4. **Use Title Casing** — Capitalize resource names properly
5. **Use correct emoji** — Apply the appropriate emoji from the legend above
6. **Link format:**
   ```
   [Resource Name](https://url-to-resource) 🎮 🎁
   ```
7. **No bold or italics** unless contextually appropriate
8. **Check spelling and grammar**
9. **Remove trailing whitespace**
10. **Commit message body** must include a link to the repository
11. **PR title** must be descriptive and useful

## Development Workflow

Since there is no code to build or test, the workflow is purely content-driven:

```bash
# 1. Create or switch to your working branch
git checkout -b your-branch-name

# 2. Edit README.md to add/update resources
# 3. Stage and commit changes
git add README.md
git commit -m "Add [Resource Name] to [Section]

https://github.com/akinfals/learning-resource-path-front-end"

# 4. Push and open a pull request
git push -u origin your-branch-name
```

**Active development branch:** `claude/add-claude-documentation-9fr63`

## AI Assistant Guidelines

When working in this repository:

- **This is not a code project.** Do not generate package.json, src/, or config files unless explicitly asked.
- **Primary task is content editing** — adding, updating, or reorganizing entries in `README.md`.
- **Preserve formatting** — maintain existing markdown structure, heading levels, and emoji conventions.
- **Validate links mentally** — do not fabricate resource URLs; only use links that were provided or confirmed to exist.
- **Follow contribution rules** — new resources go at the end of their section; use proper emoji tags.
- **No trailing whitespace** — ensure edits don't introduce trailing spaces.
- **Commit messages** must reference the repository URL in the body.
- **One concern per PR** — don't bundle unrelated resource additions into a single commit.
