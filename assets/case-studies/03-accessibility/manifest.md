# 03 Accessibility: manifest

All images are 2x PNGs of the FSR gross monthly income page, served locally with mock data (employer "Riverside Hardware"; $0 entered, then Continue selected).

| File | What it shows | Suggested alt text |
|---|---|---|
| hero-desktop.png | Shipped design (vets-website `main`, PRs #46726 and #46938) at 1440px: a slim warning alert above the income field, with the input in its normal state. | VA debt help form income step. A yellow warning above the gross monthly income field says "You told us you're currently employed, but entered $0.00 in monthly income. Make sure this is correct before you continue." |
| hero-mobile.png | The same page at 390px. | The same zero-income warning above the income field on a phone. |
| before-error.png | An earlier iteration (commit `a8b77f3ab4` on the PR branch): the input in red error style ("Please confirm this is correct.") with a warning below it. Captured by temporarily swapping that version of the component into main. | Earlier design: the income field outlined in red with "Please confirm this is correct." in red, and a yellow warning below the field. |
| after-warning.png | The same crop with the final design: the warning above the field and no error styling. | Final design: a yellow warning above the income field and no red error styling on the input. |
| thumb-16x9.png | 16:9 crop of hero-desktop for the home page card. | Zero-income warning shown above an income field on VA.gov. |

**VoiceOver recording:** not captured, because Playwright can't record VoiceOver. To make it yourself: on the page above, turn on VoiceOver (⌘F5), enter 0, select Continue, and record with ⌘⇧5. The alert takes focus and VoiceOver should read "Warning: You told us you're currently employed…".
