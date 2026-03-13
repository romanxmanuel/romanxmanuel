# Portfolio Showcase - Project Context

## What This Is

This is Roman Manuel's GitHub profile repository plus local showcase materials that support employer-facing presentation.

The repo has two responsibilities:
- root `README.md` powers the GitHub profile page
- `showcase/` contains an interactive standalone showcase site and planning docs

This project may be worked on by both Claude Code and Codex. Either tool should be able to read this file and plug in efficiently without relying on prior chat history.

## Structure

```text
portfolio-showcase/
  CLAUDE.md
  README.md
  assets/
    photo-of-roman.png
  showcase/
    README.md
    site/
      index.html
      assets/
    docs/
      roman-product-strategy-roadmap.md
      roman-product-strategy-roadmap.html
      roman-product-strategy-roadmap.docx
```

## What Lives Where

- `README.md`
  - canonical GitHub profile README
  - should stay concise, polished, and employer-facing

- `assets/`
  - profile repo assets used by the GitHub README

- `showcase/site/index.html`
  - standalone interactive showcase page
  - deployed separately to Vercel

- `showcase/site/assets/`
  - screenshots used by the standalone showcase page

- `showcase/docs/`
  - planning and strategy documents
  - useful context, but not part of the public GitHub profile page itself

## Deployment

- GitHub profile page comes from the repo root `README.md`
- Standalone showcase site is deployed from `showcase/site`
- Current live showcase URL: `https://repo-showcase-vercel.vercel.app`

## Editing Rules

- Do not mix showcase-only content into the root profile README unless explicitly intended for the public GitHub profile.
- Keep the profile README simple and high-signal.
- Keep the standalone showcase visually stronger and more interactive than the root README.
- If changing the standalone showcase, make sure relative asset paths still work from `showcase/site/index.html`.
- If redeploying the standalone site, deploy from `showcase/site`.

## Collaboration Notes

- Read this file and `showcase/README.md` before restructuring folders.
- Check `git status` before editing.
- Assume the root README and the standalone showcase have different audiences and different levels of visual intensity.
- Keep instructions in files current so either Claude Code or Codex can continue work cleanly on another machine.
