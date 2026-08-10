# StoryBoard — Obsidian templates for authors

A collection of Obsidian templates for fiction writers, organized in the order most projects need them:

1. **Writing templates** — ideation, premise, characters, antagonist, settings, Save the Cat–style beats, scene cards, goals
2. **Manuscript** — where you actually draft chaptered prose
3. **Editing** — beta worksheets, reader's reports, manuscript feedback
4. **Marketing** — reviews, interviews, content ideas, market research, publishing checklist

The layout borrows from Scrivener's binder thinking (project dashboard, corkboard-style scene cards, character/setting codex) and pacing ideas familiar from Save the Cat, without requiring either tool.

## How to download and use this in Obsidian

### 1. Get the files

1. Open this repository on GitHub.
2. Click the green **Code** button → **Download ZIP**.
3. Unzip it somewhere easy to find (for example, `Documents\Obsidian\StoryBoard`).

If you prefer git:

```bash
git clone https://github.com/10amgreen-hub/authortemplates.git
```

### 2. Open it as an Obsidian vault

1. Open Obsidian.
2. Choose **Open folder as vault**.
3. Select the unzipped folder — the one that contains `00 Home` and `README.md`.
4. Open `00 Home/Home.md` and start from there.

### 3. Use the templates

1. Duplicate `Projects/Project Dashboard Template.md` and rename it for your book.
2. Plan in `01 Writing Templates`.
3. Draft in `02 Manuscript` — duplicate `Chapter Template.md` into a book folder / `Chapters/` subfolder.
4. Use `03 Editing Templates` and `04 Marketing Templates` when you reach those stages.

**Optional:** Install the community plugin **Templater** (recommended in this vault’s plugin list), then set its template folder to `01 Writing Templates` or `02 Manuscript`.

No special theme or paid plugins are required.

## Folder structure

```text
StoryBoard/
  00 Home/                   # Home note (sorted to the top)
  00 Inbox/                  # Quick capture
  01 Writing Templates/      # Planning tools
  02 Manuscript/             # Full chapter drafts live here
    Chapters/                # Optional shared/example chapter folder
    Chapter Template.md
    Manuscript Home Template.md
    Manuscript Guide.md
  03 Editing Templates/
  04 Marketing Templates/
  Projects/                  # Per-book dashboards
```

## Drafting chapters

1. Read `02 Manuscript/Manuscript Guide.md`.
2. Duplicate `Manuscript Home Template.md` for your book.
3. Duplicate `Chapter Template.md` once per chapter (suggested names: `Chapter 01 - Title.md`).
4. Keep planning notes in `01 Writing Templates`; keep prose in `02 Manuscript`.

## Community plugins

This repo **recommends** plugins but does **not** ship the plugin files themselves.

- Included: `.obsidian/community-plugins.json` lists **Templater**
- After opening the vault, Obsidian will prompt you to install recommended community plugins (or install **Templater** manually from Settings → Community plugins)

**Why not bundle plugins in GitHub?**
- Plugin folders are large and update often
- Friends get fresher installs from Obsidian’s plugin browser
- Avoids shipping machine-specific plugin settings
- Keeps the repo easy to download and review

If you ever want a fully turnkey offline vault, plugins *can* be committed under `.obsidian/plugins/`, but that usually complicates sharing more than it helps.

## Writing templates

| Template | Purpose |
|---|---|
| Idea to Plot | Brainstorm theme, genre, conflict, rough acts |
| Project Brief | Logline, premise, stakes, readiness check |
| Character Profile | Want/need, lie/truth, arc, voice |
| Antagonist | Opposition with humanity and escalation plan |
| Setting | Place, period, sensory detail, dose control |
| Plot Beat Sheet | Full Save the Cat–style beats + five-point finale |
| Chapter Outline | Chapter job + scene list |
| Scene Card | Corkboard card: goal → conflict → outcome |
| Research Note | Facts with a clear on-page use |
| Revision Goals | One focused revision pass |
| Writing Goals | Monthly / session / stage tracker |
| Craft Notes | Short attributed craft reminders |

## Credits / inspiration

Templates are original documents for this vault. Structure and prompts were informed by common craft tools and personal study notes (including Save the Cat–style beat language and selected Alan Moore course quotations, attributed in `Craft Notes`). Source PDFs and copyrighted workbooks are **not** redistributed in this repository.

## License / sharing

Share freely with writer friends. If you publish a remixed version, a link back to this repo is appreciated but not required. Keep your private manuscript notes out of public forks.
