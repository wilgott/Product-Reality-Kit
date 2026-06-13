# Example Product Decision Record

This is a fictional example.

---

# PDR-001: Do not build custom enterprise approval logic as requested

## Status

Accepted

## Date

2026-06-12

## Owner

Product

---

## Decision

We will not build the exact custom approval logic requested by the enterprise prospect right now.

We will run focused discovery on a reusable approval control capability for regulated mid-market and enterprise customers.

We will review the decision in 30 days.

---

## Customer problem

Compliance teams in regulated companies need more control over how onboarding flows are approved before they go live.

They need to reduce risk, keep auditability, and avoid manual workarounds.

The signal is credible.

The requested solution is not validated yet.

---

## Context

A large enterprise prospect says they will sign a EUR 180k ARR contract if VerifyFlow builds custom approval logic for their compliance team.

Sales wants Product to commit this quarter.

Engineering says the request touches workflow rules, permissions, audit logs, manual review queues, and testing complexity.

CS says existing customers have mentioned approval flexibility, but not this exact solution.

---

## What we know

- One large enterprise prospect is asking for this exact solution.
- Three existing mid-market customers have mentioned approval flexibility.
- Two lost deals mentioned compliance workflow control.
- The company is moving upmarket, where approval and auditability matter more.
- Engineering expects medium to high complexity.
- CS expects onboarding and support impact if the solution is too flexible.
- Sales sees a clear short-term revenue opportunity.

---

## What we do not know yet

- We do not know if this exact approval logic is needed by the broader ICP.
- We do not know if customers would pay extra for advanced approval control.
- We do not know if this should be core product, paid add-on, service, or implementation work.
- We do not know if a simpler workflow template would solve most of the problem.
- We do not know the full maintenance cost.

---

## Options considered

### Option A: Build the exact custom logic now

Pros:

- May help close the EUR 180k ARR deal.
- Gives Sales a clear commitment.
- Solves the prospect's immediate request.

Cons:

- High risk of one-off complexity.
- May create long-term workflow engine maintenance cost.
- May make onboarding and support harder.
- May not be useful for other customers.
- May pull roadmap capacity away from broader customer problems.

### Option B: Say no completely

Pros:

- Protects roadmap focus.
- Avoids complexity.
- Keeps the product simpler.

Cons:

- May lose the deal.
- May ignore a real upmarket signal.
- May create friction with Sales.

### Option C: Run discovery on reusable approval control

Pros:

- Takes the customer problem seriously.
- Avoids committing to a one-off solution too early.
- Helps us learn if this is a real market pattern.
- Gives Product, Sales, CS, and Engineering a clearer decision path.

Cons:

- Does not give Sales an immediate build commitment.
- May not satisfy the prospect's timeline.
- Requires focused discovery effort.

### Option D: Offer a workaround while discovery runs

Pros:

- May keep the deal moving.
- Reduces short-term product complexity.
- Gives us time to learn.

Cons:

- The workaround may be operationally heavy.
- The customer may reject it.
- CS or implementation may carry the burden.

---

## Trade-off

We accept that we may lose or slow down this enterprise deal.

We are choosing not to let one customer define workflow complexity before we understand the broader pattern.

We are also choosing to spend time on discovery because the signal may be strategically important for regulated mid-market and enterprise customers.

---

## What we are saying no to

- We are saying no to building custom approval logic exactly as requested.
- We are saying no to committing roadmap capacity based only on one enterprise deal.
- We are saying no to treating configurability as free.
- We are saying no to letting Sales define the solution before Product understands the customer problem.

---

## What we are saying yes to

- We are saying yes to investigating approval control as a real customer problem.
- We are saying yes to talking to similar customers.
- We are saying yes to reviewing lost deal notes.
- We are saying yes to finding a reusable product direction if the evidence supports it.
- We are saying yes to giving Sales a clear and honest message.

---

## Reversal criteria

We will reconsider if:

- Five or more ICP customers describe the same approval control problem.
- The request appears in a meaningful share of enterprise pipeline.
- Lost deal analysis shows approval control is a repeated reason for losing deals.
- Discovery shows a simple reusable pattern.
- Engineering finds a low-risk way to support approval control without creating high workflow complexity.
- Customers show willingness to pay for advanced approval control.

---

## Review date

Review in 30 days.

Before review, complete:

- 5 customer interviews
- Review of lost deal notes
- Engineering spike on reusable approval patterns
- Sales review of active enterprise pipeline
- CS review of existing customer workarounds

---

## Communication plan

### Sales

Sales should not promise the exact custom logic this quarter.

Sales can say:

> We understand the approval control problem and are actively evaluating a reusable solution for regulated customers. We are not committing to customer-specific workflow logic until we have validated the broader pattern.

### CS

CS should identify existing customers with similar approval or compliance workflow problems.

### Engineering

Engineering should explore the smallest reusable approval control pattern and identify technical risks.

### Leadership

Leadership should understand the trade-off:

> Short-term revenue opportunity versus long-term product complexity.

### Customer

The customer should hear that the problem is taken seriously, but the company will not commit to a one-off implementation before understanding the broader product direction.

---

## Notes

This decision does not mean approval control is unimportant.

It means the problem deserves better thinking than a rushed custom feature.
