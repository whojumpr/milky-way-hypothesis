---
title: Rules of Evidence
tags: [moc, meta]
---

# Rules of Evidence

How claims get made, marked, and attacked in this vault. Modeled on the genealogy vaults' rules, adapted for a hypothesis that mixes astronomy, scripture, history, and speculation — categories that must never be allowed to blur into each other.

## Claim tags

Every factual assertion in a foundation note is audited in [[Claims Audit]] and carries one of:

- `#claim/solid` — mainstream, well-evidenced fact (astronomy that any survey confirms; a text that says what we claim it says)
- `#claim/contested` — a real scholarly dispute exists; both sides get named
- `#claim/misreading` — the cited source does not say what the claim needs it to say (anachronism, wrong referent, overtranslation)
- `#claim/interpretation` — a legitimate reading of a real text or fact, but a reading; others exist
- `#claim/speculation` — coherent, but nothing observable currently supports or could refute it
- `#claim/open` — not yet checked; needs research before it gets used to support anything

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
