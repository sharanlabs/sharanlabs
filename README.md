# Sharan Kumar

I build tools for reviewing and evaluating AI-assisted software development.

My focus is the evidence around an agent's work: explicit requirements, reproducible checks, separate review, and honest limits. I want a maintainer to be able to inspect a result and understand what was actually verified.

## Start here: claude-os

[**claude-os-public**](https://github.com/sharanlabs/claude-os-public) is my current public toolkit. It grew out of a larger personal development system and now provides a focused subset you can run without that environment.

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
