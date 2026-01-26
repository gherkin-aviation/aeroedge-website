# AeroEdge Breaking Changes Log

Track inter-node contract changes that affect other nodes. Update this when modifying events, queries, or shared types.

## Format

```
## [Date] - [Node] - [Change Type]
**What changed:** Brief description
**Affects:** Which nodes need to update
**Migration:** What other nodes need to do
```

---

## Active Changes

(None yet - add entries as breaking changes occur)

---

## Example Entry

## 2026-01-21 - Logbook - Event Schema
**What changed:** `flight.created` now includes `instructor_id` field
**Affects:** scheduler (listens to this event), syllabus (listens to this event)
**Migration:** Update event handlers to expect optional `instructor_id`

---

## Changelog

| Date | Node | Change | Affects |
|------|------|--------|---------|
| - | - | - | - |
