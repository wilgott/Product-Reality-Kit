# Example: Diagnostic Output

This is a fictional example based on the sales request in this folder.

Use it to see how a messy request can become a clearer product decision.

---

## Situation

A large enterprise prospect wants custom approval logic.

Sales wants to commit it this quarter to win a EUR 180k ARR deal.

Engineering says it will add workflow complexity.

CS says the broader problem may be real, but the exact solution is not validated.

---

## Diagnostic used

- [When Sales Drives the Roadmap](../../diagnostics/when-sales-drives-the-roadmap.md)
- [When Enterprise Wants an Exception](../../diagnostics/when-enterprise-wants-an-exception.md)
- [When "Just Make It Configurable" Sounds Easy](../../diagnostics/when-just-make-it-configurable-sounds-easy.md)

---

## The request

> Build custom approval logic for one enterprise prospect.

---

## The customer problem

Compliance teams in regulated companies need more control over how onboarding flows are approved before they go live.

They need to reduce risk, keep auditability, and avoid manual workarounds.

---

## What looks real

There is a real signal here.

Approval control is not only one customer's random idea.

Evidence:

- One large enterprise prospect is asking for custom approval logic.
- Three existing mid-market customers have mentioned approval flexibility.
- Two lost deals mentioned compliance workflow control.
- The product is moving upmarket, where approval and auditability matter more.

This is probably worth investigating.

---

## What looks risky

The requested solution is too specific.

Risks:

- It may only fit one customer process.
- It touches workflow rules, permissions, audit logs, and manual review.
- It may add many test combinations.
- It may make onboarding harder.
- It may create a feature Sales can sell but CS struggles to implement.
- It may turn the product into custom workflow software instead of a clear product.

---

## Possible false diagnoses

### "We need this feature to win enterprise."

Maybe.

But the real need may be approval control, auditability, and better workflow governance.

The exact custom logic may not be the right product solution.

### "It is just configuration."

No.

This touches important parts of the workflow engine.

Configuration does not remove complexity.

It often moves complexity to customers, CS, Support, QA, and documentation.

### "The deal size justifies it."

Maybe.

But the deal size should not be the only reason.

The better reason would be that this is a reusable problem for the market VerifyFlow wants to serve.

---

## Questions to ask next

### Ask the customer

- What risk are you trying to reduce?
- What happens today without this approval logic?
- Which teams need to approve flows?
- How often would this logic change?
- What audit evidence do you need?
- What is the simplest approval process that would work?
- Is this a must-have for all workflows or only high-risk workflows?

### Ask Sales

- Is this coming up in other enterprise deals?
- Is this a deal blocker or a negotiation point?
- What exact promise has been made?
- What competitor capability is being compared?
- Would a simpler approval capability help close the deal?

### Ask CS

- Which existing customers have similar problems?
- What workarounds are customers using today?
- Would CS be able to onboard this without heavy manual work?
- What support issues would this create?

### Ask Engineering

- What is the smallest reusable version?
- What parts of the workflow engine are affected?
- What are the long-term maintenance risks?
- What would make this safer to build later?

---

## Decision options

### Option A: Build the exact custom logic now

Pros:

- May help close the EUR 180k ARR deal.
- Shows responsiveness to enterprise needs.
- Solves the customer's immediate request.

Cons:

- High risk of one-off complexity.
- May hurt roadmap focus.
- May be hard to maintain and support.
- May not be reusable for other customers.

### Option B: Say no completely

Pros:

- Protects roadmap focus.
- Avoids complexity.
- Keeps the product simpler.

Cons:

- May lose the deal.
- May ignore a real upmarket signal.
- Sales may feel Product is blocking revenue.

### Option C: Do discovery on a reusable approval capability

Pros:

- Treats the customer problem seriously.
- Avoids committing to a one-off solution too early.
- Can validate if this matters for the broader ICP.
- Gives Sales a clear and honest message.

Cons:

- May not satisfy the prospect's timeline.
- Does not give Sales an immediate commitment.
- Requires focused discovery work.

### Option D: Offer a workaround now and evaluate product capability later

Pros:

- May keep the deal moving.
- Reduces short-term custom product work.
- Gives Product time to learn.

Cons:

- Workaround may be operationally heavy.
- Customer may reject it.
- CS or implementation may carry the burden.

---

## Recommended decision

Do not build the exact custom approval logic now.

Run focused discovery on a reusable approval control capability for regulated mid-market and enterprise customers.

Offer a clear workaround if possible.

Review the decision after:

- 5 customer interviews
- Review of lost deal notes
- Engineering spike on reusable approval patterns
- Sales review of active enterprise pipeline

---

## What we are saying no to

- No to committing roadmap capacity based only on one enterprise deal.
- No to building customer-specific workflow logic into the core product.
- No to treating configurability as free.
- No to letting Sales define the solution before Product understands the pattern.

---

## What we are saying yes to

- Yes to understanding the customer problem.
- Yes to evaluating whether approval control is a real market need.
- Yes to working with Sales on a clear customer message.
- Yes to finding a reusable product direction if the evidence supports it.

---

## Next step

Create a Product Decision Record.

See:

- [Product Decision Record example](product-decision-record.md)
