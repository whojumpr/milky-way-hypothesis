---
title: Rules of Evidence
tags: [moc, meta]
---

# Rules of Evidence

How claims get made, marked, and attacked in this vault. Modeled on the genealogy vaults' rules, adapted for a hypothesis that mixes astronomy, scripture, history, and speculation — categories that must never be allowed to blur into each other.

## The posture: exploration, not litigation
Stated by James (2026-08-25): the goal is **not** perfection or deniability. The goal is to explore the idea in peace — piecing things together, cross-referencing facts, theology, mysticism, ancient teachings, and gematria — and to see what patterns emerge. The stress-test layer exists to *serve* that exploration, not to shut it down: honest tagging is what lets astronomy, scripture, and mysticism sit side by side in one vault without any of them having to impersonate another. A thread doesn't need to be provable to be explored here; it needs to be real on its own terms (the text actually says it, the arithmetic actually works, the tradition actually taught it) and labeled for what it is.

## Claim tags

Every factual assertion in a foundation note is audited in [[Claims Audit]] and carries one of:

- `#claim/solid` — mainstream, well-evidenced fact (astronomy that any survey confirms; a text that says what we claim it says)
- `#claim/contested` — a real scholarly dispute exists; both sides get named
- `#claim/misreading` — the cited source does not say what the claim needs it to say (anachronism, wrong referent, overtranslation)
- `#claim/interpretation` — a legitimate reading of a real text or fact, but a reading; others exist
- `#claim/speculation` — coherent, but nothing observable currently supports or could refute it
- `#claim/open` — not yet checked; needs research before it gets used to support anything
- `#claim/pattern` — a real correspondence (a verified gematria equivalence, a recurring motif, a structural parallel) offered as *illumination*, not evidence. Patterns may decorate, connect, and suggest; they never carry weight.

## Gematria protocol
Gematria threads are welcome (see `explorations/`), under discipline that keeps them honest:
1. **The spelling must be the actual Masoretic spelling** of the word in the cited verse (defective vs. plene matters), stated in the note.
2. **The arithmetic is computed and shown**, standard values (*mispar hechrachi*), finals at regular values unless explicitly noted. No value gets written down that we haven't summed ourselves.
3. **Same method on both sides of any match.** Switching counting systems mid-comparison (regular ↔ *mispar gadol* ↔ reduced) to force a hit is the numerological equivalent of a strawman and is banned.
4. **State the search space.** With ~dozens of candidate words and several counting methods, coincidental matches are cheap; a match is interesting in proportion to how *few* degrees of freedom produced it. Say what was tried.
5. Every gematria observation is tagged `#claim/pattern` and inherits the load-bearing ban automatically.

**Rule:** nothing tagged `contested`, `misreading`, or `speculation` may be used as a load-bearing support for the hypothesis. It can be scaffolding, color, or a lead — never a foundation.

## The stress-test protocol

1. Every objection goes in the [[Objections Ledger]] at full strength — no softening an objection to make it survivable.
2. An objection is only **retired** when it is actually answered, with the answer written down. "We addressed that" without a written answer doesn't count.
3. The [[Steelman]] is rebuilt from whatever survives — it is allowed to be smaller than the original hypothesis. A smaller claim that stands beats a bigger claim that leans.
4. Distinguish the three versions of the hypothesis (see [[The Hypothesis]]). An objection fatal to one version may leave another untouched — say which.
5. When lore and fact diverge, record both. The goal is not to protect the idea but to find out what's true, and to preserve *why* the idea was compelling even where it fails.

## Working rules for this repo

Carried over from the genealogy projects:

1. **Never commit credentials.** No API keys, tokens, passwords, cookies, or `.env` files — ever, in any commit, including history. `.gitignore` enforces the obvious cases; the rule covers the non-obvious ones.
2. **Always ask before commits.** No commit or push happens without James's explicit go-ahead in the session where it happens.
3. **Log after every task.** Every working session gets an entry in [[Research Log]]; every change that lands gets a line in `CHANGELOG.md`.
4. **Before anything goes public** (making the repo public, opening a public PR), the content gets a review round — this repo makes public claims, which is an always-review category.
