# Ideas & Scripture Notebook

This repository is a [Mintlify](https://mintlify.com/) documentation site. Right now it is based on the Mintlify starter kit, but it has been indexed and organized so you can turn it into a searchable home for:

- personal ideas,
- Bible verses,
- devotion notes,
- sermon or study notes,
- project concepts,
- reusable writing templates.

## Is this a good repo for ideas and Bible verses?

Yes, if you want your notes to feel like a polished, browsable website instead of a folder of plain text files. Mintlify gives you navigation, search, cards, callouts, code blocks, images, and clean pages written in MDX.

It is especially good if you want to:

- publish selected notes publicly,
- keep a curated index of your ideas and verses,
- write long-form reflections,
- organize content by topic, book, theme, or project,
- add links between notes.

Consider a private repo instead if your ideas are sensitive, unfinished, or personal. Bible notes can be public, but private prayer notes, journal entries, confidential project ideas, and personal information should not be published by accident.

## Generated repository index

| Path | Purpose | Keep, change, or remove? |
| --- | --- | --- |
| `docs.json` | Mintlify site configuration, navigation, colors, logo, navbar, and footer. | Keep and customize. |
| `index.mdx` | Homepage for the notebook and high-level index. | Keep. This is now your main entry point. |
| `quickstart.mdx` | How to write and organize notes in this repo. | Keep. Rewritten for your workflow. |
| `development.mdx` | How to preview the Mintlify site locally. | Keep. Useful for editing. |
| `ideas/index.mdx` | Starting index for idea notes. | Keep and expand. |
| `scripture/index.mdx` | Starting index for Bible verse and study notes. | Keep and expand. |
| `templates/idea-note.mdx` | Copyable template for a new idea note. | Keep. |
| `templates/verse-note.mdx` | Copyable template for a new Bible verse note. | Keep. |
| `essentials/*.mdx` | Mintlify examples for Markdown, code blocks, images, settings, navigation, and snippets. | Keep while learning; remove later if you want a cleaner site. |
| `snippets/snippet-intro.mdx` | Example reusable snippet. | Optional. Useful if you repeat text across pages. |
| `api-reference/*` | Starter API documentation examples for a fake Plant Store API. | Remove unless you plan to document an API. |
| `images/*` | Starter images used by example pages. | Replace with your own images over time. |
| `logo/*` and `favicon.svg` | Starter branding assets. | Replace when you choose a name/visual identity. |

## Recommended content structure

Use simple folders and one MDX file per note:

```text
ideas/
  index.mdx
  project-name.mdx
  article-topic.mdx
scripture/
  index.mdx
  john-3-16.mdx
  psalm-23.mdx
  romans-8.mdx
templates/
  idea-note.mdx
  verse-note.mdx
```

Suggested naming rules:

- Use lowercase file names.
- Use hyphens instead of spaces.
- Use a clear title in the frontmatter of every page.
- Put draft status, tags, and dates near the top of each note.

## How to add a new idea

1. Copy `templates/idea-note.mdx` into the `ideas/` folder.
2. Rename it with a short slug, such as `ideas/sabbath-app.mdx`.
3. Edit the title, description, status, tags, and note body.
4. Add the new page path to `docs.json` under the `Ideas` navigation group.
5. Add a link to it from `ideas/index.mdx` if you want it visible in the index.

## How to add a new Bible verse note

1. Copy `templates/verse-note.mdx` into the `scripture/` folder.
2. Rename it with a reference slug, such as `scripture/romans-8-28.mdx`.
3. Include the Bible reference, translation, theme, context, and reflection.
4. Add the new page path to `docs.json` under the `Scripture` navigation group.
5. Add a link to it from `scripture/index.mdx`.

## Local development

Install the Mintlify CLI:

```bash
npm i -g mintlify
```

Run the local preview from the repository root:

```bash
mintlify dev
```

The site usually opens at `http://localhost:3000`.

## Publishing notes safely

Before publishing publicly, review these questions:

- Is the repository public or private?
- Are any personal journal entries included?
- Are any original business ideas confidential?
- Are copyrighted Bible translation quotations used within allowed limits?
- Did you cite the Bible translation you quoted?

For public Bible notes, it is often safer to quote short passages, cite the translation, and write your own reflections in your own words.
