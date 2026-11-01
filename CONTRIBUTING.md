# Contributing to SplitIt Pro

Welcome! 👋 Thanks for thinking about improving SplitIt Pro — every idea, bug report and pull request is appreciated.

## The good news: no build tools needed

SplitIt Pro is **a single HTML file**. You don't need npm, bundlers or a toolchain to contribute:

1. Fork the repo
2. Open `index.html` in your browser (or run `npx serve .` if you prefer a server)
3. Edit, refresh, test

## Ideas welcome via Issues

Not sure where to start? Open an issue and pitch it. Current roadmap ideas that would make great first contributions:

- In-browser receipt OCR
- PDF / image export of a split
- Dark/light theme toggle
- PWA install banner

## Pull request rules

- **Keep the on-device promise.** No backends, no analytics, no `<script src="https://...">` trackers, no CDNs the app *requires* to run. If a feature means sending user data anywhere, it doesn't ship.
- **Test in the browser.** Open the page, try your change with keyboard *and* touch, and check the console for errors before submitting.
- **Keep everything in one file**, unless your PR is specifically a refactor dedicated to splitting the app up.
- **Attribution for new artwork assets.** Any bundled icon, font or other artwork must be freely licensed (or your own original work) and credited in the README with its license.

## Submitting

Keep PRs focused on one change, describe what you tested, and link the issue it fixes (if any). Small and sharp beats big and vague.

Thanks for helping SplitIt Pro grow! 🚀
