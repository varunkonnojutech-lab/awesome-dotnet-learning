# Contributing to Awesome .NET Learning

Thanks for helping keep this list useful. A curated list is only as good as
its last update, so contributions are genuinely welcome.

## What makes a good addition

- **It belongs in .NET.** C#, ASP.NET Core, EF Core, Azure for .NET, .NET tooling.
- **It is maintained.** Updated for .NET 6 or later, or timeless by design.
  A 2015 blog post about .NET Framework 4.5 is not a candidate.
- **It is free, or honestly marked.** Paid resources get the 💰 tag.
- **You can say why in one line.** Every entry carries a one-line note:
  what it is, who it's for. If you can't write that line, the link probably
  doesn't belong here.

## What doesn't belong

- Your own project, course, or blog — unless it is genuinely established
  and useful to learners who have never heard of you. (Maintainers may
  still say no; that's fine.)
- Link aggregators, "top 100" listicles, and SEO roundups.
- Anything paywalled without a 💰 tag, or anything that requires an account
  just to read the first page.

## How to contribute

1. Fork the repo and create a branch.
2. Add your link to the right section, in alphabetical order within it,
   with a one-line description in the same style as its neighbours.
3. Keep lines short and the format identical: `- [Title — Author](url) — one line`.
   Add 💰 after the link for paid resources.
4. Run the checks locally if you can: `npx markdownlint-cli2 "**/*.md"`
   and confirm the link loads in a browser.
5. Open a pull request with one sentence on why the resource belongs here.

CI runs a markdown linter and a link checker on every pull request — a PR
with a dead link or broken formatting won't merge until it's fixed.

## Reporting a dead link

Open an issue with the broken URL and the section it lives in. Dead links
are removed quickly; if a resource moved, a replacement URL in the issue
is even better.
