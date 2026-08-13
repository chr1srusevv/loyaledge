# LoyalEdge — Careers Landing Page

A single-page, conversion-focused recruitment site for **LoyalEdge**, the Customer
Support careers program for **Peak Services Ltd** in Malta. It recruits multilingual
customer-support professionals across Europe to relocate for paid training, relocation
support and career progression.

> Copy on this page is legally reviewed. Before changing any wording, read the **Legal
> review** block at the top of [`BRIEF.md`](BRIEF.md) — it overrides the rest of the brief.

## Stack

Deliberately dependency-free: one `index.html`, one stylesheet, one vanilla-JS file.
No build step, no framework, no external requests — open `index.html` directly or drop
the folder onto any static host unchanged.

| File | Purpose |
|------|---------|
| `index.html` | Markup, inlined logo SVG, `JobPosting` structured data, meta/OG tags |
| `styles.css` | All styling and motion — light theme, brand `#4780FF` / `#1B3476` |
| `script.js` | Progressive enhancement: nav, accordions, scrollspy, counters, reveals, form |
| `assets/loyaledge-logo.svg` | Two-tone wordmark + shield mark |
| `BRIEF.md` | The build brief — goal, content rules, decisions, section-by-section spec |

## Running locally

Any static server works. For example:

```bash
python -m http.server 8000
# then open http://localhost:8000
```

## Before going live

- **Wire the application form.** `#applyForm` carries `data-endpoint="REPLACE_WITH_ATS_ENDPOINT"`.
  Set it to your ATS or webhook URL; until then the form validates but sends nothing.
- ~~**Set the contact email.**~~ Done — `hr@loyaledge.net` in the footer and in
  `script.js`'s submit-failure message.
- **Drop in photography.** The page ships with brand-colour blocks and no stock photos.
  Real-image slots are marked with `<!-- PHOTO SLOT -->` comments.
- **Adding roles.** The page carries one multilingual `.role` block by design — per legal,
  language-specific variants must not appear here. Language requirements belong on the
  individual open positions. If a genuinely different role is added, duplicate the `.role`
  block with a new `data-role-id` and add a matching `<option>` to the form's role select.

## Accessibility & motion

WCAG 2.1 AA: semantic landmarks, keyboard-operable menu and accordions, visible focus
rings, and text/background contrast verified against the brand palette. All motion is
decorative and disabled under `prefers-reduced-motion`. Counters and scroll reveals have
failsafes so content is never left hidden if scripting is interrupted.

---

Brand and role-terminology guidance lives in [`BRIEF.md`](BRIEF.md).
