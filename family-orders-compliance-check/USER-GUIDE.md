# User guide: Family Orders & BCSA Compliance Check

**Skill folder:** `family-orders-compliance-check`

## What it does
Checks whether you or the other party are complying with final parenting orders, property orders or a Binding Child Support Agreement (BCSA). It quotes the exact order, runs the contravention test in Division 13A of the Family Law Act 1975, and gives a one-line verdict.

## When to use it
Use it whenever something happens that might be a breach: a missed call, a late changeover notice, a late payment, a message sent outside the required app, or overseas travel.

**Example requests:**
- "Is she in breach for not making the children available for the Wednesday call?"
- "I paid child support a day late. Am I in default under the BCSA?"
- "Here is the message they sent. Does it comply with the communication order?"

## What to give it
Upload or paste these. The first one is required; the rest make the result stronger.

1. **Your sealed orders**: the court order, the minute of orders, any notations and any information sheet attached.
2. **Your BCSA** (if you have one).
3. **The evidence for the event**: messages and call logs from the parenting app, supervisor reports, payment records, Services Australia letters.
4. **Dates**: exactly when the event happened.

If something is missing, the skill marks the affected checks "Not assessable" and asks for it. It asks one question at a time.

## What you get back
- **First use:** an obligations matrix built from your orders (order, obligation, who is bound, timing, evidence). Check it carefully; everything later relies on it.
- **Each check:** a one-line **Determination** (Compliant / Likely breach / Cannot determine), a **Key point**, the order quoted, the elements met or not met, any reasonable excuse, and one next action.
- A line confirming the law was checked on that date.

## How to read the results
- **Compliant**: the evidence shows the order was followed.
- **Likely breach**: the elements are met on the evidence you gave. Only a court decides a contravention.
- **Cannot determine**: a fact or document is missing. Supply it and ask again.

A reasonable excuse under section 70NAD can defeat a breach, so read that bullet before acting.

## Tips
- Run it on your own conduct too. A breach by you, especially of an injunction, is the highest-risk item.
- Keep a dated log of each result (fact and document only). It becomes your evidence if you ever need to apply to vary or enforce the orders.
- Never use anything the children told you as evidence. The skill will remind you of this.

## Works with
- `complaint-letter-format`: when the result needs to become a letter

## Before you rely on it
- **Not legal advice.** It checks documents against the law. It does not tell you what to do in your case. Speak to a solicitor, Legal Aid or LawAccess NSW before acting.
- **Check every citation.** The skill tells the AI to verify current law, but AI can still be wrong. Open each section and case it cites.
- **Keep it private.** Section 114Q of the Family Law Act 1975 (Cth) makes it an offence to publish anything that identifies people in family law proceedings. Never post a report online or share it outside your lawyer, the court or a regulator.
