# GPT Coding System

A portable instruction and handoff package for ChatGPT Projects and GitHub repositories.

- PROJECT_INSTRUCTIONS.md: copy its content into ChatGPT Project Instructions (after reconciling with existing instructions).
- AGENTS.md: general coding-agent workflow.
- DEB_IPA_SKILL.md: DEB, IPA, Sileo and build verification.
- PYTHON_CRAWLER_SKILL.md: crawler and resolver development.
- HANDOFF_TEMPLATE.md: example checkpoint schema; do not replace an existing handoff.

This package does not install itself into ChatGPT Projects. It does not modify any existing repository or notes unless explicitly uploaded and integrated.


## Global use — no ChatGPT ZIP upload required
For every task, fetch this repository's AGENTS.md, PROJECT_INSTRUCTIONS.md and the matching skill from SKILL_INDEX.md through the GitHub connection. Then fetch the target project's existing handoff, checkpoint, relevant source files and artifacts. Commit project results to the target repo, not here. ZIPs can be read when tools support them; otherwise use verified extracted files or lossless text representations. Do not claim to have read inaccessible ZIP contents.

ChatGPT Projects still need a short bootstrap instruction pointing to this GitHub repository; simply storing files here does not cause automatic retrieval.
