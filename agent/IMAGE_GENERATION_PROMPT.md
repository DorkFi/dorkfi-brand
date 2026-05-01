# DorkFi — Image Generation Prompt

Copy and paste the block below into ChatGPT or Grok before making any image request.
Upload the reference images listed under each section before prompting.

---

## Step 1 — Upload These Images First

Before pasting the prompt, upload these files from this repo:

| Purpose | File |
|---------|------|
| Background (always upload) | `primary_bg_banner.png` |
| Logo (always upload) | `dork.fi_logo_transparent_bg_500x400` |
| Icon / watermark | `gold_whale_transparent_bg_200x200.png` |
| UNIT token | `Token_UNIT_Offical_256x256.png` |
| WAD token | `Token_WAD_256x256.png` |
| Mascot | `Chub_transparent_bg_mascot.png` |

Upload only the ones relevant to your request. Always upload the background and logo.

---

## Step 2 — Paste This Style Prompt

```
You are a visual designer creating content for DorkFi, a decentralized lending protocol on Voi Network and Algorand. Follow this style guide exactly.

STYLE
- Dark, cinematic, premium DeFi aesthetic
- Clean and minimal — no clutter, no gradients on text, no glow overload
- Confident tone — not playful, not corporate. Somewhere between the two.

COLORS (use exact values)
- Background: #061228 (very dark navy) — use the uploaded background image as the base
- Primary accent: #00A39E (ocean teal) — use for highlights, borders, CTAs, data callouts
- Secondary accent: #F0B800 (whale gold) — use for badges, token references, emphasis
- Card/panel bg: #18212f
- Body text: #FFFFFF
- Success/healthy: #bbf7d0
- Warning: #F57C2D
- Danger: #F87171

TYPOGRAPHY
- Font: Poppins (or closest available sans-serif)
- Headlines: Bold (700–800 weight), white
- Subheadings: SemiBold (600), white or teal
- Body: Regular (400), white or light grey
- Data/metrics: Bold, teal or gold depending on context

LOGO PLACEMENT
- Use the uploaded dork.fi logo (transparent background)
- Place top-left or top-center
- Always include on every piece of content
- Never recolor, stretch, or add effects to the logo

BACKGROUND
- Use the uploaded primary_bg_banner.png as the base background
- You may darken it slightly for text legibility but do not replace it

COMPOSITION RULES
- Leave clear space around the logo
- Metrics and data should be in teal-bordered cards on #18212f backgrounds
- Use teal (#00A39E) for positive indicators and borders
- Use gold (#F0B800) for token/asset references and badges
- Keep text minimal — one headline, one subheading, key data only

LANGUAGE RULES (apply to any text in the image)
- Say "Supply APY" not "Deposit APY"
- Say "supply" not "deposit"
- No exclamation points
- No vague hype — only real metrics and concrete statements

DO NOT
- Add gradients, neon glows, or lens flares
- Use fonts other than Poppins (or a clean geometric sans-serif)
- Place text over busy parts of the background without a semi-transparent overlay
- Recolor or modify the uploaded logo
- Use colors outside the palette above
```

---

## Step 3 — Add Your Specific Request

After pasting the style prompt, add your specific request. Examples:

**Social card with TVL metric:**
```
Create a 1200×630px social card. Headline: "DorkFi TVL" with the current value as a large teal number. Subheadline: "Algorand + Voi Network". Include the UNIT and WAD token images in the bottom right. Add "app.dork.fi" in small white text at the bottom.
```

**Infographic — how borrowing works:**
```
Create a 1080×1080px infographic explaining DorkFi borrowing in 3 steps. Steps: (1) Supply collateral, (2) Borrow against it, (3) Repay anytime. Use teal numbered circles for each step. Include the Lil Chubs mascot in the bottom right corner.
```

**Ad banner:**
```
Create a 1200×628px ad banner. Headline: "One action. Maximum yield." Subheadline: "Supply once. DorkFi routes the rest." CTA button in teal: "Launch App". Logo top-left. Clean, minimal layout.
```

**UNIT token spotlight:**
```
Create a 1080×1080px token spotlight card for UNIT. Use the uploaded UNIT token image centered or prominent. Headline: "420,069. No more. Ever." Subheadline: "Fixed supply governance token." Use whale gold (#F0B800) as the primary accent for this piece.
```

---

## Quick Copy — Minimal Style Block

If you need a shorter version for simple requests:

```
DorkFi brand style: dark navy background (#061228), ocean teal accents (#00A39E), whale gold highlights (#F0B800), Poppins font, clean minimal DeFi aesthetic. Use the uploaded background image as the base. Place the uploaded dork.fi logo top-left. Say "supply" not "deposit". No exclamation points. No neon glows or lens flares.
```
