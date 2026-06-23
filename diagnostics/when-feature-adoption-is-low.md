# When Feature Adoption Is Low

Low adoption does not always mean the feature is bad.
Sometimes customers simply do not know it exists.
Use this diagnostic when a feature has shipped, but customers are not using it.

This is different from launch. A launch can create awareness, but adoption means the feature becomes useful in the customer's real workflow.

Use this to diagnose why a shipped feature is not being used before deciding whether to improve it, reposition it, move it, hide it, or leave it alone.

---

## When to use this

Use this when a feature is available, but usage is lower than expected.

Common signals:

- Customers do not use a feature after it ships.
- Usage is limited to a few customers or one segment.
- Customers ask for the feature, but do not use it once it exists.
- Sales and CS are not sure when or how to mention it.
- Customers do not know the feature exists.
- Customers know it exists, but do not understand why it matters.
- Customers cannot find it in the product.
- The feature requires setup before value appears.
- Usage is low, but the team has not agreed whether low usage is actually a problem.

---

## The uncomfortable truth

Low adoption is often a weak signal until you know who should have adopted the feature and what would count as healthy use.

The feature may be bad, but it may also be invisible, poorly explained, aimed at the wrong customer, placed in the wrong package, disconnected from the customer's workflow, or blocked by setup work that happens before value appears. Sales may not know when to mention it. CS may not know how to introduce it during onboarding, account reviews, or customer meetings.

Before judging quality, check awareness. Before adding more capability, check whether the current feature solves a frequent enough problem for the right customer in a workflow where they naturally need it.

---

## First questions

Start here:

1. Do customers know the feature exists?
2. Did we communicate it clearly?
3. Did Sales mention it?
4. Did CS mention it during onboarding or customer meetings?
5. Is the feature easy to find?
6. Is the value clear?
7. Does it solve a real customer problem?
8. Is it part of the customer's real workflow?
9. Did the customer ask for the feature, or did we understand the real problem?
10. Is the feature in the right package or plan?
11. Is setup required before the feature becomes useful?
12. Is low adoption actually a problem for this feature?

---

## Red flags

Be careful when:

- The team assumes the feature failed without checking awareness.
- Customers asked for the feature, but do not use it.
- The feature is hidden or hard to discover.
- Sales does not know when to mention it.
- CS does not know how to introduce it.
- The feature is not connected to a clear workflow.
- The value depends on incomplete setup.
- Adoption is measured without knowing the target user.
- The team wants more features before understanding why the current one is not used.
- The feature is available only in a plan where the best-fit customers cannot access it.
- Usage is low, but nobody has defined what healthy adoption should look like.

---

## Common false diagnoses

### "The feature failed."

Maybe.

But low usage alone does not prove the feature is bad.

Check first:

- Whether the target customers know it exists.
- Whether they understand the value.
- Whether they can find it inside the product.
- Whether Sales and CS know how to introduce it.
- Whether it fits a real workflow.

### "Customers asked for it, so they should use it."

Maybe.

But a request does not always describe the real problem, the right solution, or the right moment in the workflow.

It may mean:

- The customer wanted an outcome, not this exact feature.
- The buyer asked, but the daily user does not need it.
- The request came from one customer or segment.
- The feature requires setup the customer did not expect.
- The customer solved the problem another way before the feature became available.

### "We need to improve the UI."

Maybe.

But UI polish will not fix a feature customers do not know about, do not understand, cannot access, or do not need in their workflow.

Before redesigning, check:

- Whether customers can discover the feature.
- Whether the feature explains its value clearly.
- Whether the right users have access to it.
- Whether setup blocks value.
- Whether the feature solves a frequent enough problem.

---

## What to check

Check adoption in context before naming the failure:

- Feature usage by segment.
- Feature usage by customer size.
- Feature usage by plan or package.
- Whether target customers use it.
- Whether usage comes from buyers, admins, or day-to-day users.
- In-product discovery and whether customers can find the feature.
- Sales communication and whether Sales knows when to mention it.
- CS communication and whether CS knows how to introduce it.
- Launch communication and whether customers were told clearly.
- Onboarding material and whether the feature appears at the right moment.
- Customer interviews with users who adopted it and users who did not.
- Support questions that show confusion, missing context, or setup blockers.
- Setup requirements before the feature becomes useful.
- Whether the feature solves a frequent customer problem.
- Whether the feature is used once, rarely, or repeatedly.
- Whether low adoption matters for the feature's purpose.

---

## Decision options

Possible decisions:

- Improve awareness.
- Improve in-product discovery.
- Improve Sales and CS enablement.
- Improve onboarding.
- Reposition the feature around a clearer customer outcome.
- Move the feature to a different package or plan.
- Simplify setup.
- Improve UX.
- Connect the feature to a stronger workflow.
- Run customer interviews before changing the product.
- Leave it as a niche feature if low adoption is acceptable.
- Hide it if it creates more confusion than value.
- Deprecate it if it creates more noise than value and does not support the product strategy.

---

## Product Decision Record output

After the diagnostic, write a Product Decision Record.

Recommended template:

- [Standard PDR](../decision-records/product-decision-record.md)

Make sure the decision record answers:

- Who was this feature built for?
- Is low adoption actually a problem?
- Do customers know the feature exists?
- Is the value clear?
- Is the feature easy to use in the customer's workflow?
- What action are we taking?
- What are we not doing yet?
- When will we review adoption again?

---

## Optional AI prompt

Use this prompt if you want help diagnosing low feature adoption:

- [Diagnose feature adoption](../prompts/diagnose-feature-adoption.md)

---

## Simple rule

Do not judge feature quality before checking awareness, access, value clarity, setup, and workflow fit.

Low adoption is a diagnosis prompt. It is not automatically a failure verdict.
