# Make the next version more useful

Corrections with a clear source are especially welcome. Open an issue with:

[Open a correction or reader-feedback issue](https://github.com/gerrygao1995-coder/live-better-australia/issues/new)

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

The build uses Node.js built-ins and has no package dependencies. It validates the data and regenerates the 40 chapters, chapter index, source directory, self-contained `index.html` and the supporting HTML pages. `launch.json` controls the selected 20 actions and the three short checklists; `build-site.mjs` generates their website pages, the Start here hub and `site.css`. Supporting HTML documents are built from their Markdown counterparts. Update the editorial README, source map and scenario Markdown manually when the scope changes. Do not change established action IDs or chapter slugs without preserving inbound links.

Check the affected source claims, relative links and reader behaviour before opening a pull request. Test a narrow search, a chapter filter and a saved-action shortlist when changing the reader. The initial validator expects 40 chapters with 18 actions each; deliberately revise its count check when a future edition expands.

## A five-minute reader check

Choose one checklist or the selected 20 and tell us:

- What were you trying to find?
- Which action or sentence was useful, confusing or missing?
- Was the state, eligibility or timing clear?
- What would make you comfortable sharing this with someone else?

Include the page link or action ID. General feedback is welcome even without a replacement source; corrections to factual claims need an authoritative source. You can give feedback to the person who shared the guide if you do not use GitHub. Feedback, professional reviews and endorsements must never be invented or implied from an invitation.

## Editorial rules

Follow [EDITORIAL-POLICY.md](EDITORIAL-POLICY.md). Use Australian English and describe a concrete next action. State eligibility limits and local differences. Do not label personal experience as official guidance. Avoid guarantees, universal treatment instructions, sales pitches and affiliate links. Prefer improving an existing entry over adding near-duplicates to increase the count.

By contributing, you agree to license guide text and documentation under CC BY 4.0, and original reader/build code and artwork under MIT. Only submit work you have the right to share. Preserve the upstream attribution and identify meaningful changes in the changelog.
