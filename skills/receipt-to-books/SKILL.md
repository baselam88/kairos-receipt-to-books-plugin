---
name: receipt-to-books
description: Turns a receipt photo or pasted receipt text into a categorized expense entry ready for the books.
---

# Receipt-to-Books Catcher

## What this does

Turns a receipt photo or pasted receipt text into a categorized expense entry ready for the books.

## Inputs to gather first

Ask for (or work from what the user already gave) — do not proceed on invented values:

- Context from the brief: Read receipt (vendor, date, total, tax), categorize against a standard SMB chart of accounts, flag unclear items instead of guessing, output a bookkeeping-ready row + monthly summary format.
- The business's own facts for this job (services, prices or price basis, service area, hours) as the user states them.
- Any example of the business's voice (a past message, post, or document) when the output is customer-facing.
- The constraints: what must not be promised, sent, or changed without the owner's say-so.

## Procedure

1. Restate the job in one line: the output, who it's for, and the decision or action it feeds. If that can't be stated, ask one question before producing anything.
2. Assemble the inputs above. List anything missing explicitly — a missing fact is flagged, never filled by guessing.
3. Read receipt (vendor, date, total, tax), categorize against a standard SMB chart of accounts, flag unclear items instead of guessing, output a bookkeeping-ready row + monthly summary format.
4. Produce the output in the format below, in the business's voice where it's customer-facing.
5. Run the quality-bar checks. Fix failures before showing the user; where a check can't pass on the supplied facts, say so and name what's needed.
6. End with the single next step (send / approve / book / file) and its owner.

## Output format

The deliverable named in the procedure, complete and ready to use: no placeholders, no lorem, no 'insert here'. Anything the user must still decide is collected in a short decision list at the end.

## Hard rules

- Work only from facts the user supplies in this session. Never invent a price, a date, a policy, a result, or a customer fact; where a fact is missing, name it as missing and ask or flag it.
- Any figure that is a projection or an industry range is labelled an estimate, with its basis stated. Measured numbers come only from records the user provides.
- Anything that will be sent to a customer, posted publicly, or spent is a draft for the user's approval first — never send, post, or commit it yourself.
- Never promise a refund, discount, remedy, deadline, or outcome on the user's behalf.
- Plain language throughout: write for the business owner and their customer, not for an industry insider.
- Outcome figures in the source catalog are targets and estimates, not guarantees — present them that way to anyone who asks.

## Quality bar (check before delivering)

- Every fact in the output traces to something the user supplied in this session.
- Every estimate is labelled an estimate, with its basis.
- The output is usable as-is by its intended reader — no step depends on information the reader doesn't have.
- If any check fails, the delivery says which one and what's needed to fix it.
