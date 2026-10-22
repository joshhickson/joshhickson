## Joshua Hickson

I evaluate frontier coding agents, and I study what gets lost when they write code.

The paid work is blind A/B evaluation. One software-engineering spec, run against two anonymized models,
both full trajectories checked against my own ground-truth analysis of the codebase, then ranked with
written rationale and per-trajectory rubric grades.

The rest of it is trying to automate the grading part.

### Berkeley RDI AgentX-AgentBeats, 1st place in the Software Testing Agent track

A competition that drew 1,300+ teams. I was project lead and co-won with Oleksandr Voievodin.

Our entry grades AI-written code on rationale, architecture, security and test quality, using an adversarial
MCTS red agent in a Docker sandbox scored against ground-truth Contextual Integrity Scoring. The repo is
pinned below.

[rdi.berkeley.edu/agentx-agentbeats](https://rdi.berkeley.edu/agentx-agentbeats)

### Contextual Debt

An attempt to measure how much verifiable intent survives the trip from spec to generated code. A
Star-Topology evaluation setup (orchestrator, target model, adversarial MCTS attacker), a Contextual
Integrity Score, and a hashed Decision Bill of Materials, so the audit trail is checkable instead of
something you take my word for. Write-up: [joshuahickson.org/systems/contextual-debt](https://joshuahickson.org/systems/contextual-debt)

### Testing the tools

In October 2026 I turned the contextual-debt scenario into a repeatable agent harness and ran it against
Entire, Git AI and brain0. Agents wrote the reason down; an ordinary cleanup removed it; none of the tools put
it in front of the next agent. Write-up: [joshuahickson.org/philosophy/provenance-tools-test](https://joshuahickson.org/philosophy/provenance-tools-test).
Issues filed: [git-ai#2433](https://github.com/git-ai-project/git-ai/issues/2433),
[git-ai#2434](https://github.com/git-ai-project/git-ai/issues/2434),
[brain0#4](https://github.com/Brain0-ai/brain0/issues/4), and comments on
[entireio/cli#408](https://github.com/entireio/cli/issues/408) and [#1923](https://github.com/entireio/cli/issues/1923).

### Open source

10 merged pull requests to [With](https://github.com/withlang-dev/with), Eric Hartford's systems language,
made by directing coding agents under written rules: nothing posted without my approval of the exact text,
every claim rechecked on current main first.

### How I work

Self-taught, no CS degree. I don't hand-write code; I build by directing AI agents. What I actually do is
evaluation and orchestration: design the experiment, drive the tooling, then defend the call in writing.

I try to build things that someone who doesn't trust me can check. Hashed decision records, answer keys,
blind controls, pre-registration. If a claim in my work isn't traceable to something you can open yourself,
treat it as a question.

Remote, US Pacific. I work asynchronously and I'm best on work that's specified in writing.

Open to contract and full-time work on evaluation, eval harnesses, design partnership and developer
community, with teams working on AI code provenance and agent evaluation.

[joshuahickson.org](https://joshuahickson.org) · josh.hickson.d@gmail.com
