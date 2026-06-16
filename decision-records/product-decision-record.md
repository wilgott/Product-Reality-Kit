# Product Decision Record

A shipped product shows what changed.

The reasoning behind a trade-off is easier to lose.

A Product Decision Record helps you write down the decision, the customer problem, the evidence, the trade-off, and when the decision should be reviewed again.

It is inspired by Architecture Decision Records, adapted for product decisions.

Use this in Confluence, Notion, Linear, Jira, GitHub, Google Docs, or wherever your team works.

The tool does not matter.

The decision does.

---

# PDR-000: [Decision title]

## Status

Proposed / Accepted / Rejected / Reversed / Superseded

## Date

YYYY-MM-DD

## Owner

Name / team

## Decision

Write the decision in one or two clear sentences.

Example:

> We will not build custom approval logic for one enterprise customer right now. We will run discovery on reusable approval patterns for regulated customers and review the decision in 30 days.

---

## Customer problem

What customer problem are we solving?

Do not start with the requested feature.

Start with the problem.

Bad:

> The customer needs custom approval rules.

Better:

> Compliance teams need more control over who can approve onboarding flows before they go live.

---

## Context

What triggered this decision?

Examples:

- Sales request
- Enterprise escalation
- Churn signal
- Pricing issue
- GTM problem
- Leadership ask
- Customer feedback
- Technical constraint
- Regulatory or compliance need

Write the context in plain language.

---

## What we know

List the evidence.

Include what is relevant:

- Customer input
- Usage data
- Revenue impact
- Sales feedback
- CS feedback
- Support tickets
- Technical constraints
- Market context
- Competitor context
- Risk or compliance context

Keep it factual.

Do not pretend weak evidence is strong evidence.

---

## What we do not know yet

Be honest.

Good product judgment includes knowing what is still unclear.

Examples:

- We do not know if this problem exists outside one customer.
- We do not know if the requested solution is the right solution.
- We do not know if customers would pay for this.
- We do not know the full maintenance cost.
- We do not know if this improves activation, retention, or expansion.

---

## Options considered

### Option A: [Name]

Description:

Pros:

-

Cons:

-

### Option B: [Name]

Description:

Pros:

-

Cons:

-

### Option C: [Name]

Description:

Pros:

-

Cons:

-

---

## Trade-off

What are we accepting by choosing this?

A meaningful decision has a cost.

Examples:

- We accept that we may lose this deal.
- We accept slower delivery of another roadmap item.
- We accept more product complexity.
- We accept that Sales needs a workaround for now.
- We accept that we need more evidence before committing.

---

## What we are saying no to

Be explicit.

A yes is clearer when we know what it replaces.

Examples:

- We are saying no to custom work for one customer.
- We are saying no to adding another setting before we understand the pattern.
- We are saying no to changing pricing without evidence.
- We are saying no to hiding a GTM problem inside the product roadmap.

---

## Reversal criteria

What would make us change this decision?

Examples:

- Three more ICP customers ask for the same problem.
- The request appears in more than 20% of enterprise deals.
- Churn analysis shows this is a top reason customers leave.
- Discovery proves this is a reusable pattern.
- Engineering finds a simpler way to solve it.
- The revenue opportunity becomes large enough to justify the trade-off.

---

## Review date

When should we review this decision again?

Example:

> Review in 30 days after five customer interviews and review of lost deal notes.

---

## Communication plan

Who needs to understand this decision?

Include the right people:

- Sales
- CS
- Engineering
- Support
- Marketing
- Leadership
- Customer-facing teams
- Customers or prospects

Write how the decision should be explained.

Example:

> Sales should explain that we are not committing to a custom feature now, but we are evaluating a more reusable approval capability for regulated customers.

---

## Notes

Add any extra context here.

Keep it short.
