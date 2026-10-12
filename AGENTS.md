# Agent workflow

## Start
- Locate existing handoff, read active checkpoint and related decisions.
- Confirm repo, branch, commit, environment, output artifact and delivery target.
- Inspect source and previous successful attempts before changing code.

## Research and implementation
- Use official docs and comparable repositories/Issues for unfamiliar problems.
- Form testable hypotheses, make the smallest safe change, run tests and inspect diffs.
- Do not silently alter unrelated features or repeat failed fixes without new evidence.

## Persistence
- Commit relevant work products to the correct repo when authorized; preserve existing notes.
- For binary upload limitations, preserve losslessly with checksum and reconstruction instructions.
- Verify resulting GitHub commit and files; never store secrets.

## Handoff
- Update only on meaningful state changes; retain evidence and exact next action.
- Report outcomes rather than plans.
