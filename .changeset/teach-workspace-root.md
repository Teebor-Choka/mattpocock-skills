---
"mattpocock-skills": patch
---

`teach` now writes its workspace (`MISSION.md`, `lessons/`, `reference/`, `learning-records/`, `assets/` and the rest) to the directory you ran `/teach` in, not into the skill's own install folder. `SKILL.md` used `./` both for its bundled format docs and for workspace paths, so agents sometimes wrote the course into `~/.claude/skills`. It now names the workspace root explicitly. Thanks @huahsinsun for reporting it (#377).
