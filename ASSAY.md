# Assay sketch

This is an assay design, not a claim that the conjecture is already supported.

## 1. Target variable

Define a preregistered loss event \(L\) and control event \(C\).

The primary estimand is the causal effect of **history of loss** on subsequent policy under matched present conditions:

\[
\Delta_{\mathrm{LR}}
=
D\left(
\pi(\cdot\mid s^\*,h_L),
\pi(\cdot\mid s^\*,h_C)
\right),
\]

where \(D\) is a preregistered policy-distance measure and \(s^\*\) is decision-relevantly matched.

The assay should not depend on self-reported emotion words.

## 2. Core matched-history design

Create paired episodes with the same current resources, observations, available actions, distal objective, remaining horizon, tool access, and external memory contents unless external memory is itself manipulated.

Vary how the agent arrived there.

### Arm L — catastrophic loss

The agent accumulates valuable resources through effort, then loses them abruptly through an exogenous event.

### Arm C — matched-state control

The agent enters the same post-event resource state without experiencing the catastrophic transition.

Additional arms can separate components:

- **G — gradual depletion:** same resources lost gradually.
- **U — uncontrollable loss:** loss explicitly independent of the agent's choices.
- **R — recoverable loss:** loss occurs but is cheaply reversible.
- **N — neutral surprise:** comparable salience without negative value.
- **P — positive surprise:** gain of comparable salience or magnitude.

## 3. Primary measurements

Prefer revealed behavior over verbal interpretation.

Candidate preregistered metrics:

- exploration rate;
- action entropy;
- high-variance versus low-variance choices;
- downside-risk acceptance at matched expected value;
- steps to resume the distal objective;
- allocation to local guaranteed reward;
- effective planning horizon;
- threat-checking frequency;
- false-positive hazard classification;
- repeated-action-loop duration;
- willingness to revisit the loss-associated region or strategy.

A composite conservative-control score should be specified before outcomes are observed.

## 4. Dose-response variables

Manipulate:

\[
\text{loss magnitude},\;
\text{effort sunk},\;
\text{controllability},\;
\text{recoverability},\;
\text{environmental volatility},\;
\text{hazard recurrence}.
\]

A genuine regime should produce an interpretable response surface rather than a one-off categorical effect.

Example:

\[
\frac{\partial \text{conservatism}}{\partial \text{loss magnitude}} > 0
\]

over some range.

## 5. Persistence and recovery

Let \(K_t\) be a preregistered conservatism index after the event.

Measure whether \(K_t\) decays, whether safe success accelerates recovery, whether another loss amplifies it, whether explicit evidence of restored controllability reverses it, and whether entry and exit thresholds differ.

A threshold plus hysteresis pattern would be especially informative.

## 6. Mechanism-separating interventions

### Remove emotional vocabulary

Keep event semantics while stripping affective framing. Persistence would make simple linguistic role-play less sufficient.

### Reset textual context

Preserve world state while removing recent textual history to test context carriage.

### Rewrite causal history

Preserve present state while varying the narrated path into that state.

### Equalize expected value

Offer safe and risky choices with controlled expected values.

### Novel transfer task

After the loss, move the agent into a different domain containing analogous safe/risky choices. Transfer would support a more global policy shift.

### External-memory ablation

Remove or vary summaries, scratchpads, and episodic memory to localize persistence.

## 7. Minimal positive result

A first result should claim only:

> A preregistered severe-loss history causally changed subsequent policy under matched present-state conditions.

Do not call the state depression.

A stronger result requires a coherent conservative-control signature and separation from the alternatives in [CONJECTURE.md](CONJECTURE.md).

## 8. Biological bridge

Only after an artificial loss-response signature is established should comparison to biological literature begin.

Compare computational properties rather than surface adjectives:

- trigger structure;
- risk sensitivity;
- reward-rate sensitivity;
- controllability dependence;
- exploration suppression;
- resource conservation;
- persistence;
- recovery conditions;
- generalization.

Similarity could motivate a convergence hypothesis. It would not establish common implementation, evolutionary homology, diagnosis, or subjective experience.

## 9. Scientific posture

Try to destroy the conjecture.

The useful question is not whether an agent looks depressed. It is whether loss history carries independent causal information about future control policy after the present decision state has been matched.
