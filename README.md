# Sharan Kumar

I build workflows that turn AI product ideas into specialist-assisted software builds.

My current system, **claude-os**, brings together slash-command intake, a planning council, specialist agents, execution, and independent review. In the full configured system, `/claude-os <idea>` helps settle what to build; `/autopilot` drives the approved plan with the relevant specialists; `/enhance` proposes improvements to existing projects.

## Start here: claude-os

[**claude-os-public**](https://github.com/sharanlabs/claude-os-public) is my current public toolkit. It publishes the runnable evaluation toolkit and selected review skills from the larger system. The full slash-command engine and specialist roster are not bundled yet. [See the product-building workflow and its current availability](https://github.com/sharanlabs/claude-os-public/blob/main/docs/SPECIALIST-WORKFLOW.md).

| Try | What you get |
|---|---|
| [Run the walkthrough](https://github.com/sharanlabs/claude-os-public/blob/main/docs/WALKTHROUGH.md) | Python-only examples with passing, failing, and incomplete results. No model call or API key needed. |
| [Inspect the evaluator](https://github.com/sharanlabs/claude-os-public/blob/main/bin/eval-runner.py) | Deterministic checks and structured judge-verdict validation for supplied outputs. |
| [Browse the review skills](https://github.com/sharanlabs/claude-os-public/tree/main/skills) | A small, attributed collection of planning and Codex critique workflows, with runtime limits documented. |
| [Read the evaluation limits](https://github.com/sharanlabs/claude-os-public/blob/main/docs/EVALUATION.md) | What synthetic examples establish, what they do not, and how I plan to evaluate real reviews. |

The toolkit is early-stage. The examples demonstrate software behavior; they do not establish model accuracy or external adoption. A live Codex review integration and independent maintainer pilots are next steps.

[Code and setup](https://github.com/sharanlabs/claude-os-public) · [Automated checks](https://github.com/sharanlabs/claude-os-public/actions/workflows/verify.yml) · [Release history](https://github.com/sharanlabs/claude-os-public/releases)

## Help make it useful

A reproducible scoring error, an overly permissive test, or a setup step that fails on your machine is a valuable contribution. Start with the [contribution guide](https://github.com/sharanlabs/claude-os-public/blob/main/CONTRIBUTING.md) or the [maintainer pilot protocol](https://github.com/sharanlabs/claude-os-public/blob/main/docs/PILOT.md). Please use public, synthetic, or explicitly authorized examples.

## Related work

[claude-os-open](https://github.com/sharanlabs/claude-os-open) is an earlier architecture snapshot of the personal system. The runnable public toolkit lives in **claude-os-public**.

I also explore AI-assisted procurement and supply-chain workflows in [procureguard-ai](https://github.com/sharanlabs/procureguard-ai) and [supply-chain-ai-resilix](https://github.com/sharanlabs/supply-chain-ai-resilix). Each repository documents its own scope and status.

I publish limitations alongside implementation. If you try something, a small reproducible report is more useful than a broad endorsement.
