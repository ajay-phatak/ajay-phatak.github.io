# ajay-phatak.github.io

My public facing portfolio of projects (most of which are vibe coded these days).

Live at: **https://ajay-phatak.github.io** *(once GitHub Pages is enabled)*

## Structure

```
index.html        ← main portfolio page (edit this to add/update projects)
CLAUDE.md         ← instructions for Claude Code when working on THIS repo
```

## How to add a project

1. Copy one of the `.project-card` blocks in `index.html`
2. Update the name, description, status badge, tags, and links
3. Commit and push — GitHub Pages auto-deploys on push to `main`

## Status badges

| Class | When to use |
|---|---|
| `status-stable` | Finished, works, you'd show it to anyone |
| `status-mvp` | Core loop works, rough edges remain |
| `status-progress` | Actively being built |
| `status-archived` | Stopped working on it |

## Updating from Claude Code

In any project repo, after a session you can run:

```bash
# From this portfolio repo:
# Edit the relevant project card in index.html, then:
git add index.html
git commit -m "portfolio: update [project name]"
git push origin main
```

Or tell Claude Code directly: *"Update my portfolio repo to reflect the current state of this project."*

## Deployment

GitHub Pages — Settings → Pages → Deploy from branch → `main` / `root`.

Your portfolio will be live at: `https://ajay-phatak.github.io`
