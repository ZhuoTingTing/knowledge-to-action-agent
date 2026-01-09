# Agent Design Patterns — Reading Notes

Use this template for each pattern we study; keep each entry short but concrete.  
（每学一个模式就按此模板记录，尽量短，但必须具体到“怎么落到代码”。）

---

## Pattern: <NAME>

### Intent
- What problem does this pattern solve?
- What “good outcome” does it optimize for?

### Context
- When does this pattern apply?
- What preconditions must be true (team, repo size, tooling, latency/cost limits)?

### Forces (Trade-offs)
- What tensions must be balanced? (accuracy vs latency, autonomy vs safety, flexibility vs simplicity)
- What failure modes is it trying to prevent?

### Solution
- Core idea in 3–7 bullets.
- Key components/roles (e.g., Planner, Executor, Critic, Memory, Tools).
- Control flow: input → steps → output.

### Consequences
- Benefits (what improves, and how).
- Costs/risks (what gets worse, new complexity).
- Common anti-patterns / misuse cases.

### How we apply it in this repo
- Decision: adopt / adapt / skip (and why).
- Files to add/change (exact paths):
  - `...`
- Interfaces/data schemas impacted:
  - `...`
- Safety gates involved (plan review / diff review / verify review):
  - `...`
- Acceptance checks (how we know it works):
  - `...`
- Follow-ups / backlog items:
  - `...`

---
