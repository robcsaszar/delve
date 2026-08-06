# AGENTS.md

## Mission

This repo publishes a single skill, `delve`, copied in from a source repo (Orakl) where it is used and refined, then published here for anyone to install. There is no build, no tests, no runtime of its own. The deliverable is `skills/delve/`.

## Judgment boundary

Don't let the skill's content drift toward being useful only in one narrow context. It exists to make any agent a more careful, confidence-flagging research collaborator on any topic; a change that only makes sense for one specific domain or project doesn't belong here. If you're updating it, re-run a grep for source-repo-specific leakage (`grep -rni "orakl"` under `skills/`) before publishing.
