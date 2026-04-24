# Operating Doc — Content-to-Cash Pipeline

Updated: 2026-04-24

---

## Current Reality

**What is working:**
- TikTok posting via `tiktok_post_bot.py` — confirmed functional
- X/Twitter manual posting via logged-in Chrome Profile 4 — confirmed functional
- `master_scheduler.py` was last running; status unknown after 8-day gap
- `slideshow_generator.py` — functional, produces 7-slide MP4s
- `tweet_queue.json` — 29 tweets queued
- `video_queue.json` — topics queued, video_gen produces clips
- Prop Firm Rinse Gumroad listing — LIVE at https://ebadventure46.gumroad.com/l/lmyhtx ($97)

**What is not working / stale:**
- X/Instagram Playwright sessions — stale, need manual re-login
- Facebook compose bot — unreliable
- Blotato — 401 Unauthorized, queue-only mode
- Peter's AI Wholesaler Vault — no Gumroad listing yet (second account)
- AI-woman profile images — not yet generated or uploaded

**What is paused intentionally:**
- Affiliate marketing
- Trading bot development
- TikTok Shop (not main lane)
- Full AI video pipeline (builds after slideshow is stable)

---

## Pipeline Structure

```
ONE MAIN OFFER LANE:     Prop Firm Rinse ($97)
ONE SUPPORT LANE:        Strongest related PDFs
ONE SERVICE LANE:        AI hosting / agent service
ONE OPTIONAL SIDE LANE:  Depop / Poshmark (only if it does not distract)
```

### Content-to-Cash Flow

```
1. Ed selects the offer for the day
2. Draft a slideshow (7 slides, navy/cream, direct CTA)
3. Draft 3-5 TikTok captions for it
4. Review queue → Ed approves
5. Post TikTok via tiktok_post_bot.py
6. Post X manually via logged-in browser
7. Traffic → Gumroad link → sale
```

### Format Order (Do Not Skip Steps)

1. Still-image asset pack — generate profile + portrait + hero first
2. Slideshow videos — primary content format
3. Talking-head style covers — thumbnail support
4. Full AI video — only after steps 1-3 are stable

---

## Offer Stack

| Lane | Offer | Price | Status | CTA Destination |
|---|---|---|---|---|
| Main | Prop Firm Rinse | $97 | LIVE | https://ebadventure46.gumroad.com/l/lmyhtx |
| Support | Strongest PDF | TBD | Needs listing | TBD |
| Service | AI hosting / agent | TBD | Needs offer page | TBD |
| Side | Depop / Poshmark | per item | Paused | — |

---

## Posting Schedule (Draft-Only Until Sessions Confirmed)

| Platform | Cadence | Bot/Method | Status |
|---|---|---|---|
| TikTok | 1 per day | `tiktok_post_bot.py` | Working |
| X/Twitter | 1-2 per day | Manual logged-in browser | Working |
| Instagram | 1 per day | `instagram_bot.py` | Stale session |
| Facebook | 1 per day | `facebook_bot.py` | Unreliable |

**Priority:** TikTok first. X second. IG and FB only after sessions refreshed.

---

## Accounts

| Platform | Handle | Profile Status |
|---|---|---|
| TikTok | @shophere79 | Live, text logo profile pic |
| X/Twitter | @Hmmmm355382 | Live, Prop Firm Rinse bio |
| Instagram | @janes_store34 | Live, stale session |
| Facebook | Prop Firm Rinse page | Live, compose unreliable |

---

## Visual Identity Lock

Persona: AI-generated conservative-American woman, white, late 20s, navy/cream wardrobe.
Brand: Steady Ground.
Disclosure: All visuals are AI-generated brand assets, not a real-person identity.

Master prompt: see `docs/image-prompts.md`

Generation order:
1. Profile image (square, Prompt 5)
2. Speaking-head thumbnail (9:16, Prompt 4)
3. Wide hero (16:9, Prompt 6)
4. Desk scene (16:9, Prompt 3)
5. 3/4 portrait (4:5, Prompt 2)

---

## Reporting

One method: check `video_review_dashboard.html` and `scheduler_status.json` in larp/bots daily.
One email template: see `docs/pipeline-status-email.md`.

---

## Human Approval Boundaries

Stop before:
- Login / passkey / 2FA
- OAuth / app connection approval
- Publishing live content
- Saving live profile or banner changes
- Sending email
- Payment actions
