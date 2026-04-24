# Monetization Roadmap

Updated: 2026-04-23 — Claude Code sync round

---

## Operating Model

| Platform | Role |
|---|---|
| ChatGPT | Strategy, coordination, ranking, monetization thinking |
| Codex | Execution, repo edits, browser inspection, integration setup |
| Claude / Cloud Code | Prompt cleanup, workflow review, handoff docs, repo sync |
| Hermes | Future router after provider auth is complete |

---

## Active Revenue Stack

Six agents. Everything else is on ice or merged.

### Lane Map

```
Ed Money Agent OS (coordinator)
├── John (promo engine + content)
│   ├── promotes → Prop Firm Rinse ($97)
│   ├── promotes → Peter's AI Wholesaler Vault
│   ├── promotes → Matthew's Lead List Scraper ($497)
│   └── promotes → Andrew's Wholesale Automation
├── TikTok Shop (separate ecommerce lane)
│   ├── Shopify + CJ Dropshipping
│   ├── TikTok Shop tab
│   ├── Depop + Poshmark (secondary)
│   └── Draft content pipeline
├── Peter (digital product)
│   └── AI Wholesaler Vault → Gumroad (second account)
├── Matthew (data product)
│   └── Lead List Scraper → Gumroad / direct sale
└── Andrew (automation service)
    └── Wholesale pipeline → outreach / retainer
```

---

## Revenue Loop (Daily)

1. Ed Money Agent OS selects the lane of the day
2. John produces draft content for that lane
3. Ed reviews and approves content
4. Content posts to TikTok (confirmed working) + X (manual, confirmed working)
5. Traffic hits Gumroad link → sale
6. TikTok Shop lane runs in parallel as direct product revenue

---

## This Week — Priority Actions Per Agent

### John (Priority 1)
- [ ] Confirm which offer to push this week
- [ ] Produce 5 TikTok draft captions
- [ ] Produce 5 X/Twitter draft posts (link-first)
- [ ] Produce 2 Instagram Reel concepts
- [ ] Produce 1 Facebook post draft
- [ ] Ed approves → post to TikTok Studio and X browser (both confirmed working)

### Peter (Priority 2)
- [ ] Ed logs into oroaramacella@gmail.com Gumroad
- [ ] Claude Code prepares listing copy (headline, bullets, CTA)
- [ ] Ed publishes listing
- [ ] John produces 3 promo scripts pointing to it

### TikTok Shop (Priority 3)
- [ ] Confirm all 4 Shopify products have active listings
- [ ] Draft TikTok captions for each of the 4 products
- [ ] Ed approves 1 caption → post manually to TikTok Studio
- [ ] Source 2 new CJ products as draft additions

### Matthew (Priority 4)
- [ ] Decide: tool sale or done-for-you data service?
- [ ] Draft 1-page offer + sample list concept
- [ ] John produces 3 promo scripts
- [ ] Ed publishes listing

### Andrew (Priority 5)
- [ ] Fix 2 open pipeline bugs
- [ ] Draft 1-paragraph service description
- [ ] Send 5 direct outreach messages

---

## Rules That Never Change

- All content is draft-only until Ed explicitly confirms posting
- No login, passkey, 2FA, OAuth, or account-connection step is crossed without Ed's approval
- No email is sent without Ed confirming recipient and content
- Hermes is not used for production routing until provider auth is complete
- All repo changes are committed and pushed after every sync session

---

## What Is On Ice

| Agent | Condition To Revive |
|---|---|
| Luke — Automation Service | Active stack generating revenue + capacity exists |
| Thomas — Trading Bot | Paper trade results confirm viability |
| Grace — Trade Signal Review | Thomas revived |
| James — AI Community | Community platform chosen and budget allocated |
| Paul — Affiliate Bot | Apex affiliate signup completed |
| Bartholomew | Affiliate infrastructure confirmed working |

---

## Merge Summary

| Merged Into | What Was Absorbed |
|---|---|
| John | Daniel, Philip, Simon |
| TikTok Shop | Product Image Worker, Listing Optimizer Worker, AI Video Pipeline Worker |

---

## Accounts That Need Action (By Ed)

| Account | Action Needed |
|---|---|
| Gumroad (second: oroaramacella@gmail.com) | Log in → publish Peter's listing |
| Apex Trader Funding | Sign up for affiliate program |
| X/Twitter via Playwright | Run `python manual_login.py --platform twitter` |
| Instagram via Playwright | Run `python manual_login.py --platform instagram` |
| Hermes in WSL2 | Run `hermes login --provider nous --no-browser` |
| GitHub CLI | Run `gh auth login` |
