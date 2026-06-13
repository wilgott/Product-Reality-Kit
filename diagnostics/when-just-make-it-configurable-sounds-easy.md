# When "Just Make It Configurable" Sounds Easy

"Just make it configurable" sounds simple.

Sometimes it is the right move.

Sometimes it is how a B2B SaaS product slowly becomes hard to understand, hard to sell, hard to support, and hard to maintain.

Use this diagnostic when the team wants to add settings, rules, workflow options, permissions, toggles, templates, or customer-specific flexibility.

---

## When to use this

Use this when you hear things like:

- "Can we just make it configurable?"
- "Every customer wants it slightly different."
- "We can solve this with a setting."
- "Let the admin decide."
- "This should be a workflow rule."
- "This only needs to work for one customer."
- "No-code will solve it."
- "We do not need to choose. Let the customer choose."

---

## The uncomfortable truth

Configurability is powerful.

But configurability is not free.

Every meaningful option creates work for someone:

- Product needs to explain it.
- Engineering needs to build and maintain it.
- QA needs to test more combinations.
- Sales needs to sell it.
- CS needs to onboard it.
- Support needs to troubleshoot it.
- Customers need to understand it.

A setting can move complexity from your team to the customer.

That is not always a win.

---

## First questions

Start here:

1. What customer problem are we solving?
2. Is the customer asking for flexibility, or do they just need a better default?
3. Is this a common pattern or a one-off preference?
4. Who will configure it: admin, user, CS, implementation, or Product?
5. Will customers know what to choose?
6. What happens if they configure it wrong?
7. Does this make onboarding easier or harder?
8. Does this make the product easier to sell or harder to explain?
9. Does this increase customer value or hide lack of product judgement?
10. Is this a setting, a workflow pattern, a template, a permission, an add-on, or a service?
11. How many combinations do we need to test and support?
12. What is the simplest useful version?

---

## Red flags

Be careful when:

- Configurability is used to avoid making a product decision.
- The setting only helps one customer.
- Nobody knows who will own configuration setup.
- Sales cannot explain the option.
- CS says onboarding will become harder.
- Support cannot easily reproduce customer issues.
- The default experience becomes unclear.
- The product starts to need expert setup for normal use.
- Every customer needs a different setup before they see value.
- The team says "no-code" but the customer still needs deep domain knowledge.

---

## Common false diagnoses

### "More flexibility means more value."

Not always.

More flexibility can create more confusion.

In many B2B SaaS contexts, customers are trying to get an outcome, not manage more choices.

### "No-code makes it easy."

No-code can reduce engineering work.

It does not remove product complexity, customer confusion, testing, support, or ownership.

### "A setting is cheaper than a product decision."

Sometimes.

But a setting can become a permanent tax on the product.

You may pay for it in onboarding, support, documentation, QA, and customer confusion.

---

## What to check

Before deciding, check:

- Number of customers asking for this
- Whether the problem is recurring
- Whether the same default would solve most cases
- Admin skill level
- Setup time
- Onboarding impact
- Support impact
- QA complexity
- Documentation needs
- Sales enablement needs
- CS ownership
- Whether this belongs in product, template, service, or implementation
- Whether it should be part of a paid advanced package

---

## Decision options

Possible decisions:

- Add a simple default
- Add one clear setting
- Add workflow templates instead of full configurability
- Build reusable rules
- Make it an advanced feature
- Make it a paid add-on
- Handle it through implementation or services
- Improve the existing experience without adding options
- Run discovery first
- Say no

---

## Product Decision Record output

After the diagnostic, write a Product Decision Record.

Recommended template:

- [Standard PDR](../decision-records/product-decision-record.md)

Make sure the decision record includes:

- What customer problem needs flexibility
- Who will configure it
- What complexity it adds
- What default experience should be
- What trade-off you are accepting
- What you are saying no to
- When to review if the configuration is creating more problems than value

---

## Optional AI prompt

Use this prompt if you want help finding weak logic:

- [Review a product decision](../prompts/review-product-decision.md)

---

## Simple rule

Do not add flexibility before you understand the problem.

A good default is often better than another setting.
