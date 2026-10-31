# 02 Hardship suspension: manifest

> **HOLD: check before publishing.** Hardship suspension is behind the `enable_hardship_suspension` feature flag, and I couldn't confirm from the repo that it's live in production.

All images are 2x PNGs of the shipped FSR app (vets-website `main`, VA Form 5655), served locally with the `fsr-minimal` e2e fixtures. The identity data is replaced with a fictional "Alex Rivera" and placeholder IDs, and no identity fields are in frame.

| File | What it shows | Suggested alt text |
|---|---|---|
| hero-desktop.png | Relief options page (step 5 of 7) with the four options and Hardship suspension selected, plus the "More information about relief options" accordions. | VA debt help form, relief options step. Four radio options (repayment plan, compromise offer, waiver, and hardship suspension), with hardship suspension selected. |
| warning.png | Confirmation warning page: "Are you sure you want to request a hardship suspension?", explaining how a suspension can affect future waiver eligibility. | Warning alert asking "Are you sure you want to request a hardship suspension?" and explaining how it can affect eligibility for a future waiver. |
| time-range.png | Time-range question: "When do you expect your financial hardship to improve?" with four ranges up to 24 months, a note to choose a different option if it's longer, and a confirmation checkbox. | Form question "When do you expect your financial hardship to improve?" with four options from within 6 months to between 18 and 24 months, followed by a confirmation checkbox. |
| review.png | Review-and-submit page with the Relief options section expanded, plus the statement of truth and Submit. | Review page of the debt help form showing the selected relief option, followed by the statement of truth and a Submit your request button. |
| thumb-16x9.png | 16:9 crop of the relief options for the home page card. | Relief options step with hardship suspension selected. |

**Not captured yet:** the Figma frames (waiting on file URLs).
