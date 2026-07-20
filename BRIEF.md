# Loyaledge — Retention Careers Landing Page

## Goal

Ship a single-page, conversion-focused careers site that recruits **multilingual Account Managers (client portfolio / client loyalty roles)** to relocate to Malta and join Peak Services Ltd.

**One measurable outcome:** a qualified applicant (Swedish-speaking, relocation-willing, relationship-selling background) lands on the page and submits an application. Everything on the page either builds belief or removes friction toward that submit.

**Primary audience:** ambitious multilingual professionals in Sweden, Poland, Italy and wider Europe — currently in account management, customer success, B2B/B2C relationship sales, or hospitality/service roles with strong people skills — who are open to relocating for higher earnings and faster progression.

**Success signals:** application form completion rate, scroll depth past the Malta section, CTA clicks on the open role.

---

## Non-negotiable content rules

### Scope: retention only
This page is **only** about the client-portfolio / account-management track. The Sales Agent material from the source doc is out of scope — do not include the Sales Agent JD, outbound-prospecting language, or "introducing potential clients to our services" framing.

### Terminology guardrail
- **Never** use the phrase **"retention agent"** (or "retention agents"). That exact term maps to a sensitive role title.
- **"Retention" as a business activity is fine and expected** — "client retention", "retention benchmarks", "retention bonus", "high-retention portfolio" all read as standard B2C business vocabulary. Use them naturally.
- Approved role titles: **Account Manager**, **Client Relationship Manager**, **Portfolio Manager**, **Client Success Manager**.
- Approved framing for the work: nurturing existing client portfolios, building long-term trusted relationships, growing lifetime client value (LTV), portfolio health.
- Avoid: "brokers", "trading floor", anything implying the candidate advises on financial products. The employer is an **outsourcing company specialising in financial services and client relations** — keep it at that level.

### Company naming (decision made — flag if wrong)
The source text mixes three names. Resolution used here:
- **Loyaledge** = the recruitment brand / name of this page and program.
- **Peak Services Ltd** = the legal employer, named in the "About" and in the job description.
- **"Smart Connect"** = dropped entirely; it belongs to the sales-side draft.

If Loyaledge is actually meant to be a standalone entity rather than a Peak Services program, this needs correcting before build.

---

## Brand & visual direction

**Position:** Modern Mediterranean career launchpad.
**Tone:** Energetic, aspirational, supportive, transparent, high-performance. Confident but not hypey — no fake urgency, no invented numbers.

### Colors
| Token | Hex | Use |
|---|---|---|
| Primary | `#4780FF` | CTAs, links, accents, highlights, icon fills |
| Deep | `#1B3476` | Headings, dark sections, footer, logo mark |
| Background | `#F7F9FC` (off-white, light theme) | Page base — light, **not** pure white, **not** dark |
| Surface | `#FFFFFF` | Cards raised off the background |
| Text | `#1B3476` / `#4A5568` | Headings / body |

Light theme throughout. Gradients between `#4780FF` and `#1B3476` are on-brand for hero and section dividers.

### Logo
`assets/loyaledge-logo.svg` — wordmark "LOYALEDGE" with a two-tone shield mark. Native viewBox `0 0 1045 316`. Inline it as SVG so it stays crisp; never rasterize. Dark-navy-on-light is the default lockup; on the dark hero band use a white/light variant of the wordmark with the blue mark intact.

### Imagery direction
- **Work:** sleek modern offices, high-energy floor moments, teams celebrating results, modern tech setups, one-to-one client conversations.
- **Life:** sunlit Malta coastline, Valletta streets, rooftop networking drinks, vibrant expat social scenes.
- **Hard avoid:** sterile call-center stock photos, heavy headsets, blank white walls, generic handshake shots.

---

## Page structure

### 1. Hero
- **Headline:** *Build Client Relationships That Last. In the Mediterranean Sun.*
- **Sub-headline:** Join Loyaledge in Malta as an Account Manager. Grow a portfolio of loyal clients, earn uncapped rewards tied to the value you build, and live somewhere that feels like a permanent getaway.
- **CTAs:** `[ View Open Roles ]` (primary, `#4780FF`) · `[ Discover Life in Malta ]` (secondary, outline)
- Trust strip beneath: *200+ professionals · Multiple nationalities · Full relocation support · Paid training*

### 2. Why Loyaledge — core value props (4 cards)

**💎 Portfolio Excellence & Client Loyalty** — *"Build long-term value, not one-off transactions."*
Manage, nurture and grow high-value relationships with existing clients. Drive strong retention benchmarks through meaningful conversations and genuine service alignment.

**💰 Consultative Growth & Uncapped Rewards** — *"Your ability to build trust dictates your success."*
Generous base salary plus high-tier bonus structures tied to lifetime client value and portfolio health. Premium client accounts are reserved for the strongest portfolio managers.

**🎓 Paid Training & Continuous Coaching** — *"We invest in your success before your first client conversation."*
No prior industry experience required. Complete, fully paid onsite onboarding, then continuous coaching in consultative methodology, consumer psychology and client communication.

**📈 Accelerated Career Progression** — *"Fast-track from Account Manager to leadership."*
Promotion strictly on performance, not tenure. Clear routes into Team Leader, Desk Manager, Quality Assurance and Operational Coaching.

### 3. The Malta Advantage
*"Work hard, live in paradise."* — four tiles:
- **300+ days of sun** — Mediterranean climate, crystal-clear sea, year-round outdoor life.
- **English-speaking island** — zero language barrier for daily life, healthcare and admin.
- **Safe & expat-friendly** — among Europe's safest countries, thriving international community.
- **Full relocation support** — flight assistance, initial accommodation guidance, complete admin setup (ID, tax, banking).

### 4. Open Positions
Card list with expand-to-detail (accordion or modal). Launch with one role; structure must scale to more languages without a rewrite.

> **Account Manager — Swedish Speaker** · Malta (on-site) · Full-time
> **Overview:** Create long-term, trusting relationships with our customers. Oversee and grow a portfolio of clients, develop new business from existing accounts, and act as the lead point of contact for everything relating to your accounts. You'll liaise with Customer Service and other internal teams to improve the whole client experience.
> **Responsibilities:** lead point of contact for your accounts · build and maintain strong, long-lasting client relationships · develop trusted-advisor relationships with key accounts · ensure timely, successful delivery of solutions against client needs · develop new business with new and existing clients · meet and exceed daily client retention targets · handle challenging requests and escalations.
> **Requirements:** fluent Swedish (written and verbal) · negotiation skills · previous experience as an Account / Key / Junior Manager or similar · proven ability to run multiple account relationships at once with sharp attention to detail · excellent listening, negotiation and presentation ability · genuine enthusiasm and energy.

### 5. Benefits & Rewards
Icon grid: fixed base salary · attractive monthly commission structure · relocation package with flight assistance and accommodation support · comprehensive onboarding and training · financial-market education and professional development · weekly food allowance after three months · employee discounts with local partners · incentive programs and competitions · modern international office, 200+ employees · career progression in a fast-growing company.

### 6. Career Development
Short section on internal promotion: *"At Peak Services, we promote from within. Strong performers with leadership potential grow across departments and management levels."* Ideally a simple visual progression path: Account Manager → Senior Account Manager → Team Leader → Desk Manager.

### 7. About Peak Services Ltd
International outsourcing company specialising in financial services and client relations. 200+ professionals, multiple nationalities, performance-driven environment built for long-term careers.

### 8. Application form
Fields: Full name · Email · Phone · Language(s) spoken · Current location · Role applying for (prefilled from the CTA clicked) · LinkedIn or CV upload · Short "why Malta?" free text (optional).
Inline validation, clear success state, GDPR consent checkbox with a link to the privacy notice. No dark patterns.

### 9. Footer
Logo, Peak Services legal line, contact email, social links, privacy policy, equal-opportunity statement.

---

## Technical requirements

- **Stack:** single static `index.html` with a co-located stylesheet and minimal vanilla JS. No build step, no framework, no CDN dependencies — it must open from the filesystem and drop onto any host unchanged.
- **Responsive:** mobile-first, tested at 375 / 768 / 1280. Sticky header with a working mobile menu; sticky or repeated primary CTA on mobile.
- **Accessibility:** WCAG 2.1 AA. Real semantic landmarks, keyboard-navigable accordions and form, visible focus rings, alt text on every image, `#4780FF` used only where it clears 4.5:1 against its background (it does not clear AA as body text on light backgrounds — use `#1B3476` for text and reserve `#4780FF` for larger type, fills and borders).
- **Performance:** no blocking third-party requests, images lazy-loaded, inline critical CSS. Target sub-2s load on 3G.
- **SEO/meta:** title, description, Open Graph and Twitter cards, `JobPosting` structured data for the open role, favicon from the logo mark.
- **Motion:** subtle scroll reveals and hover states only. Everything must respect `prefers-reduced-motion`.
- **Forms:** ship with a clearly marked submission endpoint placeholder — do not wire it to a live service without explicit instruction.

---

## Guardrails

- Do not invent salary figures, commission percentages, employee testimonials, ratings, or client names. Every claim on the page must trace to the source material above.
- Do not imply the role involves giving financial or investment advice.
- Keep imagery placeholder-based unless real photography is supplied; label placeholders clearly so nobody ships stock-looking filler by accident.
- Copy is European-English throughout.

---

## Resolved decisions

1. **Loyaledge vs Peak Services** — Loyaledge is the recruitment brand; Peak Services Ltd is the named legal employer. "Smart Connect" dropped. *Revisit if Loyaledge is a separate entity.*
2. **Application handling** — form posts to a `data-endpoint` placeholder on the `<form>`. Not wired to any live service. Swap the attribute value for the real ATS/webhook URL.
3. **Additional languages** — Swedish ships now. Roles are marked up as a repeatable `.role` block with `data-role-id`; adding Polish/Italian is a copy-paste of one block plus one `<option>` in the form.
4. **Photography** — ships with **no stock imagery**. Visual weight comes from typography, brand color blocks and abstract SVG. Photo slots are marked with `<!-- PHOTO SLOT -->` comments so real assets drop in without a redesign.

---

## Ready-to-run build prompt

> Build a single-page recruitment website for **Loyaledge**, the Account Manager careers page for Peak Services Ltd in Malta, following `BRIEF.md` in this directory exactly.
>
> Produce `index.html`, `styles.css` and `script.js` — static, no build step, no external dependencies. Inline `assets/loyaledge-logo.svg` as SVG.
>
> Brand: primary `#4780FF`, deep navy `#1B3476`, light off-white background `#F7F9FC` (light theme, never dark, never pure white). Tone: energetic, aspirational, supportive, transparent, high-performance.
>
> Sections in order: hero → why Loyaledge (4 value cards) → the Malta advantage (4 tiles) → open positions (expandable, launching with Account Manager – Swedish Speaker) → benefits grid → career development path → about Peak Services → application form → footer.
>
> **Critical constraint:** never use the phrase "retention agent". "Retention" as a business activity — client retention, retention targets, retention bonus — is expected and correct. Role titles must be Account Manager / Client Relationship Manager / Portfolio Manager. Exclude all Sales Agent content.
>
> Use only the copy and facts in `BRIEF.md`. Invent no salary figures, testimonials, or statistics. Mobile-first responsive, WCAG 2.1 AA, `JobPosting` structured data, `prefers-reduced-motion` respected, form endpoint left as a clearly marked placeholder.
