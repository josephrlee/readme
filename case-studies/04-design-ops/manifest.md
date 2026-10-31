# 04 Design ops: manifest

| File | What it shows | Suggested alt text |
|---|---|---|
| hero-pr-table.png | **A recreation, not a screenshot.** It's a GitHub-style render of PR #46726's description, cut down to its summary, with colleague names, ticket numbers, and va.ghe.com links removed. The original PR didn't use a before/after table; this one uses the 03 before/after images, laid out the way your later PRs (for example #48541) format screenshots. | A pull request description titled "[FSR] Add zero-dollar employment income alert", with a summary and a before/after screenshot table comparing the red error-style input with the final warning alert. |
| annotate-overlay.png | The `overpayment-balances-with-study-feedback` prototype with `?annotate` on: dashed outlines and numbered badges on each annotated part of the summary card. | Prototype of an overpayment summary card with dashed outlines and numbered green badges marking each design decision. |
| annotate-note.png | Annotation #5 (split CTA pattern) on its own, with its code snippet. Notes 1–4 are hidden because they quote usability-study findings, so the header still says "5 items". | Developer annotation panel showing design decision 5, a split call-to-action pattern, with the production code it replaces. |
| token-diff.png | Full SCSS diff from PR #47057 (dispute-debt): 7 hard-coded values replaced with VADS tokens (font weight, breakpoint, border width, spacing, heading size). | Code diff replacing hard-coded CSS values such as bold, 480px, 1px, and 2rem with VA design system tokens such as var(--vads-font-weight-bold). |
| thumb-16x9.png | 16:9 crop of hero-pr-table for the home page card. | Pull request with a before/after screenshot table. |

**Review before publishing:**
- The annotation text describes production component names and internal file paths (SummaryCard.jsx and so on). Fine for a code-focused audience, but check with your product owner.
- Per your canvas notes, credit the kit maintainers for the prototype kit and the VA platform engineer for the token scanner.
