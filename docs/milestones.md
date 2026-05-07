# Milestones

> Bridge between `docs/project-brief.md` and `docs/roadmap.md`.
>
> A milestone groups roadmap features (`vX.Y.0` entries) into a coherent, shippable, user-visible slice of value. Roadmap entries should not exist outside a milestone.
>
> **Cannot create milestones until `docs/project-brief.md` is approved.** This is Phase 0.5 in `PROJECT_PROTOCOL.md`.

---

## How milestones work

- A milestone is the smallest version of the product that delivers a coherent slice of brief-approved scope.
- Every roadmap entry (`vX.Y.0`) belongs to exactly one milestone.
- A milestone's done criteria must reference the brief — specifically, the boundary contracts, isolation tests, and integration risks for the components it touches. A milestone that ships without verifying its isolation tests is not done.
- New milestones cannot be created from product ideas alone — the underlying scope must already be in the approved brief. If it isn't, the brief needs to be revised and re-approved first.

---

## Status

- [ ] Drafted
- [ ] Reviewed by owner
- [ ] **Approved** — date: `YYYY-MM-DD`, by: `[NAME]`

---

## Milestones

### M1 — [Milestone name]

**Goal**: [What user-visible capability does this milestone deliver? One sentence, ending in "...so that [user] can [action]".]

**From brief**: [Which scope item(s) from `docs/project-brief.md` → *Boundaries — IN scope* does this milestone fulfill? Quote them directly.]

**Approved**: `YYYY-MM-DD`

**Features in this milestone**:

- `v0.1.0` — [feature name]
- `v0.2.0` — [feature name]
- `v0.3.0` — [feature name]

**Done criteria**:

- [ ] [User can do X end-to-end in production]
- [ ] Isolation test from brief passes for: [components]
- [ ] Integration risk resolved or fallback verified: [integrations]
- [ ] [Other measurable, binary criterion]

---

### M2 — [Milestone name]

**Goal**: [...]

**From brief**: [...]

**Approved**: `YYYY-MM-DD`

**Features in this milestone**:

- `vX.Y.0` — [feature name]
- `vX.Y.0` — [feature name]

**Done criteria**:

- [ ] [...]

---

## Backlog milestones

Milestones that are recognised as future scope but not yet approved. These exist so the team can see the shape of the road ahead, but they have no done criteria and no roadmap entries until they are promoted into the **Milestones** list above with owner approval.

- **[M3 — Name]** — sketch: [one sentence]
- **[M4 — Name]** — sketch: [one sentence]
