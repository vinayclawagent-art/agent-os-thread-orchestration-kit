# Agent OS Promotion Decision Card

Package: [[Agent OS Thread Orchestration Kit]]
Source: [[Codex Threads as an Agent Operating System]]
Status: template-ready, evidence-pending

## Purpose
Use this after the first real [[Agent OS Thread Orchestration Kit/Agent OS Thread Map]] run. It converts captured thread-map evidence into a promote / pilot-only / iterate / hold decision without claiming validation before proof exists.

## Evidence prerequisites
| Required proof | Link / note | Pass? | Notes |
| --- | --- | --- | --- |
| Filled thread map with supervisor, worker threads, sensors, plugins, and handoffs |  |  |  |
| Real task context and operator constraints |  |  |  |
| Run transcript, command logs, repo diff, screenshots, or generated artifact |  |  |  |
| Failure/friction notes showing where the thread map broke down |  |  |  |
| Human review of whether the map improved handoff clarity |  |  |  |

## Decision gate
Choose exactly one after reviewing the evidence bundle.

- [ ] **Promote** — evidence shows the thread map reliably improves agent orchestration and should become a repeated VinClawLabs workflow.
- [ ] **Pilot-only** — useful on this task class, but needs 1-2 more runs before skill or README claims are broadened.
- [ ] **Iterate** — promising, but missing sensors, stopping rules, or handoff proof must be fixed before reuse.
- [ ] **Hold** — evidence is too weak or the workflow is not currently relevant.

## Claim patch checklist
Patch claims only where evidence supports them.

- [ ] Package README updated with evidence-backed result and remaining limits.
- [ ] Prototype README updated with the observed run sequence and failure modes.
- [ ] Skill draft patched only if the workflow repeated cleanly enough to be procedural.
- [ ] Improvement loop next focus updated to the next evidence-backed step.

## Decision notes
- Decision:
- Evidence summary:
- Claim patches approved:
- Next action:
