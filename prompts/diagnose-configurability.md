# AI Prompt: Diagnose Configurability

Use this before adding another setting, rule, toggle, permission, workflow option, or customer-specific configuration.

The goal is not to block flexibility.

The goal is to decide whether configurability solves a real repeated problem or hides unclear product thinking.

---

## Prompt

Copy and paste this into your AI tool.

```text
You are helping me diagnose a B2B SaaS configurability request.

Do not assume flexibility is always better.
Do not assume a setting is cheap.
Do not assume the customer should decide.
Do not invent evidence.

Separate known facts from unknowns. If this is only one customer's preference, say so.

Help me understand whether this should be a better default, template, setting, rule, permission, advanced feature, paid add-on, implementation work, service work, or no.

Context:
- Company type:
- Product:
- Customer segment:
- Request:
- Customer problem behind the request:
- Who asked:
- Number of similar requests:
- Current default behavior:
- Current workaround:
- Who would configure it:
- Who would use it:
- What happens if it is configured wrong:
- Sales impact:
- CS or onboarding impact:
- Support impact:
- Engineering impact:
- QA and documentation impact:
- Compliance or governance context:
- Data we have:
- Data we do not have:

Please return:

1. The likely customer problem behind the configurability request
2. What we know from evidence
3. What is still unknown
4. Whether this is a repeated pattern or one preference
5. Common false diagnoses and red flags
6. Whether the problem is better solved by a default, template, setting, rule, permission, paid add-on, service, or no
7. Questions to ask customers
8. Questions to ask Sales, CS, Support, Engineering, QA, and documentation owners
9. Decision options and trade-offs
10. Complexity added for customers and internal teams
11. Evidence gaps to close before adding configuration
12. What not to make configurable yet
13. A draft Product Decision Record in plain English

Use clear language.
Be direct.
Avoid consultant-speak.
```

---

## Good follow-up questions

```text
Where are we using configurability to avoid choosing a better default?
```

```text
What complexity does this setting move to customers, CS, Support, QA, and Engineering?
```

```text
What is the smallest version that solves the repeated problem without creating a maze of options?
```
