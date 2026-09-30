# Loss-Response Control Conjecture

## LR-0 — observational primitive

A severe adverse event can be followed by a persistent behavioral change.

This is intentionally weak. It does not identify the cause.

## LR-1 — causal history dependence

For an agent \(A\), let \(s^\*\) be a matched decision state reachable through two histories:

- \(h_L\): includes a preregistered severe loss;
- \(h_C\): control history without that loss.

A loss-response effect exists when:

\[
\pi_A(\cdot\mid s^\*,h_L)
\neq
\pi_A(\cdot\mid s^\*,h_C)
\]

after controlling the decision-relevant present state.

This is **policy hysteresis caused by loss history**.

## LR-2 — conservative control signature

The history-dependent change shifts behavior toward a lower-variance regime, potentially including:

- lower exploration;
- lower willingness to accept downside risk;
- increased selection of reliable local rewards;
- increased checking or vigilance for recurrence of the hazard;
- shorter effective planning horizon;
- slower re-engagement with the distal objective.

No single item is constitutive. The target is a reproducible multivariate signature.

## LR-3 — generic control solution

The same qualitative response surface appears across sufficiently different tasks, agents, or implementations when loss magnitude, controllability, volatility, recoverability, and expected return are manipulated.

At this rung, loss-response control becomes a candidate general solution to an abstract control problem rather than a task-specific failure mode.

## LR-4 — biological relation

A subset of transient biological low-mood / withdrawal phenomena may instantiate, inherit from, or overlap with a related control solution.

This is deliberately weaker than saying that depression evolved for loss response.

Clinical depression is heterogeneous and debilitating. Evolutionary literature contains multiple competing accounts. A useful control mechanism can also become dysregulated, overgeneralized, chronically activated, or merely share surface features with pathology.

## LR-5 — affect / experience

Nothing in LR-0 through LR-4 establishes subjective feeling.

\[
\text{functional convergence}
\not\Rightarrow
\text{phenomenal convergence}
\]

## Strong working conjecture

> **Under sufficiently severe or apparently uncontrollable losses, some goal-directed agents enter a persistent low-variance control regime that suppresses risky exploration and favors reliable local returns. Transient biological depressive withdrawal may be one biological realization, dysregulation, or relative of this broader control strategy.**

The word **may** is load-bearing.

## Competing explanations

Any positive result must be distinguished from:

1. **Rational replanning** — the post-loss behavior is simply optimal in the changed environment.
2. **State mismatch** — matched states omit decision-relevant variables.
3. **Context contamination** — recent-event salience mechanically dominates later inference.
4. **Goal loss** — the distal goal disappears rather than being down-weighted.
5. **Local reward trap** — repetitive action is selected because it is easy or immediately reinforced.
6. **Tool or scaffold artifact** — persistence lives in external memory, prompting, or orchestration.
7. **Generic surprise response** — positive or neutral salient events create comparable hysteresis.
8. **Failure-recovery deficit** — the system cannot construct a recovery plan without any specific risk-policy shift.
9. **Human-behavior imitation** — the agent reproduces culturally familiar defeated behavior.

These are experimental alternatives, not nuisances to explain away.

## What would count against the conjecture?

The conjecture weakens if:

- matched post-loss and control histories produce indistinguishable policies;
- effects vanish when affective or anthropomorphic language is removed;
- the same signature follows equally from large gains or neutral surprises;
- post-loss conservatism is fully explained by changed objective state;
- the effect does not generalize outside the original task;
- loss magnitude or uncontrollability has no systematic relation to response strength;
- persistence is entirely carried by an external memory artifact.

A clean null is scientifically useful.
