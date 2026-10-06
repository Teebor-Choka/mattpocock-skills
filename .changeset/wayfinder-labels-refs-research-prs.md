---
"mattpocock-skills": patch
---

`wayfinder` tightens three things it publishes to your tracker. Maps and tickets carry only their `wayfinder:` label, never a triage-state label like `ready-for-agent`, since they are questions rather than work to implement (#518). Cross-references between tickets are written only once the issues exist, using their real ids, so a placeholder `#1` never auto-links to an unrelated old issue (#507). And a research subagent pushes its `research/<name>` branch but opens no pull request from it (#576). Thanks @sridhar-3009 for the research-branch report.
