# Seven Critics — Stress-Test Any Marketing Copy Through 7 Hostile Readers

**Your copy has 21 ways to fail. Find them before your audience does.** An AI skill for Claude Code that simulates 7 hostile readers on 7 bad days, each attacking your copy across 3 failure layers (first impression, trust, action). 21 checks per draft. Run before every send.

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/works_with-Claude_Code-orange)](https://claude.com/claude-code)
[![Strategy Sprints](https://img.shields.io/badge/built_by-Strategy_Sprints-red)](https://strategysprints.com)

---

You wrote the copy. You know the context. You're already bought in.

That makes you the worst person to review it.

Seven Critics simulates 7 hostile readers having 7 bad days — from the CEO with 43 unread emails to the subscriber burned by every "game-changing framework" they ever bought. If your copy survives all 7, it survives the inbox.

---

## Who this is for

- **Founders** shipping cold emails, landing pages, newsletters, or ads and not sure which parts are working
- **Copywriters and marketers** who need an adversarial review without begging a colleague for time
- **Consultants and coaches** rewriting client copy and needing a structured critique layer
- **Founders using AI-generated copy** who want to kill the tell-tale AI phrasing before it kills the send

---

## The 7 Readers

| # | Reader | What kills the copy |
|---|--------|---------------------|
| 1 | **The Time-Crushed** | Subject line doesn't earn the next line |
| 2 | **The Self-Conscious** | Feels like a mass email about anyone |
| 3 | **The Burned Skeptic** | Claims without proof, hype without substance |
| 4 | **The AI-Allergic** | Polished corporate phrasing, templated patterns |
| 5 | **The Lurker** | Nothing specific enough to break 3 months of not clicking |
| 6 | **The Visual Reader** | Abstract concepts, no scenes or moments |
| 7 | **The Inspiration Seeker** | Information without motivation |

## The 3 Failure Layers

Every reader attacks at three levels:

1. **First Impression** — "In the first 3 seconds, I stop reading because ___"
2. **Trust & Engagement** — "Even if I kept reading, I lose interest because ___"
3. **Action** — "Even if I read everything, I wouldn't do anything because ___"

**7 readers × 3 layers = 21 failure checks per draft.**

---

## What it produces

```
FAILURE REPORT
CRITICAL: [n] failures
HIGH PRIORITY: [n] failures
LOW: [n] failures

REBUILT COPY
[Full rewrite that passed all 7 readers]

WHAT CHANGED
[Specific fixes, specific reasoning]
```

**The standard:** if the rebuilt version reads like a different person wrote it, the review failed. Tighter, not bigger. Sharper, not different.

---

## Install

### Claude Code

```bash
git clone https://github.com/SimonTheSalesBooster/sevencritics ~/code/sevencritics
ln -s ~/code/sevencritics/seven-critics.md ~/.claude/commands/seven-critics.md
```

Then:
```
/seven-critics
```

Paste your copy when prompted.

### As a skill file

Add `seven-critics.md` to your project context. Then: "Run the 7 critics on this email."

### Standalone

Paste `seven-critics.md` into any frontier model (Claude, GPT, Gemini). Follow with your draft.

---

## When to use it

- Before sending any cold email sequence
- Before publishing a landing page or ad
- Before hitting send on a newsletter
- When copy "feels right" but isn't converting
- When AI-generated copy sounds too polished

## When NOT to use it

- To write copy from scratch (this reviews, it doesn't write)
- On copy that's already converting (don't fix what isn't broken)
- On copy under 50 words (not enough surface area for 21 checks)

---

## FAQ

**Do I have to rebuild my copy after running it?**
No. Sometimes only 2 of the 21 checks fail and the fix is a single line. Severity ratings make it scannable.

**Can I use this with GPT instead of Claude?**
Yes. The skill file is agent-agnostic. Works in any frontier model.

**Can I customize the 7 readers for my industry?**
Yes — that is exactly the right move. Fork the repo and add industry-specific personas. If you build something useful, open a PR.

**Does this replace human review?**
No. It replaces the 3-hour wait for a colleague to respond. Use it to ship a cleaner draft to the human reviewer.

**What if the rebuilt copy is worse than my original?**
That means the rebuilder compromised with the critics instead of resolving them. Re-run with a stricter instruction: "rebuild tighter, not bigger."

---

## Pair this with prospectingwork

Seven Critics + [prospectingwork](https://github.com/SimonTheSalesBooster/prospectingwork) = diagnosis + review. Write a positioning diagnostic with prospectingwork. Stress-test it with Seven Critics. Ship what survives.

---

## Related search terms

copy review AI · marketing copy AI · cold email review · cold email critique · copywriting tool · AI copywriter · email copy feedback · landing page copy review · adversarial copy review · copy stress test · kill AI writing · humanize AI copy · Claude copy skill · AI copywriting skill · Rick Rubin copy · David Ogilvy copy review · B2B copywriting · SaaS email copy · email conversion · cold email reply rate · Strategy Sprints methodology

---

## About

Built by [Simon Severino](https://linkedin.com/in/simonseverino), founder of [Strategy Sprints](https://strategysprints.com). Author of [*Strategy Sprints*](https://www.amazon.com/Strategy-Sprints-Accelerate-Growth-Transform/dp/1789668131) (Kogan Page) and [*Time Freedom*](https://www.amazon.com/Time-Freedom-Control-Calendar-Life/dp/1264269234) with Jay Abraham. Added $2B+ in sales to B2B clients across 72 countries.

## Strategy Sprints offers

- [**Sprint Club**](https://strategysprints.com/sprintclub) — $49/mo community, 7-day free trial, 47+ AI skills
- [**Jetpack Monthly**](https://strategysprints.com/jetpack) — $200/mo cohort workshop
- [**200K Club**](https://strategysprints.com/jetpack) — $900/mo 5-founder group coaching
- [**Private Jetpack**](https://strategysprints.com/jetpack) — $9K/mo 1:1 with Simon
- [**Certification**](https://calendly.com/strategysprint/certification) — for consultants teaching the method

**Book:** [30-min coffee](https://calendly.com/simonseverino/coffee-with-simon) · [90-day sprint discovery](https://calendly.com/strategysprint/discovery-call) · [Certification](https://calendly.com/strategysprint/certification)

## More open-source skills

- [**prospectingwork**](https://github.com/SimonTheSalesBooster/prospectingwork) — Rick Rubin positioning diagnostic
- [**ogilvy**](https://github.com/SimonTheSalesBooster/ogilvy) — copy review through David Ogilvy's lens
- [**emailwriter**](https://github.com/SimonTheSalesBooster/emailwriter) — write emails that book meetings
- [**natural-planning-for-teams**](https://github.com/SimonTheSalesBooster/natural-planning-for-teams) — 11-minute team planning model
- [**ClaudeSkills-SprintClub**](https://github.com/SimonTheSalesBooster/ClaudeSkills-SprintClub) — 18 AI sales skills

## License

MIT. Rip it apart, rebuild it better. *Keep rolling, Simon & The Sprinters.*
