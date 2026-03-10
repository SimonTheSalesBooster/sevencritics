# Seven Critics: A Copy Stress-Test Framework

> Run any marketing copy through 7 hostile reader personas who each try to break it. Find every failure point. Fix them. Ship copy that survives real inboxes.

## The core idea

You wrote the copy. You know the context. You're already bought in. That means you're the worst person to review it.

The Seven Critics forces a perspective shift by simulating 7 specific readers having 7 specific bad days — from the CEO with 43 unread emails to the subscriber who's been burned by every "game-changing framework" they've ever bought. If your copy survives all 7, it survives the inbox.

---

## The Skill: [seven-critics.md](seven-critics.md)

A structured review framework that runs any piece of marketing copy — email, ad, landing page, sales page, social post — through 21 failure checks (7 readers × 3 failure layers). Produces a severity-ranked failure report and a rebuilt version that passes.

Add `seven-critics.md` to your project as a skill file or system prompt. The framework uses standard markdown with YAML frontmatter — it works with any frontier model that accepts structured instructions.

### What's in the box

- **7 hostile reader personas** — each represents a real way people experience marketing copy
- **3 failure layers** — first impression, trust & engagement, action
- **21 failure checks per draft** — systematic, not vibes-based
- **Severity ranking** — CRITICAL / HIGH PRIORITY / LOW with clear thresholds
- **Rebuild rules** — fix without making copy longer, preserve voice, avoid cross-reader conflicts
- **Validation pass** — rebuilt copy gets re-tested until clean

### The 7 Readers

| # | Reader | What kills the copy |
|---|---|---|
| 1 | **The Time-Crushed Reader** | Subject line or first sentence doesn't earn the next line |
| 2 | **The Self-Conscious Reader** | Feels like a mass email that could be about anyone |
| 3 | **The Burned Skeptic** | Claims without proof, hype without substance |
| 4 | **The AI-Allergic Reader** | Polished corporate phrasing, templated sentence patterns |
| 5 | **The Lurker** | Nothing specific enough to break a 3-month habit of not clicking |
| 6 | **The Visual Reader** | Abstract concepts, vague descriptions, no scenes or moments |
| 7 | **The Inspiration Seeker** | Information without motivation, no feeling of capability |

### The 3 Failure Layers

1. **First Impression** — "In the first 3 seconds, I would stop reading because ___."
2. **Trust & Engagement** — "Even if I kept reading, I would lose interest because ___."
3. **Action** — "Even if I read the whole thing, I wouldn't do anything because ___."

---

## How to use it

### As a Claude Code slash command

```
/seven-critics
```

Then paste your copy when prompted. Works in any Claude Code session where the command file is installed.

### As a system prompt / skill file

Add `seven-critics.md` to your project's context. Then ask:

- "Run the 7 critics on this email"
- "Stress-test this landing page copy"
- "Tear this apart before I send it"

### Standalone

Paste `seven-critics.md` into any frontier model conversation and follow with your draft.

---

## What it produces

```
## Failure Report

CRITICAL failures found: [n]
[Which readers flagged it, what they said, which section it hit]

HIGH PRIORITY failures found: [n]
[...]

LOW failures found: [n]
[...]

---

## Rebuilt Copy

[The full rewritten copy that passed all 7 readers]

---

## What Changed

[Specific fixes and reasoning]

Passes completed: [n]
Remaining tradeoffs: [any acceptable HIGH PRIORITY items]
```

---

## When to use it

- Before sending any cold email sequence
- Before publishing a landing page
- Before launching an ad campaign
- Before hitting send on a newsletter
- When copy "feels right" but isn't converting
- When you suspect AI-generated copy sounds too polished

## When NOT to use it

- To write copy from scratch (this is a review tool, not a writing tool)
- On copy that's already performing well (don't fix what isn't broken)
- As a substitute for knowing your audience (the readers simulate — they don't replace real customer research)

---

## The standard

If the rebuilt version reads like it was written by a different person than the original draft, the review failed. The Seven Critics preserves voice while eliminating failure points. Tighter, not bigger. Sharper, not different.

---

*"Keep rolling, Simon & The Sprinters"*
