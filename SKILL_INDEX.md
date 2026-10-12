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
