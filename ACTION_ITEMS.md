# FlowOS — Action Items for You

These are tasks from the homepage audit that require your input, assets, or external services. Check them off as you complete them.

---

## High Priority

### 1. Wire the invitation form to a backend
**Status:** Form currently shows success message only — no data is saved.

**Options:**
- **Formspree** — Add `action="https://formspree.io/f/YOUR_ID"` to the form (free tier available)
- **Tally / Typeform** — Embed their form or redirect
- **Your own API** — Build an endpoint that stores to Airtable, Notion, or your database
- **Resend + Vercel Serverless** — Send to your email when someone applies

**Location:** `flowos-homepage.html` — search for `id="invite-form"`

---

### 2. Get real product screenshots
**Impact:** 10/10 — The single biggest thing missing for investor credibility.

**What you need:**
- Hero screenshot: Full-bleed screenshot of the actual FlowOS dashboard/flow builder (replace the HTML mockup)
- Feature screenshots: Each of the 6 feature cards could link to or show a real screenshot or GIF
- Flow builder in action: Screenshot or animated GIF of someone building a flow with the card-based system

**If product isn't ready:** Use high-fidelity Figma mockups that look real. No generic stock photos.

---

### 3. Commission a real logo
**Impact:** 9/10 — The blue square with "F" is a placeholder.

**What you need:**
- Wordmark + icon that works at small sizes (favicons, app icons, social avatars)
- Design direction: Systematic, intelligent — think Linear, Vercel, Stripe
- Budget: $1,500–$5,000 for a full identity package from a freelance brand designer (Dribbble, Twitter/X)

---

### 4. Record a 2-min demo video
**Impact:** 8/10 — "See It In Action" CTA was removed because there's no demo yet.

**Options:**
- **Loom** — You talking over the product, raw and authentic (recommended for early-stage)
- **Screen recording + motion graphics** — Polished but more time/cost
- **Navattic / Storylane** — Interactive click-through demos without giving away the backend

**When done:** Add a "Watch Demo (2 min)" button back to the hero that links to the video.

---

### 5. Replace legal page placeholders
**Status:** `privacy.html` and `terms.html` exist but have placeholder content.

**Action:** Use [Termly](https://termly.io) or [iubenda](https://iubenda.com) to generate compliant docs, then have a lawyer review before launch.

---

## Medium Priority

### 6. Set up analytics
**Status:** Plausible script is commented out in the HTML.

**Steps:**
1. Sign up at [plausible.io](https://plausible.io)
2. Add your domain: `getflowos.com`
3. Uncomment the script in `flowos-homepage.html`:
   ```html
   <script defer data-domain="getflowos.com" src="https://plausible.io/js/script.js"></script>
   ```

**Optional:** Add [Microsoft Clarity](https://clarity.microsoft.com) for session recordings and heatmaps.

---

### 7. Write 2–3 launch blog posts
**Impact:** 7/10 — An empty "Blog" link hurts credibility.

**Suggested posts (800–1,200 words each):**
1. **Foundational:** "Why Funnels Are Dead (And What Replaces Them)"
2. **Product:** "Introducing FlowOS: The Adaptive Marketing OS"
3. **Thought leadership:** Your POV on where marketing is going

---

### 8. Add real social proof when you have it
**Status:** Testimonials and logos sections were removed (no real data yet).

**When you have:**
- **Alpha/beta users:** Get 2–3 real quotes with real names, headshots, companies
- **Moonshot clients:** A quote like "This is what we've been asking for" from a known CMO
- **Waitlist count:** "1,247 marketing teams on the waitlist" — show the number
- **Logos:** 3–4 real client logos (with permission) in a "Trusted by" bar

---

## Lower Priority

### 9. Integrations grid
**Idea:** Show logos of tools FlowOS replaces or integrates with (Mailchimp, ActiveCampaign, Google Analytics, HubSpot, etc.) to help buyers understand where FlowOS fits.

---

### 10. Interactive pricing calculator (aspirational)
**Idea:** Let users input contact count or monthly traffic, show projected ROI vs. their current stack. Conversion tool + signal to investors about unit economics.

---

### 11. About / Team section (for investors)
**Idea:** Add your photo, Moonshot's track record ("$300M in combined client revenue"), and any advisors. Answers "Is this team credible?"

---

### 12. Market size line (for investors)
**Idea:** Add a brief line in the problem section: "The $X billion marketing automation market is ripe for disruption."

---

## Quick Reference

| Item | Est. Cost | Est. Time |
|------|-----------|-----------|
| Wire form to Formspree | $0 | 15 min |
| Product screenshots | $0–500 | 1–3 days |
| Logo commission | $1,500–5,000 | 1–2 weeks |
| Loom demo | $0 | 1 day |
| Legal pages (Termly) | $0–100 | 1 day |
| Plausible analytics | $0–9/mo | 1 hour |
| Blog posts | $0 | 3–5 days |

---

*Last updated: March 2026*
