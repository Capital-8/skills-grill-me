---
"mattpocock-skills": patch
---

Skills that dispatch subagents (`implement-spec`, `code-review`, `codebase-design`, `improve-codebase-architecture`, `wayfinder`, `research`, `grilling`, `chief-of-staff`) now say to start each one with a fresh context window rather than forking the current conversation, which some harnesses (Codex) do by default and which throws away the clean context a subagent exists for.
