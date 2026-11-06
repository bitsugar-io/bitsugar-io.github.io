# AGENTS.md

This repository is the bitsugar landing page, a single hand-written
`index.html` with its styles inline and `logo.png`. GitHub Pages serves the root
of `main` at bitsugar.io, the domain in `CNAME`. There is no README, build step,
test suite or formatter. Check a change by opening `index.html` in a browser.

## Publishing

A merge to `main` publishes the site. There is no build, preview or required
review in between, so open the page in a browser before you merge, not after.

## Commit trailer

When committing via Claude Code, end the message with:

```
🤖 Generated with [Claude Code](https://claude.ai/code)

Co-Authored-By: Claude <noreply@anthropic.com>
```
