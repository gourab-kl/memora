# Playbook: term-sheet-compare

**Trigger:** "run the term-sheet-compare playbook" then paste or attach both term sheets

**When to use:** When you have two or more term sheets and need to understand what's actually different before talking to your lawyer.

---

## What it does

1. Read your current cap table context, fundraise details, and company stage from `CLAUDE.md`.
2. Read both term sheets provided.
3. Extract and compare every material term side by side:

   **Economics:**
   - Pre-money valuation and resulting ownership percentage
   - Option pool size and whether it's pre- or post-money (this changes your effective dilution significantly)
   - Liquidation preference: 1x non-participating vs. participating preferred vs. 2x — and what each means for founder proceeds at different exit sizes
   - Anti-dilution: broad-based weighted average vs. full ratchet

   **Control:**
   - Board composition: who gets seats, who gets observer rights
   - Protective provisions: what decisions require investor approval
   - Pro-rata rights: do they have the right to follow on in future rounds
   - Information rights: what reporting are you committing to

   **Founder terms:**
   - Vesting acceleration: single trigger vs. double trigger
   - Drag-along provisions
   - Right of first refusal on founder shares

4. Write a plain-English comparison that flags:
   - Which term sheet is better overall and why
   - The 2-3 terms where they differ most materially
   - Any terms that look standard but are founder-unfriendly at your stage
   - Questions to ask each investor before signing

5. Save to `Process/fundraise/term-sheet-compare-[date].md`

**Output format:** `Process/fundraise/term-sheet-compare-YYYY-MM-DD.md`

**Notes:**
- This is not legal advice. Take this analysis to your lawyer before signing anything.
- Valuation is not the only number that matters. A $12M cap with a participating liquidation preference can be worse than a $10M cap with a clean 1x non-participating structure.
- The investor behind the term sheet matters as much as the terms. A better investor on worse terms often beats a worse investor on better terms.
