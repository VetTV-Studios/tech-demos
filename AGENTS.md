# Agent rules — tech-demos

This is the sticky demo monorepo. Do **not** create a new GitHub repository for a demo.

## Scope

- Only add or update files under `apps/<kebab-slug>/` for the approved pick.
- Leave `tracking/`, root config, and other apps alone unless the human explicitly asks.
- Each app must be self-contained: `bun install && bun run dev` from that app directory.

## Planning

1. Read and follow `skills/project-planning/SKILL.md`.
2. Write `apps/<kebab-slug>/PLAN.md` before substantial implementation.
3. Single-user MVP only. Prefer Bun scaffolds (`bunx create-*`) and shadcn/ui.
4. Every Bun project needs `bunfig.toml` with `[install] minimumReleaseAge = 259200` before `bun install`.

## Validation (required)

Before opening the PR, attach **both**:

- at least one screenshot of the running app
- at least one video of the running app

These are not optional.

## PR

- Open exactly one PR against the default branch.
- Title/body name the tech and demo angle.
- Model for initial prototypes: Fable 5 (`claude-fable-5`) unless the owner says otherwise.
