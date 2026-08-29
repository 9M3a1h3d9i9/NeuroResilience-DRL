# NeuroResilience-DRL

> Research direction: improving network resilience (تاب‌آوری شبکه) through Deep Reinforcement Learning.

## Vision

**NeuroResilience-DRL** explores how deep reinforcement learning can support adaptive decisions when a network experiences congestion, failures, or changing operating conditions.

The long-term research direction is to connect:

**Network State → Graph Representation → DRL Agent → Resilience Action → KPI Evaluation**

## Current Status

**Early-stage research prototype.**

The repository is maintained as a research workspace and is not presented as a completed production system or as evidence of measured performance.

## Research Questions

- How should network resilience be represented as an RL objective?
- Which network state features are most useful for adaptive decisions?
- How can an agent react to failures without sacrificing overall network performance?
- Can graph representations improve generalization across network topologies?

## Planned Roadmap

### Phase 1 — Problem formulation
- Define resilience objectives.
- Define state, action, transition, and reward models.

### Phase 2 — Simulation environment
- Build reproducible network scenarios.
- Model congestion and node/link failures.
- Track relevant network KPIs.

### Phase 3 — DRL agent
- Establish baseline policies.
- Implement a suitable DRL algorithm.
- Compare learned and heuristic strategies.

### Phase 4 — Graph-based extension
- Represent topology as a graph.
- Investigate GNN-based state representations.
- Evaluate transfer across topologies.

### Phase 5 — Evaluation
- Resilience under failure.
- Recovery time.
- Service-level performance.
- Computational cost.

## Long-Term Direction

The project may become a supporting research component of a broader intelligent telecom-network optimization platform.

## Integrity Note

Results, performance percentages, and claims will only be added after experiments are actually executed and reproducibly evaluated.

## Author

Mohammad Mahdi Shafighi — M.Sc. Artificial Intelligence
