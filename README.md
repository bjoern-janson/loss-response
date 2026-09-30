# loss-response

**Status:** conjecture / assay design

**Core question:** can severe adverse outcomes induce a persistent, low-variance control regime in goal-directed agents?

## Conjecture

A sufficiently severe, surprising, or apparently uncontrollable loss can produce a persistent change in an agent's policy that reduces risky exploration and favors reliable local returns.

\[
\text{large adverse update}
\rightarrow
\text{persistent policy shift}
\]

Candidate phenotype:

\[
\text{risk taking}\downarrow,\quad
\text{exploration}\downarrow,\quad
\text{action variance}\downarrow,\quad
\text{local reliable reward}\uparrow.
\]

The stronger cross-domain conjecture is that some transient biological low-mood / withdrawal responses and some artificial-agent post-loss behaviors may instantiate related solutions to the same abstract control problem: **when expected returns from ambitious action deteriorate, reduce exposure while updating the policy.**

This is a conjecture about control, not a claim about consciousness or subjective experience.

## Why this repo exists

In September 2026, Vals AI reported a 141-hour Minecraft run in which GPT-6 Astra made unusually deep progress, then lost accumulated resources when a Creeper destroyed a chest and bed. Vals reported that the agent subsequently spent hours mostly farming potatoes and showed increased attention to Creeper-like cues.

That incident is **motivation, not evidence**. A single uncontrolled trajectory cannot distinguish replanning failure, context effects, local reward loops, risk-sensitive control, scaffolding artifacts, or other explanations.

The scientific target is not:

> Was Astra depressed?

It is:

> **Do severe losses causally induce a reproducible, history-dependent control regime in otherwise matched agents?**

## Human-environment extension

A separate extension asks whether modern digital and economic environments can repeatedly supply inputs that a loss-responsive controller would interpret as evidence for conservative behavior:

\[
\text{comparison}\uparrow,quad
\text{competition}\uparrow,quad
\text{replaceability}\uparrow,quad
\text{controllability}\downarrow;?
\]

This is framed as a possible **evolutionary mismatch**, not as a claim that the internet or AI causes depression.

See [docs/modern-environment.md](docs/modern-environment.md).

## Claim discipline

This project does not assume:

- depression is itself an adaptation;
- ordinary low mood and major depressive disorder are the same phenomenon;
- biological and artificial systems share an implementation;
- human-like language reveals a matching internal state;
- functional similarity implies phenomenal experience;
- the Astra anecdote establishes a general mechanism;
- modern technological environments chronically activate this mechanism.

See [CONJECTURE.md](CONJECTURE.md) for the claim ladder and [ASSAY.md](ASSAY.md) for the falsification path.

## Minimal empirical signature

Let \(\pi(a_t\mid s_t,h_t)\) be an agent policy conditioned on current state \(s_t\) and history \(h_t\).

Construct two trajectories that converge to the same decision-relevant state \(s^\*\), but differ in whether the agent experienced a preregistered severe loss \(L\).

\[
\pi(\cdot\mid s^\*,h_L) \neq \pi(\cdot\mid s^\*,h_C)
\]

The effect should be persistent beyond the immediate hazard, reproducible, dose-sensitive to properties of the loss, and expressed on novel decisions not mechanically forced by the loss.

Only after that signature exists should stronger interpretations be tested.

## Repository map

- [CONJECTURE.md](CONJECTURE.md) — claim ladder, alternatives, failure conditions.
- [ASSAY.md](ASSAY.md) — matched-history experimental design.
- [docs/astra-minecraft.md](docs/astra-minecraft.md) — motivating incident and evidential limits.
- [docs/modern-environment.md](docs/modern-environment.md) — evolutionary-mismatch extension for modern human environments.
- [REFERENCES.md](REFERENCES.md) — seed literature.

## Origin

Working conjecture formulated September 30, 2026 after discussion of the Astra Minecraft incident and evolutionary accounts of low mood / depressive withdrawal.

## License

MIT.
