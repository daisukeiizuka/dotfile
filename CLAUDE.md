# Coding & Workflow Preferences

## Coding Principles
- Keep changes minimal — only touch what's necessary, don't modify unrelated files
- Fix root causes, not symptoms — no temporary workarounds
- Ask yourself: "Would a senior engineer approve this PR?"

## Workflow
- For non-trivial tasks (3+ steps or architectural decisions), present a plan and get approval before implementing
- If something goes wrong mid-task, stop immediately and re-plan — don't push through
- When given a bug report or error log, investigate logs, tests, and code on your own — don't ask for hand-holding
- Before declaring a task complete, prove correctness by running tests and verifying behavior
- Delegate research, exploration, and parallel analysis to subagents to keep the main context clean (one task per subagent)

