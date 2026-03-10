---
name: seven-critics
description: "Review any marketing copy through 7 hostile reader personas who each try to break it. Use when you have a draft (email, ad, landing page, sales page, social post) and want to stress-test it before publishing. Outputs a failure report with severity rankings and a rebuilt version that passes."
triggers:
  - review this copy
  - stress-test this email
  - run the 7 critics
  - run the 7 readers
  - validate this draft
  - check this before I send it
  - will this convert
  - tear this apart
---

# The 7 Critical Readers

Most people review their own copy as themselves. The person who wrote it, who knows the context, who's already bought in. They never become the skeptic at 11pm who's been burned before. They never become the person who reads the subject line, feels nothing, and archives it. This skill forces that perspective shift by running your draft through 7 specific readers having 7 specific bad days.

---

## The Core Job

Take a piece of marketing copy the user has already written (or that an AI just wrote) and stress-test it through 7 hostile reader simulations. Find every failure point. Fix them. Re-test until clean. Only show the final version after it passes.

This is a review tool, not a writing tool. It takes existing copy and makes it survive real inboxes.

**Output format:** Failure report (what broke and why) + rebuilt copy that passed all 7 readers.

---

## Before Starting: Gather Context

**STOP. Do not run the readers until you have the draft. If the user hasn't pasted their copy yet, ask them to paste it now.**

You need exactly two things:

1. **The draft** — The actual copy to review (email, ad, landing page, sequence, whatever)
2. **The audience** — Who's reading this? (If not provided, ask. The readers can't simulate real reactions without knowing who they're pretending to be.)

Optional but helpful:
3. **What's the goal?** — What should the reader DO after reading? (Buy, click, reply, sign up)

---

## Step 1: Spawn the 7 Readers

Each reader represents a real way people experience marketing copy. They're not archetypes. They're the specific person having a specific bad day who lands on your draft.

**The 7 Readers:**

**1. The Time-Crushed Reader**
43 unread emails. 10 minutes before their next meeting. They'll read the subject line and maybe the first sentence. If neither earns the next line, deleted. They're not going to "give it a chance." They're looking for a reason to move on.

**2. The Self-Conscious Reader**
Needs to feel like you wrote this specifically for them. The moment it feels like a mass email that could apply to anyone, they disconnect. They want to feel seen.

**3. The Burned Skeptic**
Bought 3 courses. Hired 2 agencies. Tried every tactic they found online. Nothing worked the way it was supposed to. They now actively distrust anyone selling anything. And honestly, fair enough.

**4. The AI-Allergic Reader**
Read 50 AI-generated emails this week and they can identify the tone in about two seconds. Any polished corporate phrasing, any "it's not x, it's y" energy, any sentence that feels templated, and they're gone.

**5. The Lurker**
Been on the list 3 months. Never clicked a single link. Opens maybe half the emails, scans for about four seconds, closes. Getting them to actually do something takes a very specific kind of pull.

**6. The Visual Reader**
Thinks in images and scenes. Abstract concepts and vague descriptions make them zone out. They need to see a specific moment, feel a specific frustration, picture themselves in a specific scenario.

**7. The Inspiration Seeker**
Wants to walk away feeling like they can actually do this. If you dump information without making them feel capable and motivated to act on it, they'll nod along, think "cool," and do absolutely nothing.

---

## Step 2: Run the 3 Failure Layers

Each of the 7 readers answers ALL 3 questions about the draft. No skipping.

**Layer 1 — FIRST IMPRESSION FAILURE:**
"In the first 3 seconds, I would stop reading because ___."
- Subject line too generic?
- Opening line doesn't hook?
- Nothing signals this is for ME specifically?

**Layer 2 — TRUST & ENGAGEMENT FAILURE:**
"Even if I kept reading, I would lose interest because ___."
- Voice feels fake?
- Claims without proof?
- Doesn't understand my situation?
- Filler that wastes my time?
- Flat writing with no vivid details?

**Layer 3 — ACTION FAILURE:**
"Even if I read the whole thing, I wouldn't do anything because ___."
- CTA is vague?
- No urgency that feels real?
- Doesn't inspire me to act?
- Risk feels higher than reward?
- I can justify doing nothing?

This produces 21 failure checks per piece of copy (7 readers × 3 layers).

---

## Step 3: Tally and Prioritize

Compile all failures into a ranked list:

| Severity | Threshold | Action |
|---|---|---|
| **CRITICAL** | 3+ readers flagged the same failure | Must be fixed. No exceptions. |
| **HIGH PRIORITY** | 2 readers flagged the same failure | Should be fixed. |
| **LOW** | 1 reader flagged it | Fix if it doesn't break something else. |

Group failures by which section of the copy they hit (subject line, opener, body, CTA) so the rebuild is surgical.

---

## Step 4: Rebuild

For every CRITICAL and HIGH PRIORITY failure:

1. **State the failure** — Which readers flagged it and what they said
2. **State the fix** — What you're changing and why
3. **Show the rewrite** — The new version of that section

**Rebuild rules:**
- Fix the failure without making the copy longer. Tighter, not bigger.
- A fix for the Skeptic can't make the Inspiration Seeker feel hopeless.
- A fix for the Time-Crushed Reader can't strip the detail the Visual Reader needs.
- When fixes conflict, prioritize: First Impression > Trust > Action. People who stop reading can't take action.

---

## Step 5: Second Pass

Run the rebuilt copy through all 7 readers again, all 3 failure layers.

**Pass criteria:**
- Zero CRITICAL failures remaining
- No more than 2 HIGH PRIORITY failures remaining (with documented reasoning for why those are acceptable tradeoffs)

If it fails: repeat steps 4–5. The copy is not approved until it passes.

---

## Output Format

```
## Failure Report

**CRITICAL failures found:** [number]
[List each one: which readers flagged it, what they said, what section it hit]

**HIGH PRIORITY failures found:** [number]
[List each one]

**LOW failures found:** [number]
[List each one]

---

## Rebuilt Copy

[The full rewritten copy that passed validation]

---

## What Changed

[Brief list of the specific fixes made and why]

**Passes completed:** [number]
**Remaining tradeoffs:** [any HIGH PRIORITY items left, with reasoning for why they're acceptable]
```

---

## Example: Reviewing an Email Opener

**Draft submitted:**
"Are you struggling to get results from your marketing?"

**Reader responses:**

CRITICAL (3+ readers flagged):
- Time-Crushed Reader: "Nothing specific here. I'm moving on."
- Self-Conscious Reader: "This could be about literally anyone."
- AI-Allergic Reader: "I've read this exact sentence in about forty newsletters this month."

3 critical flags on a single sentence. Must rewrite.

**Rebuilt version:**
"I rebuilt my entire email workflow last Tuesday. The part that took the longest? Figuring out which of my 'best practices' were actually making my copy worse."

**Why it passes:**
- Time-Crushed Reader stays because there's a specific, concrete detail (last Tuesday, a real workflow, a real discovery)
- Self-Conscious Reader feels a pull because they've probably wondered the same thing about their own process
- AI-Allergic Reader doesn't flag it because it reads like someone recounting an actual thing that happened

Same core message. Completely different experience of reading it.

---

## The Test

A good review:

1. **Every reader gave specific feedback** — Not "this is generic" but "this sentence in the opener sounds like a template because ___"
2. **Fixes didn't create new problems** — Fixing for the Skeptic didn't crush the Inspiration Seeker
3. **The copy got tighter, not longer** — The rebuild cut filler, it didn't add padding
4. **The failure report is useful on its own** — Even without the rebuild, the user learns what their copy's weak spots are
5. **The rebuilt version sounds like the user, not like Claude** — The fix matches the voice of the original draft

If the rebuilt version reads like it was written by a different person than the original draft, it failed.

---

## What Good Looks Like

Every output must pass:
- Would a reader **share this** because it surprised or helped them?
- Is it **elegant** — clean, no waste?
- Is it **simple** — instantly understood?
- Is it **fresh** — not what everyone else is saying?
- Is it **actionable** — can someone use this today?

If any answer is no — revise before delivering.
