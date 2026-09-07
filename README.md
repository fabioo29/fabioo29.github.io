# fabioo29.github.io

Public pages for my apps: the privacy policy and terms of service that each
store listing links to. One folder per app, so a second app gets its own
`<app>/privacy.md` and `<app>/terms.md` without touching the others.

- Pocket Words: https://fabioo29.github.io/pocket-words/privacy and
  https://fabioo29.github.io/pocket-words/terms

Served by GitHub Pages from the `main` branch. Jekyll turns each Markdown file
into a page at the `permalink` in its front matter. The old root `/privacy`
and `/terms` redirect to the Pocket Words pages through `redirect_from`,
because released builds of the app still link to them.
