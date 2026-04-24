# Pipeline Status Email Template

Updated: 2026-04-24

Use this template once per day. Send only after Ed confirms "send it" explicitly.

---

## Template A — Healthy

**Subject:** Pipeline OK — [Date]

Pipeline is running.

- TikTok: [X] posts queued / [X] posted today
- X/Twitter: [X] tweets queued / [X] posted today
- Gumroad: [X] sales today / [X] total
- Scheduler: running (last checked [time])
- Review queue: [X] pending / [X] approved

Next action: [one sentence — what happens next]

No blockers.

---

## Template B — Blocked

**Subject:** Pipeline BLOCKED — [Date] — Action Needed

Pipeline is blocked. Posting is paused or degraded.

**What is blocked:**
- [Platform]: [reason — e.g., stale session, bot error, queue empty]

**What is still working:**
- [Platform or queue]: [status]

**What Ed needs to do:**
- [ ] [Specific step — e.g., run `python manual_login.py --platform twitter`]
- [ ] [Specific step]

Once unblocked, pipeline resumes automatically.

---

## Fill-In Reference

| Field | Where to check |
|---|---|
| TikTok posts | `video_review_dashboard.html` or `tiktok_post_log.json` |
| X tweets queued | `tweet_queue.json` (count unposted items) |
| Scheduler status | `scheduler_status.json` |
| Review queue | `video_review_manifest.json` |
| Gumroad sales | Log in to Gumroad dashboard manually |

---

## Send Rules

- Do not send without Ed's "send it"
- Do not send if the recipient has not been confirmed
- Send from the signed-in Gmail browser (Profile 4) using native Gmail compose — do not use bot email paths
