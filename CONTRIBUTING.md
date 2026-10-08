# Make the next version more useful

Corrections with a clear source are especially welcome. Open an issue with:

1. The action ID, for example `AU-0001`.
2. What is wrong, unclear or missing.
3. The relevant state or territory and date, if applicable.
4. A direct primary-source link and the change it supports.
5. Suggested replacement wording, if you have it.

Please avoid posting identity documents, medical records, account numbers or other personal case details. Public issues are for improving the guide, not resolving an individual case.

## Editing the project

`guide.json` is the source of truth for action content. Each chapter contains its number, title, slug, introduction and entries. Each entry needs a stable ID, action, cost, potential value, applicability, evidence basis, source list and review date.

Edit that data, then run:

```sh
node build.mjs
```

The build uses Node.js built-ins and has no package dependencies. It validates the data and regenerates the 40 chapters, chapter index, source directory and self-contained `index.html`. It does not regenerate the editorial README, source map or scenario pages; update those manually if the scope changes. Do not change established action IDs or chapter slugs without preserving inbound links.

Check the affected source claims, relative links and reader behaviour before opening a pull request. Test a narrow search, a chapter filter and a saved-action shortlist when changing the reader. The initial validator expects 40 chapters with 18 actions each; deliberately revise its count check when a future edition expands.

## Editorial rules

Follow [EDITORIAL-POLICY.md](EDITORIAL-POLICY.md). Use Australian English and describe a concrete next action. State eligibility limits and local differences. Do not label personal experience as official guidance. Avoid guarantees, universal treatment instructions, sales pitches and affiliate links. Prefer improving an existing entry over adding near-duplicates to increase the count.

By contributing, you agree to license guide text and documentation under CC BY 4.0, and original reader/build code and artwork under MIT. Only submit work you have the right to share. Preserve the upstream attribution and identify meaningful changes in the changelog.
