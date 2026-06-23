# Diagnostics

Start here when the situation is messy and you are not sure which file to use.

Pick the situation that sounds closest. The diagnostic helps you slow down, find the real problem, and decide what evidence to check before the roadmap reacts.

## How to use this

1. Choose the closest situation below.
2. Read the diagnostic.
3. Use the linked prompt if you want AI help turning context into clearer options.
4. Write the decision down in a Product Decision Record.

Do not try to make the diagnostic decide for you.

Use it to make the trade-off clear.

## Diagnostic chooser

| Messy situation | Use this diagnostic | Next artifact |
| --- | --- | --- |
| Sales says a feature is needed to close a deal. | [When Sales Drives the Roadmap](when-sales-drives-the-roadmap.md) | [Diagnose a Sales Request](../prompts/diagnose-sales-request.md), then [Product Decision Record](../decision-records/product-decision-record.md) |
| A large customer wants an exception or special flow. | [When Enterprise Wants an Exception](when-enterprise-wants-an-exception.md) | [Challenge an Enterprise Request](../prompts/challenge-enterprise-request.md), then [Product Decision Record](../decision-records/product-decision-record.md) |
| Pricing, packaging, tiers, limits, or add-ons are hard to explain. | [When Pricing Is Confusing](when-pricing-is-confusing.md) | [Pressure-Test Pricing and Packaging](../prompts/pressure-test-pricing-packaging.md), then [Product Decision Record](../decision-records/product-decision-record.md) |
| A launch shipped, but the market, Sales, CS, or customers did not respond. | [When the Launch Does Not Land](when-the-launch-does-not-land.md) | [Diagnose Launch](../prompts/diagnose-launch.md), then [Product Decision Record](../decision-records/product-decision-record.md) |
| Customers buy or start onboarding, but do not reach first value. | [When Activation Is Weak](when-activation-is-weak.md) | [Diagnose Activation](../prompts/diagnose-activation.md), then [Lite Product Decision Record](../decision-records/product-decision-record-lite.md) |
| A shipped feature exists, but the right customers are not using it. | [When Feature Adoption Is Low](when-feature-adoption-is-low.md) | [Diagnose Feature Adoption](../prompts/diagnose-feature-adoption.md), then [Lite Product Decision Record](../decision-records/product-decision-record-lite.md) |
| Customers are leaving and the team is blaming the product too quickly. | [When Customers Churn](when-customers-churn.md) | [Diagnose Churn](../prompts/diagnose-churn.md), then [Product Decision Record](../decision-records/product-decision-record.md) |
| Someone says "just make it configurable" to avoid choosing a default. | [When "Just Make It Configurable" Sounds Easy](when-just-make-it-configurable-sounds-easy.md) | [Diagnose Configurability](../prompts/diagnose-configurability.md), then [Product Decision Record](../decision-records/product-decision-record.md) |

## If two diagnostics fit

That is normal.

Start with the pressure source, then check the second file before writing the decision.

Common combinations:

- Sales pressure plus enterprise exception: use [When Sales Drives the Roadmap](when-sales-drives-the-roadmap.md) first, then [When Enterprise Wants an Exception](when-enterprise-wants-an-exception.md).
- Enterprise exception plus configurability: use [When Enterprise Wants an Exception](when-enterprise-wants-an-exception.md) first, then [When "Just Make It Configurable" Sounds Easy](when-just-make-it-configurable-sounds-easy.md).
- Weak launch plus low adoption: use [When the Launch Does Not Land](when-the-launch-does-not-land.md) first if the issue is GTM, or [When Feature Adoption Is Low](when-feature-adoption-is-low.md) first if the issue is usage inside the product.
- Churn plus weak activation: use [When Customers Churn](when-customers-churn.md) first, then [When Activation Is Weak](when-activation-is-weak.md) if customers never reached first value.

## Example flow

If you want to see the whole path, use one of the fictional examples.

Sales pressure:

1. Start with the messy request: [Sales Request](../examples/verifyflow/sales-request.md)
2. Read the diagnostic output: [Diagnostic Output](../examples/verifyflow/diagnostic-output.md)
3. See the written decision: [Example Product Decision Record](../examples/verifyflow/product-decision-record.md)

Pricing confusion:

1. Start with the messy situation: [Pricing Confusion](../examples/pricepath/pricing-confusion.md)
2. Read the diagnostic output: [Diagnostic Output](../examples/pricepath/diagnostic-output.md)
3. See the written decision: [Example Product Decision Record](../examples/pricepath/product-decision-record.md)
