# Skill index — global routing

Read only the skills relevant to the task after reading PROJECT_INSTRUCTIONS.md and AGENTS.md.

| Work type | Skill file | Target repo evidence |
|---|---|---|
| iOS jailbreak, CarPlay, DEB, IPA, Sileo | DEB_IPA_SKILL.md | Existing handoff, packaging files, workflows, build logs, artifacts |
| Python crawler, resolver, metadata, catalogs | PYTHON_CRAWLER_SKILL.md | Existing handoff, working scripts, test commands, datasets, logs |
| Any coding or GitHub/Render work | AGENTS.md | Exact repo, branch, commit, source, CI/CD status |
| Continuation across chats | HANDOFF_TEMPLATE.md (reference only) | Existing handoff first; do not create duplicates |

Routing rules:
1. Identify the requested project/repo from current conversation and accessible context; never choose another project by similarity.
2. Fetch the global instructions, then the relevant skill(s).
3. Fetch the project's actual history, handoff, related ZIP/artifact, code and workflow.
4. Execute and verify. Save all necessary deliverables in the correct target repo.
5. If GitHub access is missing, explain the limitation; do not claim a ZIP or repository was read.


## ZIP skill discovery priority
Search **Gpt-training-** by feature first for a matching skill ZIP (including nested paths). If present, inspect its contents or verified extracted equivalent. The Markdown files above are fallback/entry points and do not imply a ZIP exists. Do not substitute ZIP files from the target work repository for centrally stored skill packages.

Keep deliverables and handoff in the target project's own repo. If no target repo exists, ask the user to create one or authorize use of a shared handoff repo; do not choose silently.
