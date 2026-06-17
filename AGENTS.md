> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is the public documentation site for **MentionScout**, built on [Mintlify](https://mintlify.com).
- MentionScout tracks how a brand is mentioned and cited by AI answer engines (ChatGPT, Perplexity, Claude, Google AI Overviews and AI Mode, and others), alongside social listening. Core flows: brand analysis, scheduled prompt runs, competitor tracking, citations, and AI-crawler analytics.
- Pages are MDX files with YAML frontmatter. Site configuration lives in `docs.json`.
- The brand color is violet (`#8200DB`). Logos and favicon live at the repo root (`logo/`, `favicon.svg`).

## Terminology

- Use **prompt** for a question MentionScout runs against an answer engine, not "query" or "search".
- Use **answer engine** for AI products that answer questions (ChatGPT, Perplexity, Claude, Google AI Overviews/AI Mode).
- Use **mention** when a brand is named in an answer; use **citation** when a brand is linked or cited as a source. These are distinct.
- Use **brand** for the account's own product and **competitor** for tracked rivals.

## Style preferences

- Use active voice and second person ("you").
- Keep sentences concise — one idea per sentence.
- Use sentence case for headings.
- Bold for UI elements: Click **Settings**.
- Code formatting for file names, commands, paths, and code references.
- Never use em-dashes anywhere. Use a regular hyphen or rewrite the sentence.

## Content boundaries

- Never name the underlying third-party data sources or vendors MentionScout uses to collect data. Describe capabilities, not suppliers.
- Don't document internal, admin, or unreleased features.
- Don't promise specific answer-engine coverage or refresh frequencies unless confirmed for the current release.
