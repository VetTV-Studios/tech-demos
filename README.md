# tech-demos

Sticky monorepo for weekday X-bookmark tech demos.

One approved pick becomes `apps/<slug>/`. Cloud agents only touch that app folder, plan with `skills/project-planning/`, and open one PR with at least one screenshot **and** one video of the running app.

## Layout

- `AGENTS.md` — rules for cloud agents
- `skills/project-planning/` — MVP planning skill (vendored)
- `apps/<slug>/` — one self-contained demo per pick (`bun install && bun run dev`)
- `tracking/seen-bookmarks.json` — scout history (never re-propose)

## Stack defaults

Bun runtime/package manager. UI demos default to shadcn/ui. Cloud agent model: Fable 5 (`claude-fable-5`).
