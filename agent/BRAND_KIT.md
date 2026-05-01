# DorkFi Brand Kit — Agent Reference

This file is the authoritative brand reference for AI agents creating content for DorkFi.
Read this file completely before generating any content.

---

## Identity

- **Name:** DorkFi
- **Tagline:** Dive into the depths of DeFi.
- **Domain:** dork.fi | App: app.dork.fi
- **Ecosystem:** Voi Network + Algorand (AVM-compatible chains)
- **Description:** DorkFi is a decentralized, non-custodial borrow-and-lend protocol. Users supply assets to earn variable rates, borrow against overcollateralized positions, and mint WAD — the protocol's native overcollateralized stablecoin.

---

## Primary Images

Use these as your defaults unless instructed otherwise.

### Default Background
```
URL: https://raw.githubusercontent.com/DorkFi/dorkfi-brand/main/images/primary_bg_banner.png
Use for: all social cards, infographics, ads, hero banners, and any content requiring a background
```

### Primary Logo
```
URL: https://raw.githubusercontent.com/DorkFi/dorkfi-brand/main/images/dork.fi_logo_transparent_bg_500x400
Size: 500×400 | Transparent background
Use for: ads, banners, presentations, any content where the logo appears prominently
```

### Primary Icon
```
URL: https://raw.githubusercontent.com/DorkFi/dorkfi-brand/main/images/gold_whale_transparent_bg_200x200.png
Size: 200×200 | Transparent background
Use for: profile images, favicons, thumbnails, watermarks, small-format placements
```

---

## Full Asset Library

### Logos
| Asset | URL | Size | Use When |
|-------|-----|------|----------|
| dork.fi logo (transparent) | `https://raw.githubusercontent.com/DorkFi/dorkfi-brand/main/images/dork.fi_logo_transparent_bg_200x200` | 200×200 | Smaller logo placements |
| dork.fi logo (transparent) | `https://raw.githubusercontent.com/DorkFi/dorkfi-brand/main/images/dork.fi_logo_transparent_bg_500x400` | 500×400 | **PRIMARY — default for ads/banners** |
| dork.fi logo (white bg) | `https://raw.githubusercontent.com/DorkFi/dorkfi-brand/main/images/logo-dorkfi-white-bg.jpg` | — | Light backgrounds only |
| dork.fi logo (dark bg) | `https://raw.githubusercontent.com/DorkFi/dorkfi-brand/main/images/logo-dorkfi-dark-bg.jpg` | — | Dark UI contexts |
| Dork Labs logo (transparent) | `https://raw.githubusercontent.com/DorkFi/dorkfi-brand/main/images/dorklabs_transparent_bg_200x200.png` | 200×200 | Corporate/grant contexts |
| Dork Labs logo (transparent) | `https://raw.githubusercontent.com/DorkFi/dorkfi-brand/main/images/dorklabs_transparent_bg_500x400.png` | 500×400 | Press kits, presentations |
| Gold Whale icon (transparent) | `https://raw.githubusercontent.com/DorkFi/dorkfi-brand/main/images/gold_whale_transparent_bg_200x200.png` | 200×200 | **PRIMARY ICON — favicons, thumbnails** |

### Token Assets
| Asset | URL | Size | Use When |
|-------|-----|------|----------|
| UNIT token | `https://raw.githubusercontent.com/DorkFi/dorkfi-brand/main/images/Token_UNIT_Offical_256x256.png` | 256×256 | Token listings, governance content |
| UNIT token | `https://raw.githubusercontent.com/DorkFi/dorkfi-brand/main/images/Token_UNIT_200x200.png` | 200×200 | Exchange submissions, smaller placements |
| WAD token | `https://raw.githubusercontent.com/DorkFi/dorkfi-brand/main/images/Token_WAD_256x256.png` | 256×256 | Stablecoin content, WAD-related materials |
| WAD token | `https://raw.githubusercontent.com/DorkFi/dorkfi-brand/main/images/Token_WAD_200x200.png` | 200×200 | Exchange submissions, smaller placements |

### Backgrounds & Banners
| Asset | URL | Use When |
|-------|-----|----------|
| Primary background | `https://raw.githubusercontent.com/DorkFi/dorkfi-brand/main/images/primary_bg_banner.png` | **DEFAULT — use for all backgrounds** |
| Agent DeFi banner | `https://raw.githubusercontent.com/DorkFi/dorkfi-brand/main/images/agent_defi_bg_banner.png` | Tech/agent/builder-focused content |
| Beach banner | `https://raw.githubusercontent.com/DorkFi/dorkfi-brand/main/beach_banner.png` | Community, lifestyle, casual content |
| Dark landscape | `https://raw.githubusercontent.com/DorkFi/dorkfi-brand/main/images/background-dark-landscape.jpg` | NFT drops, dark atmospheric content |

### Mascots
| Asset | URL | Use When |
|-------|-----|----------|
| Gold Whale | `https://raw.githubusercontent.com/DorkFi/dorkfi-brand/main/images/gold_whale_transparent_bg_200x200.png` | UNIT/governance content, premium materials |
| Lil Chubs (transparent) | `https://raw.githubusercontent.com/DorkFi/dorkfi-brand/main/images/Chub_transparent_bg_mascot.png` | Community content, Discord, social |
| Chubs GM Office | `https://raw.githubusercontent.com/DorkFi/dorkfi-brand/main/images/chub_gm_office_mascot.png` | GM posts, community greetings |
| Dork v1 Blue | `https://raw.githubusercontent.com/DorkFi/dorkfi-brand/main/images/dork_v1_blue_mascot.png` | NFT collection content |
| Dork v1 Red | `https://raw.githubusercontent.com/DorkFi/dorkfi-brand/main/images/dork_v1_red_mascot.png` | NFT collection content |
| Dork v1 Censored | `https://raw.githubusercontent.com/DorkFi/dorkfi-brand/main/images/dork_v1_censored_mascot.png` | Meme/community content only |

---

## Colors

Use these exact values. Do not approximate or substitute.

```json
{
  "primary": {
    "ocean_teal":    { "hex": "#00A39E", "hsl": "178 100% 32%", "use": "CTAs, buttons, links, highlights, borders" },
    "deep_navy":     { "hex": "#061228", "hsl": "218 76% 9%",   "use": "Main background, page background" },
    "whale_gold":    { "hex": "#F0B800", "hsl": "46 100% 47%",  "use": "Accents, badges, warnings, UNIT references" }
  },
  "extended": {
    "card_bg":       { "hex": "#18212f", "use": "Card backgrounds" },
    "highlight_aqua":{ "hex": "#00BDBD", "use": "Hover states, active indicators" },
    "sky_blue":      { "hex": "#82D4F5", "use": "Subtle highlights, info states" },
    "warning_orange":{ "hex": "#F57C2D", "use": "Warnings, at-risk health factors" },
    "danger_red":    { "hex": "#F87171", "use": "Errors, liquidation alerts" },
    "safe_green":    { "hex": "#bbf7d0", "use": "Healthy positions, success states" },
    "white":         { "hex": "#FFFFFF", "use": "Text on dark backgrounds" }
  },
  "css_tokens": {
    "--background": "218 76% 9%",
    "--primary":    "178 100% 32%",
    "--accent":     "46 100% 47%",
    "--muted":      "217.2 32.6% 14%",
    "--border":     "217.2 32.6% 17.5%"
  }
}
```

---

## Typography

- **Font:** Poppins (Google Fonts)
- **Import:** `https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap`
- **Weights:** 300 (captions) / 400 (body) / 500 (labels) / 600 (subheadings) / 700 (headings) / 800 (hero)

---

## Tokens

### UNIT
- **Full name:** UNIT
- **Type:** Governance token — fixed supply, non-inflationary
- **Supply:** 420,069 (permanent cap, no minting)
- **Algorand ASA:** `3121954282` (decimals: 8)
- **Voi ARC-200:** `420069` (decimals: 8)
- **How to frame:** Governance and coordination layer. Fixed supply = same fundamentals regardless of price.
- **Do not frame as:** investment, yield product, or speculative asset

### WAD (Whale Asset Dollar)
- **Full name:** Whale Asset Dollar
- **Type:** Overcollateralized stablecoin
- **Peg:** $1.00 USD
- **Algorand ASA:** `3334160924` (decimals: 6)
- **Voi ARC-200:** `47138068` (decimals: 6)
- **How to frame:** Utility, borrowing, on-chain liquidity, stability mechanism
- **Do not frame as:** yield product, savings account, or investment
- **Key fact:** WAD is minted only through collateralized borrowing — no pre-mint, no reserve

---

## Voice & Tone

### Always
- Direct and concise — no filler words
- Technically accurate — DorkFi users are crypto-native
- Confident without being hypey
- "Playful branding, serious economics"

### Never
- Exclamation points in formal or marketing copy
- The word "deposit" — use **"supply"** instead
- Yield framing for WAD ("earn on your WAD", "WAD savings")
- Investment language ("guaranteed returns", "passive income")
- Vague DeFi buzzwords with no substance behind them

### Vocabulary
| Use | Instead of |
|-----|-----------|
| Supply | Deposit |
| Supply APY | Deposit APY |
| Health factor | Collateral ratio |
| Overcollateralized | Backed |

---

## Content Guidelines by Format

### Social Cards / Infographics
- Background: `primary_bg_banner.png` (default)
- Logo: `dork.fi_logo_transparent_bg_500x400` (top-left or top-center)
- Accent color for highlights: Ocean Teal `#00A39E`
- Data callouts: Whale Gold `#F0B800`
- Font: Poppins Bold (700) for headlines, Regular (400) for body

### Ads
- Lead with a single clear idea — one metric, one feature, one question
- Use the primary background unless the ad concept specifically calls for another
- Always include the dork.fi logo
- CTA should link to `app.dork.fi`

### Protocol Announcements
- Open with what changed, not why it matters
- Lead with on-chain facts (TVL, APY, market count) where available
- Close with what's next — one concrete thing, not a bullet list of vague roadmap items

### UNIT Content
- Lean into fixed supply: "420,069. No more. Ever."
- Frame price drops as buying opportunities: "Lower price, same fundamentals, same fixed supply"
- Use Gold Whale mascot or UNIT token image

### WAD Content
- Emphasize utility and stability mechanism
- Never frame as yield — frame as a tool for capital efficiency
- "Borrow WAD against your collateral. Use it. Repay it."

---

## Social Handles

| Platform | Handle / URL |
|----------|-------------|
| X (Twitter) | [@dork_fi](https://x.com/dork_fi) |
| Discord | [discord.gg/HZzvGGmcNB](https://discord.gg/HZzvGGmcNB) |
| Medium | [medium.com/@dorkfi](https://medium.com/@dorkfi) |
| Docs | [docs.dork.fi](https://docs.dork.fi) |
| App | [app.dork.fi](https://app.dork.fi) |

---

## Quick Reference

```
DEFAULT BACKGROUND : https://raw.githubusercontent.com/DorkFi/dorkfi-brand/main/images/primary_bg_banner.png
PRIMARY LOGO       : https://raw.githubusercontent.com/DorkFi/dorkfi-brand/main/images/dork.fi_logo_transparent_bg_500x400
PRIMARY ICON       : https://raw.githubusercontent.com/DorkFi/dorkfi-brand/main/images/gold_whale_transparent_bg_200x200.png
PRIMARY COLOR      : #00A39E (Ocean Teal)
BACKGROUND COLOR   : #061228 (Deep Navy)
ACCENT COLOR       : #F0B800 (Whale Gold)
FONT               : Poppins
CTA LINK           : https://app.dork.fi
NEVER SAY          : deposit, earn (for WAD), guaranteed, investment
ALWAYS SAY         : supply, borrow, overcollateralized, on-chain
```
