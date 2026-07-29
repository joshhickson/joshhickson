## Joshua Hickson

I evaluate frontier coding agents, and I build the systems that grade them.

The paid work is blind A/B evaluation. One software-engineering spec, run against two anonymized models,
both full trajectories checked against my own ground-truth analysis of the codebase, then ranked with
written rationale and per-trajectory rubric grades. Ten evaluations in my first month, so twenty
trajectories.

The rest of it is trying to automate the grading part.

### Berkeley RDI AgentX-AgentBeats, 1st place in the Software Testing Agent track

1,300+ teams entered. The judging panel included authors of τ²-Bench, GAIA2, CyberGym and AgentBench, plus
researchers from Google DeepMind, Meta, Sierra and Lambda.

Our entry grades AI-written code on rationale, architecture, security and test quality, using an adversarial
MCTS red agent in a Docker sandbox scored against ground-truth Contextual Integrity Scoring. The repo is
pinned below.

[rdi.berkeley.edu/agentx-agentbeats](https://rdi.berkeley.edu/agentx-agentbeats)

### Contextual Debt

An attempt to measure how much verifiable intent survives the trip from spec to generated code. A
Star-Topology evaluation setup (orchestrator, target model, adversarial MCTS attacker), a Contextual
Integrity Score, and a hashed Decision Bill of Materials, so the audit trail is checkable instead of
something you take my word for.

### Research

Lead author on an AI-safety paper about inference-time monitoring of model behavior, written with an
academic research advisor at McGill. It is under double-blind review, so that is all I can say about it
right now.

### How I work

Self-taught, no CS degree. What I actually do is evaluation and orchestration: design the experiment, drive
the tooling, then defend the call in writing.

I try to build things that someone who doesn't trust me can check. Hashed decision records, answer keys,
blind controls, pre-registration. If a claim in my work isn't traceable to something you can open yourself,
treat it as a question.

Remote, US Pacific. I work asynchronously and I'm best on work that's specified in writing.

Open to evaluation contracts, red-team engagements, eval-harness work, and written work trials.

[joshuahickson.org](https://joshuahickson.org) · josh.hickson.d@gmail.com
