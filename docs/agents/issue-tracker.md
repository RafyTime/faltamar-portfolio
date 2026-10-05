# Issue tracker

Issues and specs live in local Markdown, grouped by feature or PR.

## Paths

- Work folder: `docs/.work/<feature-or-pr-slug>/`
- Spec: `<work-folder>/spec.md`
- Tickets: `<work-folder>/tasks/<NN>-<slug>.md`, numbered from `01`
- Exploration map, when needed: `<work-folder>/map.md`

Create one file per ticket. Fetch tickets by their referenced path.
Record triage state as a `Status:` line near the top, using
`docs/agents/triage-labels.md`. Append discussion under `## Comments`.

## Wayfinder

Use the work folder's map and tasks for exploration.
Record ticket kind in `Type:` using `research`, `prototype`,
`grilling`, or `task`. Record dependencies in `Blocked by: NN, NN`.

Choose the lowest-numbered open, unblocked, unclaimed task.
Set `Status: claimed` before starting work. Resolve it by adding
`## Answer`, setting `Status: resolved`, and adding a summary
and ticket link to the map's Decisions-so-far section.
