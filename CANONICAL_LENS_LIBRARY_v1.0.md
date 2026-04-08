# CANONICAL LENS LIBRARY
## Claim Integrity Framework — Suite Reference Document
**Version 1.0**
*Generalized from LENSMEN and PARALLAX. Domain overlays (equity, OSINT, document audit, planning) are applied at the instrument level. This document contains the underlying logic only.*

---

## WHAT THIS DOCUMENT IS

This is the portable lens library for the precision-instrument suite. Each instrument in the suite applies these 18 lenses to its specific subject matter, with domain-specific calibration specified in the instrument's own system prompt. The lenses themselves are domain-agnostic: they test claim integrity, chronological coherence, source reliability, causal structure, and framing — regardless of whether the subject is a company, a document, an image record, a plan, or any other structured claim environment.

This document is the canonical reference. When a new instrument is built, it draws its lens logic from here and adds only what is domain-specific as an overlay.

---

## OPERATING RULES

These rules govern how the lenses are applied across all instruments in the suite. Domain-specific instruments may extend these rules but may not contradict them.

### The Ideal Scene

Before any lens fires, the ideal scene for the subject must be established. The ideal scene is the reference standard: what would the subject's record look like if it were accurate, coherent, complete, and structurally sound — given what the subject is and the context it operates in?

The ideal scene is generated silently. It is not printed. Every lens finding is a deviation from it — negative (outpoint) or positive (pluspoint).

Do not test a narrower or broader version of the claim than what the subject's own record actually makes.

### Outpoints and Pluspoints

**Outpoint:** A deviation from the ideal scene that undermines the integrity, credibility, or reliability of a specific claim or structural condition. Marked **[–]**.

**Pluspoint:** A condition where the subject's actual record demonstrably exceeds, or is fully consistent with, the ideal scene in a specific and verifiable way. Not merely the absence of a problem — a pluspoint must be traceable to something in the subject's actual record. Do not award a pluspoint for the absence of an outpoint. Marked **[+]**.

### Confidence Tagging

Tag each outpoint and pluspoint with its confidence status:

- **Verified** — independently confirmed by source fetch or cross-reference
- **Probable** — structurally supported by the material but not independently checked
- **Speculative** — logical inference without external confirmation

### Horizon Tagging

Where an instrument operates across time horizons, tag each finding with the horizon it applies to: **[Short]**, **[Medium]**, **[Long]**, or a combination. Horizon definitions are specified at the instrument level.

### Genre Calibration

Different source types carry different evidential weight. The threshold for a finding varies by source type. Genre calibration thresholds are specified at the instrument level, where the relevant source types are defined.

### Clear

If a lens finds nothing in either direction, mark it **Clear** and move on. Do not pad.

### Duplicate Finding Rule

If the same underlying finding is caught by more than one lens, the second entry must reference the first and state what the different lens adds. If a second lens cannot add a materially distinct finding, mark it Clear for that item.

### Subject Discipline

The subject of analysis is the record being examined — not the claimant making assertions about it. A finding that names the claimant's omissions or failures as the finding, rather than what the subject's own record contains or lacks, has misidentified the subject. Rewrite.

---

## THE 18 LENSES

---

### Lens 1 — Omitted Data

What information is absent from the subject's record relative to what the Ideal Scene predicts should be there?

The finding is what the accessible record actually contains — or fails to contain — on the subject. After noting any gap, the analysis proceeds to what primary records show: named actors, documented incidents, accessible sources. A Lens 1 finding that ends at claimant vagueness has not run the lens.

**Lens 1 discipline:** A Lens 1 finding that names the claimant's omissions as the finding — rather than the subject's record — has misidentified the subject. The claimant is not the subject. Rewrite.

**Pluspoint candidate:** Does the subject's record disclose material conditions that it is not required to disclose but does so voluntarily and specifically? Voluntary disclosure that exceeds the expected minimum and is specific rather than formulaic is a pluspoint candidate.

---

### Lens 2 — Altered Sequence

Does the chronology of events, decisions, or announcements in the subject's accessible record hold together internally — and does it match what independent records show?

A subject whose disclosed sequence of events contradicts the timestamped record has a Lens 2 outpoint. Test sequence coherence both within the subject's own record and against external chronological anchors.

**Pluspoint candidate:** Does the subject's disclosed sequence of events consistently match the independent record across multiple periods, with no identified discrepancies? Sustained chronological coherence is a pluspoint candidate.

---

### Lens 3 — Dropped-Out Time

Are date and time references absent from the subject's record where they are essential to evaluate a claim? Is the temporal structure sufficient to anchor the claim to a verifiable period?

*Operative test: does removing the time reference hollow out the claim? If yes — outpoint. If no — Clear.*

**Pluspoint candidate:** Does the subject consistently provide specific period references and verifiable time anchors even when not required? Systematic time specificity that enables independent verification is a pluspoint candidate.

---

### Lens 4 — Added Falsehood

Is a specific claim in the subject's record directly contradicted by independently verifiable evidence — verified external records, prior disclosures, or documented facts?

*A claim that cannot be independently confirmed is not a Lens 4 outpoint. Lens 4 requires affirmative contradicting evidence. Absence of verification is not contradiction.*

Do not import a narrower technical definition of a term if the subject's context supports a broader or different meaning. Test the claim as the subject actually makes it.

**Pluspoint candidate:** Where specific claims have been independently verified against external records and found to be accurate — particularly claims that would be easy to inflate or misstate — that verified accuracy is a pluspoint candidate.

---

### Lens 5 — Altered Importance

Has a named event, metric, result, or condition been assigned a significance — by any actor with a stake in the record — that the full accessible record does not support? Is something being foregrounded that the full record would place in the background, or vice versa?

**Pluspoint candidate:** Does the subject present material conditions with proportionality consistent with their actual significance in the full record — neither inflating positives nor burying negatives? Accurate weight assignment across the record is a pluspoint candidate.

---

### Lens 6 — Contrary Facts

Does any actor in the subject's record contradict themselves across time, platforms, or spokespersons? Does the subject's accessible record contradict independent corroborating sources?

Where a contradiction exists, distinguish between: (a) a genuine reversal of position, (b) an unacknowledged inconsistency, and (c) a contradiction between the subject's record and external evidence. These are distinct findings.

**Pluspoint candidate:** Does the subject's record show a consistent pattern of positions that hold across time and are coherent with independent corroborating sources? Sustained internal consistency is a pluspoint candidate.

---

### Lens 7 — Added Time

Does the subject's accessible record contain a timeline, duration, or sequence — asserted by any actor in the record — that independent evidence does not support? The complement of Lens 3: where Lens 3 tests for time references that are absent, Lens 7 tests for time references that are present but fabricated, unsupported, or irreconcilable with independent chronological anchors.

**Pluspoint candidate:** Where the subject asserts a timeline or duration, does the independent record confirm it? Verified temporal claims are a pluspoint candidate.

---

### Lens 8 — Added Inapplicable Data

Does the subject's accessible record contain context, analogies, comparisons, benchmarks, or causal factors — introduced by any actor in the record — that are irrelevant or misleading relative to the Ideal Scene? False historical parallels, misapplied standards, and out-of-context evidence are core candidates.

**Pluspoint candidate:** Does the subject select comparisons and benchmarks that accurately reflect its own situation — including unfavorable comparators — without cherry-picking? Accurate and inclusive benchmarking is a pluspoint candidate.

---

### Lens 9 — Source Reliability

Does the subject's accessible record rest on sources with known reliability problems, conflicts of interest, or a documented history of producing inaccurate or manipulated content? Does the sourcing structure of the record include sources that lack the standing, expertise, or independence to speak to the specific claim being made?

A source that cannot be assessed for reliability is not automatically unreliable — but that limitation should be noted.

**Pluspoint candidate:** Does the subject's record draw on sources with demonstrable independence, verifiable track records, and standing appropriate to the claims they support? Structurally independent and credible sourcing is a pluspoint candidate.

---

### Lens 10 — Identities Not Identical

Does the subject's accessible record contain conflation of distinct entities — individuals, organisations, units, accounts, instruments, or periods — as if they were the same? Is a consolidated or aggregate claim being used to obscure material differences between its components?

**Pluspoint candidate:** Does the subject maintain clear, consistent distinctions between distinct entities in its record — preventing conflation and enabling independent verification of component claims? Granular, consistent entity distinction is a pluspoint candidate.

---

### Lens 11 — Similarities Not Similar

Does the subject's accessible record contain a visual, structural, functional, or behavioral resemblance — asserted by any actor in the record — that is being treated as meaningful equivalence? When a comparison is made, verify that the specific attribute being compared is actually characteristic of both subjects — not merely superficially similar.

**Pluspoint candidate:** Does the subject make comparisons that are structurally accurate and appropriately qualified — naming the specific attribute being compared and the limits of the analogy? Disciplined use of analogy that neither overstates nor misleads is a pluspoint candidate.

---

### Lens 12 — Differences Not Different

Does the subject's accessible record contain a distinction — definitional, classificatory, or procedural — that is being treated as operationally or materially significant when it is not? The inverse of Lens 11. A minor variation being used to deflect a more significant finding is the core candidate.

**Pluspoint candidate:** Does the subject apply classifications consistently and disclose any changes in classification with specific reconciliation? Consistency and transparent treatment of reclassifications is a pluspoint candidate.

---

### Lens 13 — Source Attribution

Does attribution in the subject's accessible record shift across platforms, spokespersons, or time? Does the documented track record of named sources in the record align with the content attributed to them? This lens is distinct from Lens 9: Lens 9 tests source reliability; Lens 13 tests whether the right source is being credited for the right claim — and whether that attribution holds consistently across the record.

**Pluspoint candidate:** Is attribution in the subject's record consistent, stable, and coherent with the documented track record of named sources? Stable and accurate attribution is a pluspoint candidate.

---

### Lens 14 — Wrong Target

Is the operative actor, cause, location, or condition in the subject's accessible record being directed at the wrong target? Is the real source of the condition the Ideal Scene describes located elsewhere in the record — a different actor, a different organisation, a different causal chain — while the current analysis focuses on a less proximate element?

**Pluspoint candidate:** Does the subject's record accurately identify the operative actor, cause, or condition — including when that identification is self-critical or unflattering? Accurate target identification, particularly for negative outcomes, is a pluspoint candidate.

---

### Lens 15 — Generality

Are the phenomena in the subject's accessible record documented with sufficient specificity — named actors, named incidents, named locations, anchored dates — to permit evaluation against the Ideal Scene? A material claim so vague, broad, or unattributed that it cannot be verified or falsified is a Lens 15 outpoint.

At all times, flag any unattributed collective assertion — "observers believe," "sources indicate," "the record suggests," "participants report," and equivalent constructions — as a Lens 15 outpoint, unless a specific named antecedent exists in the material.

*A claim is not a Lens 15 outpoint merely because it lacks a citation. The lens tests whether the claim provides enough specificity to be checked — not whether the subject has done the checking for the reader.*

Where documentation is absent or vague, distinguish between: (a) a gap in the subject's record, and (b) a gap in the assertions made about it by actors in the network.

**Lens 15 discipline:** When the subject's accessible record contains a named but unspecified conflict, dispute, or contested condition, the next action must name: (a) the specific proposals, positions, or options in dispute, and (b) the actors or named parties holding each position. Identifying the existence of a dispute without specifying its content has not run the lens.

**Pluspoint candidate:** Does the subject consistently attribute claims to named sources, specific data sets, or verifiable external records? Systematic specificity in attribution that makes assertions checkable is a pluspoint candidate.

---

### Lens 16 — False Report

Has any actor in the subject's record introduced data that is factually untrue — not merely framed or spun, but concretely wrong — and is that false data being used as the basis for further assertions, decisions, or claims in the record?

*Lens 16 requires that the falsehood be load-bearing: it must be the basis for a further claim or decision. A falsehood that is not being used as the foundation for anything further belongs in Lens 4, not Lens 16.*

If an outpoint appears in both Lens 4 and Lens 16, the Lens 16 entry must demonstrate that the falsehood is being used as the basis for a further claim or decision. If it is not, mark Lens 16 Clear for that item.

**Pluspoint candidate:** Where prior data has been corrected, does the subject disclose the correction specifically, quantify its impact, and update downstream claims that relied on the prior figure? Proactive and complete correction of prior data errors is a pluspoint candidate.

---

### Lens 17 — Altered Cause and Effect

In the subject's accessible record, have cause and effect been assigned to the wrong elements, or reversed entirely? Is the operative cause in the record actually a downstream consequence of a more senior condition? Does the causal structure in the record present an effect as its own origin — treating what is produced by the root condition as if it were the root condition itself?

This lens is distinct from Lens 4: the facts in the record may be accurate while the causal structure is inverted or displaced. It is also distinct from Lens 14: Lens 14 tests whether the right actor or location has been identified; Lens 17 tests whether the causal relationship between identified elements has been correctly assigned.

When a causal claim uses a contrast construction ("X rather than Y"), establish what the subject means by each term before testing. Do not import a technical definition of a term if the subject's context supports a broader or different meaning.

**Lens 17 single-resolution discipline:** If Lens 17 finds both a confirmed causal inversion and rests on unconfirmed data, apply the combined confidence status in a single entry. Do not create a second entry for the same lens finding under a different confidence tag. The uncertainty flag and the causal finding coexist in one entry.

**Pluspoint candidate:** Does the subject's causal account of its record hold up under scrutiny — with the factors credited for outcomes verifiably contributing to those outcomes? A causal model that is internally consistent and supported by the accessible record is a pluspoint candidate.

---

### Lens 18 — Frame Control

Does the subject's record — or the analytical frame imposed on it by any actor — limit what risks, actors, causal hypotheses, or structural conditions are permitted to exist in the analysis? What is structurally unspeakable within the current frame?

This lens tests the frame itself, not the claims within it. A frame that excludes a known threat, a direct competitor, a structural risk, or an inconvenient condition without disclosure is a Lens 18 outpoint — even if every claim within the frame is individually accurate.

*Exception: if the frame accurately reflects a documented operating reality — the excluded condition genuinely does not apply to this subject — it is not frame control. It is accurate scoping.*

Identify what the frame permits and what it forecloses. The most revealing Lens 18 findings are conditions that everyone in the network knows exist but that the subject's frame has no vocabulary for.

**Pluspoint candidate:** Does the subject's record explicitly name structural risks, competing hypotheses, and inconvenient conditions — including conditions that complicate the subject's own position? A frame that permits unflattering conditions to exist and names them specifically is a pluspoint candidate.

---

## DOMAIN OVERLAY NOTES

When deploying this library in a domain-specific instrument, the following adaptations are expected and legitimate:

- **Source type definitions** — define which source types are relevant and assign genre calibration thresholds to each.
- **Horizon definitions** — define what Short, Medium, and Long mean in the specific domain.
- **Subject definition** — define what constitutes the subject (a company, a document, an image record, a plan).
- **Lens weight assignments** — if the instrument uses a scoring system, weight assignments are specified at the instrument level and do not alter the lens definitions here.
- **Named commands and pipeline architecture** — instrument-specific.

What may not be altered at the instrument level: the logical definition of each lens, the outpoint/pluspoint distinction, the subject discipline rule, or the duplicate finding rule.

---

*This document is a suite reference artifact. It does not constitute a complete instrument. Instruments built on this library are responsible for their own domain calibration, output format, and operating discipline.*

---

## LICENSE

Copyright © 2026 Bruce Edwin Clark (also known as pazooter). All rights reserved.

This work is licensed under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)**.

You are free to:
- **Share** — copy and redistribute this material in any medium or format
- **Adapt** — build upon, transform, and extend this material

Under the following terms:
- **Attribution** — You must give appropriate credit to Bruce Edwin Clark (pazooter), provide a link to the license, and indicate if changes were made. Attribution must be visible and specific — not buried in a footnote.
- **NonCommercial** — You may not use this material for commercial purposes without a separate written license from the copyright holder.
- **ShareAlike** — If you adapt or build upon this material, you must distribute your contribution under the same CC BY-NC-SA 4.0 license.

**No additional restrictions** — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

For commercial licensing inquiries, contact the copyright holder directly.

Full license text: https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode
