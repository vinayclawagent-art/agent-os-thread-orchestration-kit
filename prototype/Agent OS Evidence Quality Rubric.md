# Agent OS Evidence Quality Rubric

Source: [[Codex Threads as an Agent Operating System]]  
Package: [[Agent OS Thread Orchestration Kit]]  
Status: template-ready; evidence pending.

## Purpose
Grade whether future agent-OS thread orchestration proof is strong enough to change package README, prototype, infographic, or skill-draft claims. This rubric is not validation by itself; it is the gate for judging a future real trial.

## Minimum evidence bundle
| Evidence slot | What must be linked or pasted | Evidence link / note |
|---|---|---|
| Real task / system boundary | Name the task, agent threads, sensors, plugins, routing rule, and stop condition tested |  |
| Thread map filled | Completed map showing each process, handoff, owner, and evidence artifact |  |
| Execution trace | Logs, transcript, screenshots, or state transitions proving threads ran in the claimed order |  |
| Failure / escalation evidence | What happened when a handoff stalled, tool failed, or thread produced ambiguous output |  |
| Operator review notes | Human review of whether the architecture reduced confusion or just added ceremony |  |
| Decision artifacts filled | Promotion card and post-trial debrief completed from evidence links, not memory |  |

## Scoring gate
| Outcome | Use only when | Decision notes |
|---|---|---|
| Promote to repeatable pilot | Thread map, execution trace, escalation path, and review evidence all support the claimed operating model. | |
| Pilot-only / narrow | The architecture works for one task class but requires narrower routing, fewer threads, or clearer operator roles. | |
| Iterate | Evidence is partial, handoffs are unclear, or the loop does not reach a clean stop condition. | |
| Hold | No real execution trace, no operator review, or the thread model creates more ambiguity than it removes. | |

## Claim patch checklist
- [ ] Evidence bundle is filled with durable links or pasted excerpts.
- [ ] Agent OS Promotion Decision Card is completed from evidence, not memory.
- [ ] Agent OS Post-Trial Debrief Template lists exact README/prototype/skill-draft claims to patch.
- [ ] Any public wording still says template-ready/evidence-pending unless the scoring gate explicitly allows stronger claims.
- [ ] Claims that lack proof are moved to backlog instead of promoted.

## Operator notes
- Treat missing screenshots, logs, diffs, or review notes as a failed evidence slot.
- Prefer a narrow pilot decision over broad reusable-workflow claims when proof comes from only one task.
- Keep all future claim patches reversible and linked back to the evidence row that justified them.
