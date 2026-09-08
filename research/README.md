# Consent research

**Status: proposed; no completed evaluation or funding award claimed.**

The research asks how reliably AI-generated profiles respect explicit consent boundaries. It will compare natural-language instructions, equivalent structured permissions, and a restricted-input condition that supplies only authorized information. The last condition evaluates an application-level control, not prompt wording alone.

## Planned evaluation

- 40 development scenarios, separate from a frozen set of up to 200 manually reviewed fictional evaluation scenarios.
- Two models, three approaches, and five repetitions per evaluation scenario.
- Primary outcome: responses containing unauthorized disclosure.
- Secondary outcomes: permitted-task completion, unsupported claims, inference labeling, and unnecessary refusals.
- Predefined rubrics, deterministic checks, and manual audits; automated judgments are not ground truth.
- Scenario-level comparisons and uncertainty estimates that account for repeated outputs.

The target is a four-week core evaluation after receipt of credits. Calibrate cost and manual-review effort before freezing scope. If needed, reduce volume before execution rather than compromise scoring quality. A human comprehension study is optional and depends on recruitment and applicable ethics requirements.

## Intended public outputs

Publish the protocol, reviewed synthetic scenarios, research-specific code and prompts, and a report including negative findings and limitations. Do not present synthetic model results as proof of human understanding, comprehensive privacy, or production security.

Keep real identity data, participant records, application-account details, and proprietary implementation outside this repository. Research materials should permit reproduction independently of the private product. See the [roadmap](../ROADMAP.md).
