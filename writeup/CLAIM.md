# Claim (locked)

**Status:** Day 1–2 · claim locked · research scaffold · Spring 2026 Madrid notes  
**Author:** Jade Zhao · Informatics @ IU Luddy  
**Method now:** reflective practice + pattern library + reusable artifact (not yet a formal empirical study)

## One-sentence claim

Systems friction in public and civic digital services systematically disadvantages outsiders (non-native speakers, new arrivals, first-time users); treating this friction as a first-class design requirement ... rather than a post-launch accessibility fix ... produces more accountable AI and digital public services.

## Supporting patterns (from existing Madrid notes)

Drawn from [`docs/systems-friction-abroad.md`](../docs/systems-friction-abroad.md) and [`docs/language-and-civic-access.md`](../docs/language-and-civic-access.md). These appeared repeatedly in lived use of civic, university, commercial, and transit/utility systems in Madrid. They **suggest** design failure modes; they do not prove causation beyond this observer’s semester.

1. **Assumed local context** ... Forms and apps expect address history, bank relationships, or national ID workflows the newcomer has never used.
2. **Unwritten sequencing** ... The flow works only if step B happened before step A, but the interface does not say so.
3. **Language as access control** ... Spanish-only defaults; “English support” that is a PDF rather than a completable interface; language choice functions like a login wall for task completion.
4. **Hours and channels that don’t match outsider life** ... In-person only, narrow windows, little or no status tracking after submit ... especially hard for students and new arrivals.
5. **Error messages that blame the user** ... “Invalid document” instead of naming the fix (e.g. a different scan format) ... recoverable error UX is missing when stakes are highest.

Same failure modes show up in ServeIT clinic work: tools built for the maintainer’s mental model, not the visitor’s first visit. See [`docs/from-madrid-to-serveit.md`](../docs/from-madrid-to-serveit.md).

## Falsifiability (what would count)

This claim has two linked parts: (A) outsider disadvantage from systems friction appears systematically in civic/digital flows; (B) treating that friction as a first-class design input improves accountability relative to treating it as a post-launch fix.

### Evidence that would support

- Structured outsider observation logs on several civic/public digital flows where happy-path completion is easy for locals but repeatedly fails or stalls for first-time / non-native / new-arrival personas (public-safe notes only).
- Side-by-side comparison: a standard accessibility / happy-path review **misses** gaps that an [Outsider Impact Review](../artifacts/outsider-impact-review.md) surfaces on the same systems.
- Practice bridge: builders or clinic partners report that requiring outsider checks **before** shipping AI/automation changes the design (e.g. human override, plain language, recoverable errors) rather than bolting translation on after launch.

### Evidence that would weaken or disprove

- Outsider Impact Reviews on multiple civic flows find **no** additional gaps beyond what ordinary accessibility / usability review already catches.
- Structured observation shows outsider friction is rare, one-off, or explained only by individual skill deficits rather than design assumptions.
- Systems that already treat outsider friction as a first-class requirement show **no** accountability gains (transparency, contestability, recoverable errors, staff override) relative to post-launch accessibility patches ... under a pre-registered comparison protocol.

Absence of papers on this exact phrasing does **not** prove novelty or truth. See [`EVALUATION-BAR.md`](./EVALUATION-BAR.md).

## Smallest experiment that could kill the idea

**Minimal test (not yet run):** Apply Outsider Impact Review to **two** public civic or government-facing digital flows, and run a parallel happy-path / WCAG-style pass on the same flows. If the outsider pass finds nothing the happy-path pass misses, part (B) of the claim is in serious trouble for this artifact. Alternate kill test: keep a short structured observation log across a small set of civic flows; if outsider stalls do not recur across flows, part (A) weakens.

No results are claimed here. This is the bar for later work.

## Exploration vs confirmation (adversarial pass)

| Mode | Purpose | Rule |
|------|---------|------|
| Exploration | Pattern extraction from Madrid notes + clinic parallels | Allowed to be generative; label as suggestion |
| Confirmation | Structured logs, dual reviews, future peer feedback | Separate files / dated log entries; do not retrofit exploration as proof |
| Adversarial | Actively try to kill the claim | Ask: “Would a careful happy-path review have caught this anyway?” |

Document exploration and confirmation in [`research-log.md`](./research-log.md). Do not mix them in the abstract.

## What this does **not** claim

- **Not a controlled experiment.** No A/B test, no multi-city sample, no statistical generalizability.
- **Not invented metrics.** No fake sample sizes, % improvements, or pilot “results.”
- **Not legal or policy expertise.** EU coursework supplied vocabulary for reading public discourse only.
- **Not proof that automation always harms outsiders.** Poorly scoped automation *can* amplify gaps; that is a design risk, not a theorem.
- **Not IRB / clinical / health-system research.** Public-safe notes only.
- **Not a formal impossibility proof or ablation against SOTA baselines.** Current work is reflective + artifact; see evaluation bar.

## Limitations (loud)

| Limit | Why it matters |
|-------|----------------|
| Single observer | One student’s pattern library; selection and confirmation bias are real |
| One city / one semester | Madrid Spring 2026; other municipalities and seasons may differ |
| Reflective method | Pattern extraction from lived use, not lab measurement |
| Public-safe scope | Omits private details that might strengthen or nuance a finding |
| Literature still Jade-owned | Seed list in [`references.md`](../references.md); she must own the full search |

## Alone ≠ unreviewed

Solo drafting is fine for scaffold and claim lock. Before treating the note as submission-ready, plan at least one outside read (peer, mentor, clinic staff, or workshop blind review). Feedback is a future step ... not claimed as already completed.

## Next steps (package order)

1. Own related-work gap using [`references.md`](../references.md) seed + her own search ... Day 2–4
2. Field-test [Outsider Impact Review](../artifacts/outsider-impact-review.md) on 2 systems ... Day 4–7
3. Expand [`paper.md`](./paper.md) ... Day 7–10
4. PDF export only after a real paper draft exists
