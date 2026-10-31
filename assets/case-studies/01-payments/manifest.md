# 01 Payments: manifest

> **HOLD: don't publish before the Nov 11, 2026 launch.** These screens show My VA Payments before release. Check with your VA product owner and Friends From The City before using them.

All images are 2x PNGs from the `modernized-ae` prototype (va-prototype-kit `main`), with fictional mock data. The prototype banner and site footer are cropped out.

| File | What it shows | Suggested alt text |
|---|---|---|
| hero-desktop.png | Payments page at 1440px (`?scenario=default`). Action required lists 1 overpayment, 3 copay bills, and a travel pay claim; Updates groups Payment history, Copays, Overpayments, and Travel pay. | VA.gov Payments page on desktop. An "Action required" list of overpayment, copay, and travel pay tasks with due dates sits above an "Updates" section grouped by payment type. |
| hero-mobile.png | The same page at 390px. | VA.gov Payments page on a phone, with Action required tasks stacked above the Updates section. |
| state-empty.png | Empty state (`?scenario=empty`): nothing needs action and there are no recent updates. | VA.gov Payments page with no action items or updates, showing empty-state messages and Quick access links. |
| state-partial-error.png | Partial error (`?scenario=partial-error`). Travel pay fails in Action required while the other items still load; each Updates section shows its own error alert. | VA.gov Payments page where some data failed to load. Inline error alerts appear in each affected section while the available action items still show. |
| routing-table.png | A rebuilt table showing which overpayment statuses go to Action required, which go to Updates, and which show a due date. It uses the plain-language status names from VA.gov's own copy, not internal status codes. The routing comes from `platform/my-va/shared/domains/debts.js`. | Table mapping 13 overpayment statuses to a Payments section. Four informational statuses go to Updates, eight that need action go to Action required (five with a due date), and unrecognized statuses are hidden. |
| thumb-16x9.png | 16:9 crop of the top of hero-desktop for the home page card. | VA.gov Payments page with an Action required list of payment tasks. |

**Not captured yet:** the Figma frames (waiting on file URLs).
