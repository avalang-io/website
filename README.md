# AvaLang Website

This repository contains the static landing page for [avalang.io](https://avalang.io).

AvaLang is an independent open-source programming language and compiler tutorial project. It is designed for human programmers and coding agents, with a focus on strong diagnostics, native code generation, and a long-term path toward self-hosting.

## Current status

The website is intentionally simple while the public compiler tutorial and repository are being prepared.

Current site contents:

- Landing page
- Project goals
- Naming and command overview
- GitHub organization links
- Independence disclaimer

## Project naming

- Project name: `AvaLang`
- Source file extension: `.ava`
- Compiler command: `avac`
- Future umbrella tool command: `avalang`

## Local development

This is a plain static website. No build step is required.

Run a local server from the repository root:

```bash
python3 -m http.server 8080
```

Then open:

```text
http://localhost:8080
```

## Files

```text
index.html   Main landing page
styles.css   Website styles
README.md    Repository notes
```

## Deployment

The site is deployed through Cloudflare Pages from this GitHub repository.

## Independence

AvaLang is an independent open-source programming language project. It is not affiliated with, sponsored by, endorsed by, or connected to any employer, company, or third-party product.
