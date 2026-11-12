# Tech Info: Codex project instructions

- Use `.agents/skills/lean-coding/SKILL.md` for focused, cost-aware changes when relevant.
- This is a static website. Start with `index.html` and only the necessary files under `assets/css/`; inspect `admin/` only if the task involves the admin area.
- For a design tweak, change the named section or component, not the whole page. Reuse styles and preserve mobile responsiveness and accessibility.
- Avoid full-project dumps, lengthy prior-chat rereads, unnecessary dependency installations, and unrelated refactoring.
- Run a small relevant check of affected HTML/CSS and confirm the requested change did not break layout; expand checking if risk warrants it.
- Read `docs/STATE.md` when resuming a task; validate against source. Update it only for meaningful milestones.
- Never deploy, change secrets, delete content, or modify payment/security logic without explicit authorization.
