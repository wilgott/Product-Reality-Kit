# When "Just Make It Configurable" Sounds Easy

"Just make it configurable" sounds simple.

Sometimes it is the right move.

Sometimes it is how a B2B SaaS product slowly becomes hard to understand, hard to sell, hard to support, and hard to maintain.

Use this diagnostic before adding another setting, rule, toggle, permission, workflow option, or customer-specific configuration.

Use it especially for B2B SaaS, no-code products, workflow products, orchestration platforms, enterprise products, admin-heavy products, and compliance-heavy products. These are the products where configuration can create real power, and where unclear configuration can turn the product into custom work with a UI.

---

## When to use this

Use this when the team says:

- "Can we just make it configurable?"
- "Every customer does this differently."
- "We can solve this with a setting."
- "Let the admin decide."
- "This should be a workflow rule."
- "That customer needs their own option."
- "No-code will solve it."
- "We do not need to choose. Let the customer choose."

Also use it when the product already has a growing surface of permissions, templates, automations, exception rules, admin controls, compliance settings, workflow branches, or customer-specific defaults.

---

## The uncomfortable truth

Configurability is powerful.

But configurability is not free.

Good configuration solves a real repeated problem. It lets different customers express valid differences in workflow, risk, scale, policy, geography, compliance, org structure, or operating model.

Bad configuration hides unclear product thinking. It avoids deciding what should happen by default, pushes judgment onto customers, and makes every future customer, seller, implementer, support agent, QA pass, help doc, and engineer pay rent on the choice.

A setting does not remove complexity.

It moves complexity somewhere.

Sometimes that place is exactly where it belongs: with a capable admin who needs control.

Sometimes it lands on a customer who does not know the consequences, a CS team that has to explain it, a Support team that cannot reproduce it, a QA suite that explodes in combinations, or an Engineering team that now maintains one product with hundreds of invisible variants.

That is how a product becomes less like software and more like professional services wrapped in UI.

---

## First questions

Start here:

1. What customer problem are we solving?
2. Is the customer asking for flexibility, or do they need a better default?
3. Is this a common pattern or one customer's preference?
4. Who will configure it: customer admin, end user, CS, implementation, Support, partner, or Product?
5. Will the customer know what to choose?
6. What happens if it is configured wrong?
7. Does onboarding become easier or harder?
8. Does Sales become easier or harder?
9. Does CS or Support become easier or harder?
10. Does this increase customer value, or hide a lack of product judgement?
11. How many combinations will we need to test?
12. What is the simplest useful version?
13. Should this be a default, template, setting, rule, permission, paid add-on, or service?

If the team cannot answer these plainly, the next step is not configuration. The next step is better product thinking.

---

## Red flags

Be careful when:

- Configurability avoids a product decision.
- The setting only helps one customer.
- Nobody owns setup.
- Sales cannot explain the option.
- CS says onboarding will become harder.
- Support cannot reproduce issues.
- QA says there are too many combinations.
- The default is unclear.
- The product needs expert setup before customers see value.
- Every customer needs a different setup before the product works.
- "No-code" is used to avoid thinking about product logic.
- The option creates hidden behavior that ordinary users cannot understand.
- Compliance, permissions, or workflow rules can conflict without a clear resolution model.
- The customer asks for control but cannot name the decision they need to make.
- Internal teams say "we will document it" before anyone can explain it simply.

---

## Common false diagnoses

### "More flexibility means more value."

Not automatically.

Flexibility has value when it maps to real differences customers understand and care about. More choices can also mean more setup, more hesitation, more broken workflows, more inconsistent outcomes, and more reasons for customers to blame themselves for a product that should have guided them.

In B2B SaaS, most customers are buying an outcome. They are not buying the privilege of becoming product designers.

### "No-code makes it easy."

No-code can make some changes faster to create.

It does not make product logic obvious. It does not remove the need for defaults, guardrails, naming, testing, documentation, onboarding, governance, or ownership. A no-code workflow with unclear logic is still unclear logic.

When "no-code" means "we do not have to decide how this should work," the team is using tooling as a substitute for product judgement.

### "A setting is cheaper than a product decision."

Only in the first sprint.

After that, the setting needs UI, permissions, analytics, documentation, training, QA coverage, support paths, migration behavior, API behavior, reporting behavior, and an owner when customers use it badly.

The product decision still exists. The team has only delayed it and made customers participate in the confusion.

### "Let the customer decide."

Sometimes the customer should decide.

Enterprise admins should control real policy, risk, workflow, access, thresholds, exceptions, and governance. But asking customers to decide is not neutral when they do not understand the trade-off, cannot predict the outcome, or have no good reason to prefer one option over another.

"Let the customer decide" is strong when the decision belongs to the customer's operating model.

It is weak when the team is avoiding its own product decision.

---

## What to check

Before deciding, check:

- Number of customers asking for this
- Whether the problem is recurring
- Whether better default behavior solves most cases
- Whether there are valid workflow differences across customers
- Admin skill level
- Who will own setup and ongoing changes
- Setup time
- Onboarding impact
- Sales enablement impact
- CS impact
- Support impact
- QA complexity
- Number of test combinations
- Documentation needs
- Maintenance cost
- Whether the configuration creates new failure states
- Whether the product can explain the option in one clear sentence
- Whether customers can recover from a wrong configuration
- Whether the option belongs in the product, a template, a service, or implementation
- Whether this should be a paid advanced package

Also check the current default. If the default is weak, unclear, or too generic, another option may only preserve a bad default.

---

## Decision options

Possible decisions:

- Improve the default
- Add one clear setting
- Add workflow templates instead of full configurability
- Build reusable rules
- Make it an advanced feature
- Make it a paid add-on
- Handle it through implementation or services
- Improve the current experience without adding options
- Run discovery first
- Say no

Choose the smallest decision that solves the repeated problem without making the whole product harder to understand.

---

## Product Decision Record output

After the diagnostic, write a Product Decision Record.

Recommended template:

- [Standard PDR](../decision-records/product-decision-record.md)

Make sure the decision record answers:

- What customer problem needs flexibility?
- What recurring pattern proves this is not only one preference?
- Who configures it?
- What complexity is added for customers, Sales, CS, Support, Engineering, QA, documentation, and maintenance?
- What is the default experience?
- What trade-off are we accepting?
- What are we saying no to?
- When will we review whether this configuration creates more problems than value?

If the PDR cannot answer these, do not ship the option yet.

---

## Optional AI prompt

Use this prompt if you want help finding weak logic:

- [Review a product decision](../prompts/review-product-decision.md)

---

## Simple rule

Configurability is powerful when it solves a real repeated problem.

It is dangerous when it hides unclear product thinking.

Do not add flexibility before you understand the problem.

A good default is often better than another setting.
