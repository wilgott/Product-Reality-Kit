# Product Reality Kit - June 23, 2026 Update

**Release Date:** June 23, 2026

## Highlights

### Easier start for messy product situations

Product Reality Kit now has a diagnostic chooser that helps you quickly pick the right file for the situation in front of you. Start with the pressure you are seeing, then move directly to the matching diagnostic, AI prompt, and Product Decision Record template.

### More complete AI prompt coverage

Five new AI prompts help diagnose weak activation, churn, low feature adoption, weak launches, and configurability pressure. Each prompt asks the AI to separate evidence from assumptions, identify false diagnoses, surface stakeholder questions, compare decision options, and draft a plain-English Product Decision Record.

### New pricing confusion example

The new PricePath example shows how to handle pricing and packaging confusion without jumping straight to a new tier or lower price. It walks through the messy context, diagnostic output, and final Product Decision Record.

---

## New

- **Diagnostic chooser:** Use [Diagnostics](diagnostics/README.md) to match a messy situation to the right diagnostic, prompt, and decision record.
- **Activation prompt:** Use [Diagnose Activation](prompts/diagnose-activation.md) when customers do not reach first value.
- **Churn prompt:** Use [Diagnose Churn](prompts/diagnose-churn.md) when the team is blaming churn on product too quickly.
- **Feature adoption prompt:** Use [Diagnose Feature Adoption](prompts/diagnose-feature-adoption.md) when a shipped feature exists but the right customers are not using it.
- **Launch prompt:** Use [Diagnose Launch](prompts/diagnose-launch.md) when a launch ships but does not land.
- **Configurability prompt:** Use [Diagnose Configurability](prompts/diagnose-configurability.md) before adding another setting, rule, toggle, or customer-specific option.
- **PricePath example:** Use the [PricePath pricing confusion example](examples/pricepath/pricing-confusion.md) to see a full pricing diagnostic flow.

## Improvements

- **Clearer first-use path:** The [README](README.md) and [Usage guide](USAGE.md) now point new users to the diagnostic chooser and worked examples.
- **More relevant diagnostic prompts:** Diagnostics for activation, churn, feature adoption, launch, and configurability now link to dedicated prompts instead of generic review prompts.
- **Cleaner local development:** `.worktrees/` is ignored so local worktree folders do not get tracked by Git.

## Known Issues

- Public documentation links have been checked and pass.
- Some older `_private/` planning files still contain stale internal links. They are not part of the public toolkit.

## Feedback

If something feels unclear or too theoretical, open an issue or suggest a simpler version. This kit should stay practical, direct, and useful in real B2B SaaS product work.
