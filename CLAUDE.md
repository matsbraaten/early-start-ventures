# Early Start Ventures Website

## What this project is
The website for **Early Start Ventures**, the consulting/advisory company of
**Torstein Braaten** (the user's father). It will be published to a
**GoDaddy Managed WordPress** site.

## Creative direction (from the owner — overrides anything that conflicts)
- The company should come across as a **simple, small consulting firm** that
  is deeply expert in capital markets and crypto. Not a large business — no
  big-corporate feel, no flashy imagery. Understated, credible, expert.
  **The person IS the brand.**
- Copy: confident and expert but modest in scale — "consulting practice"
  energy, not "global firm" energy. Emphasize deep expertise in capital
  markets compliance and crypto/digital asset regulation. Avoid phrases
  implying teams, offices worldwide, or scale the firm doesn't have. Use
  "I/Torstein" or firm-singular voice where natural.
- Pictures support, not dominate: the headshot on the About page; at most
  one subtle stock hero/section background. All images compressed for fast
  loading, with alt text.

## Images (in `images/`)
- Originals (kept locally, gitignored because they are multi-MB):
  `torstein-headshot.jpg` plus three Unsplash stock photos.
- Optimized web copies (committed, used by the site):
  - `images/headshot.jpg` — Torstein's headshot, About page.
  - `images/toronto-skyline.jpg` — Toronto skyline, subtle homepage hero
    background (fits the Toronto-based positioning).
- The unused stock photos (executive office, boardroom) were rejected as
  too big-corporate.

## Branding & messaging
- **Slogan: "Empowering Startups to Succeed"** — used as the main homepage
  hero headline.
- Homepage messaging: Early Start Ventures helps early-stage companies
  (especially fintech and digital assets) get compliance and regulatory
  strategy right from the start, so they can grow with confidence. Blends
  startup empowerment with the firm's core strength in digital asset
  compliance. The stablecoin digest stays as a featured section.
- Tone: professional and confident, not salesy.

## Real contact details (confirmed by the user — use these, they are not fake)
- Email: tbraaten@me.com (clickable mailto link)
- Phone: +1 416 904 0102 (clickable tel link)
- LinkedIn: https://www.linkedin.com/in/torsteinbraaten/
- Location: "Based in Toronto's West End — serving clients across Canada
  and internationally"
- Email and LinkedIn also appear in the footer of **every** page.
- Contact page is a clean simple page — **no contact form**.

## About the company & owner (for the About page)
Torstein Braaten is a compliance executive with 30+ years advising banks,
investment dealers, and crypto platforms. Career highlights:
- Chief Compliance Officer at WonderFi Technologies
- Head of Regulatory Affairs & CCO at Bitbuy (registered Canadian crypto
  dealer/marketplace)
- CCO at Coinsquare
- Chief Operating & Compliance Officer at Instinet Canada (2018–2021)
- CCO at BMO Nesbitt Burns (2016–2018)
- Served on the Ontario Securities Commission Fintech Advisory Committee
- Served on IIROC's Crypto-Asset Working Group
- BComm Honours, Carleton University; ICD.D designation; Certified
  Securities Compliance Professional
The bio on the site is written as polished professional prose, not a list.

## Site structure (multi-page, relative links)
- `index.html` — home: hero introducing Early Start Ventures, value
  proposition around digital asset compliance and regulatory intelligence,
  cards linking to each topic section.
- `about.html` — Torstein's bio and the company's mission.
- `stablecoins.html` — first topic section: the stablecoin news/regulation
  digest (Canada, US, UK, Switzerland, EU) with real, dated summaries and
  sources — never placeholder text.
- `contact.html` — simple contact page with the real contact details
  listed above (no form).
- `styles.css` — one shared stylesheet used by every page, so design
  changes happen in one place.

## Design direction
- Clean, professional, finance/consulting look; dark navy and white with a
  muted gold accent.
- Consistent header navigation and footer across all pages.
- Real photos are now in place (see Images section) — no placeholder boxes
  remain.

## Technical approach
- Plain HTML/CSS/JS, no build tools or external dependencies.
- Must work by simply double-clicking `index.html` locally (relative links
  only), and stay portable for GoDaddy hosting.
- Future topic digests get their own page, linked from a card on the home
  page, following the pattern of `stablecoins.html`.

## How to work with the user
- The user is a **non-coder**. Always explain changes in plain English and
  keep explanations simple. Avoid jargon; when technical terms are needed,
  define them briefly.
