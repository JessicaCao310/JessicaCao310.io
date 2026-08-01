# AGENTS.md

Guidance for AI coding agents working in this repository.

## Project

Personal website hosted from the GitHub repository
`JessicaCao310/JessicaCao310.io`. The site is currently in early setup — the
tech stack and structure are still being established.

## Setup

```bash
# Clone
git clone https://github.com/JessicaCao310/JessicaCao310.io.git
cd JessicaCao310.io
```

If/when a build tool is added, document its install and run commands here
(e.g. `npm install`, `npm run dev`).

## Project Structure

```
.
├── index.html      # Main entry point (add when ready)
├── assets/         # Images, fonts, static files
├── css/            # Stylesheets
├── js/             # Scripts
├── README.md
└── AGENTS.md
```

Update this section as real files are added.

## Conventions

- Keep HTML semantic and accessible (alt text, headings in order, labelled controls).
- Prefer relative units and responsive layouts; the site should work on mobile.
- Keep styles and scripts organized in `css/` and `js/` rather than inline,
  once the project grows beyond a single page.
- Optimize images before committing them.

## Git Workflow

- Default branch: `main`.
- Make small, focused commits with clear messages.
- Do not commit secrets, API keys, or large binary files.

```bash
git add .
git commit -m "Describe the change"
git push
```

## For Agents

- Ask before introducing a new framework or build tool — the stack is not yet decided.
- Do not push to `origin` or publish content without explicit confirmation.
- Keep `README.md` and this file up to date when the structure or workflow changes.
