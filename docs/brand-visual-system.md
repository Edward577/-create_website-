# Brand Visual System — Steady Ground / John Persona

Updated: 2026-04-24 — Claude Code full system build

This file is the single source of truth for all visual decisions across ChatGPT, Codex, and Cloud Code for the John / Conservative Woman promo lane.

---

## Brand Identity

**Working name:** Steady Ground
**Persona name (internal):** John — Conservative Woman / AI Offer Media
**Visual front:** AI-generated woman (see image-prompts.md for all prompts)
**Disclosure required:** Yes — all AI face visuals must carry the brand disclosure

---

## Color System

| Role | Name | Hex |
|---|---|---|
| Primary | Deep Navy | `#1B2B4B` |
| Accent | Warm Gold | `#C9A84C` |
| Background | Warm Cream | `#F5F0E8` |
| Supporting | Sage Green | `#6B8F71` |
| Text on dark | White | `#FFFFFF` |
| Text on light | Near Black | `#1A1A1A` |

---

## Typography Direction

- Headlines: Serif (think Times, Playfair Display, or similar) — conveys tradition, authority, trust
- Body: Clean sans-serif (Inter, Source Sans, or similar) — readable, modern
- Accent labels: Small caps or light uppercase tracking

**Never use:**
- Script fonts that look aggressive or casual
- Condensed display fonts that feel like hype marketing
- Gradient text effects

---

## Visual Rules (Always Active)

1. Navy background + cream text + gold accent = the default combination
2. One idea per slide or visual panel
3. Body copy under 40 words per visual
4. No red/black aggressive compositions
5. No explicit face AI if it looks uncanny — regenerate until it looks clean
6. No fake testimonials, no fake proof screenshots framed as real
7. No sexualized or thirst-trap visual direction
8. No political symbols as props (flags are acceptable as subtle background detail only)
9. Always include the AI disclosure when the face is used

---

## Persona Visual Summary

She is:
- White woman, late 20s to early 30s
- Light brown to dark blonde hair, natural styling
- Clear realistic eyes, minimal makeup
- Navy blazer or cream blouse as default wardrobe
- Soft natural window light
- Calm, composed, intelligent expression
- Business desk or neutral studio setting

She is not:
- Glamorous or sexualized
- Dressed in political costuming
- Showing luxury items
- Cartoonish, uncanny, or obviously AI-glitchy

---

## Social Platform Asset Map

| Platform | Profile Photo | Banner | Thumbnail | Story/Reel Cover |
|---|---|---|---|---|
| TikTok @shophere79 | Prompt 5 — square headshot | Deep navy with gold Steady Ground text | Prompt 4 — speaking head | Prompt 4 or Master |
| X @Hmmmm355382 | Prompt 5 — square headshot | Wide navy desk/lifestyle image | n/a | n/a |
| Instagram @janes_store34 | Prompt 5 — square headshot | n/a | Prompt 4 | Prompt 3 or Master |
| Facebook Prop Firm Rinse | Prompt 5 — square headshot | Wide hero or desk scene | n/a | n/a |

All replacements require Ed's explicit confirmation before upload.

---

## Offer Asset Map

| Offer | Hero Image | Profile Image | Thumbnail |
|---|---|---|---|
| Prop Firm Rinse $97 | Prompt 6 — wide hero | Prompt 5 | Prompt 4 |
| Peter — AI Wholesaler Vault | Prompt 6 — wide hero | Prompt 5 | Prompt 2 |
| Matthew — Lead List Scraper | Prompt 6 or Prompt 2 | n/a | Prompt 4 |
| Andrew — Wholesale Automation | Prompt 2 or Prompt 3 | n/a | Prompt 4 |

---

## Current Replacement Queue

Generate these first. Then stage for Ed's approval before any publishing step.

| Priority | Asset | Prompt | Format | Destination |
|---:|---|---|---|---|
| 1 | Profile headshot (square) | Prompt 5 | 1:1 PNG | All 4 social profiles |
| 2 | Speaking-head thumbnail | Prompt 4 | 9:16 PNG | TikTok + IG Reel covers |
| 3 | Wide hero image | Prompt 6 | 16:9 PNG | Gumroad + landing page |
| 4 | Desk scene background | Prompt 3 | 16:9 PNG | Slideshow covers |
| 5 | 3/4 portrait | Prompt 2 | 4:5 PNG | Blog/article/X header |

---

## Generation Workflow

1. Paste the relevant prompt into ChatGPT / DALL-E 3 or Midjourney v6
2. Generate 4 candidates
3. Pick the strongest (most realistic, cleanest expression, no artifacts)
4. Save to: `C:\Users\oeroh\OneDrive\Documents\Claude\Projects\larp\brand_assets\`
5. Name using the naming system: `persona_[type]_[variant]_[date].png`
6. Show Ed for review before any publishing step
7. After approval, update profile images manually
8. Once first face is approved, use `--cref` (Midjourney) or img2img seeding to maintain consistency

---

## Disclosure Text (Paste Into All Published Materials)

> Brand visuals are AI-generated and are used as creative brand assets, not as a real-person identity.

---

## Files In This System

| File | Purpose |
|---|---|
| `docs/image-prompts.md` | All 6 prompts + master + negative + consistency rules + naming |
| `docs/brand-visual-system.md` | This file — colors, typography, platform map, offer map, workflow |
| `docs/brand-guide.md` | Voice, positioning, copy rules, disclosure |
| `docs/account-change-checklist.md` | Step-by-step replacement order with confirmation gates |
