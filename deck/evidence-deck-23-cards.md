# The Evidence Deck — 23 cards

Twenty-three cards of evidence discipline for anyone evaluating AI systems —
whether it works, for whom, and under which conditions. Distilled from *Prove,
Don't Persuade* and *Test the Claim*. Sections: **Claims** (5), **Gates** (5),
**Measurement** (5), **Ratings** (4), **Records** (4).

One card type: why it goes wrong, the move, the line.

**Anyone can demo AI. The edge is proving it works.**

---

## CLAIMS · What is a claim, and what survived testing

### 01 · Policy versus control
**Why it goes wrong:** A written policy reads like an accomplished fact, and the audit inherits the feeling instead of the truth.

**The move:** A policy is a claim about how the organisation intends to operate. A control is the practice that actually reduces risk. Audit the practice.

*"A policy is a claim. A control is a claim that has survived testing."*

### 02 · The board does not need a policy
**Why it goes wrong:** Boards are shown documents and asked to feel reassured.

**The move:** The board needs to know whether the policy is true. A report that repeats management's assurances is not assurance; a report that tests them is.

*"The board does not need a policy. It needs to know whether the policy is true."*

### 03 · The demo versus the deployment
**Why it goes wrong:** A working demo proves the solution runs. Runs is not reliable, and the gap between them is where applied AI lives.

**The move:** Read every demo as an assertion: a claim that has not yet met its evidence. A deployment has to survive inputs the demo never showed you.

*"A demo is engineered to be impressive. A deployment has to work."*

### 04 · Fluency is camouflage
**Why it goes wrong:** The smooth answer gets a pass because it reads well.

**The move:** Fluency is not a signal of correctness or fairness; it is camouflage. Separate how it reads from whether it holds.

*"The most dangerous AI output is the one nobody checked."*

### 05 · Agreement is not evidence
**Why it goes wrong:** A session where the AI was right every time feels like proof of reliability.

**The move:** A demo persuades; a log proves — because the log shows the work, including where the AI was confidently wrong and you caught it. If the log reads as a smooth collaboration, you have written persuasion, not proof.

*"Agreement is not evidence."*

---

## GATES · Three gates, not one launch

### 06 · Gate one: prototype to bounded pilot
**Why it goes wrong:** Polished prototypes get shown to clients as if they were systems.

**The move:** Before a bounded pilot: defined use, held-out evaluation against the brief, data and security review, named owner, tested fallback, limits on users, actions, duration and volume. Missing any of it? Keep it in development.

*"A polished prototype is not a production system."*

### 07 · Gate two: pilot to production
**Why it goes wrong:** Pilot scope quietly widens, and the pilot becomes production by drift.

**The move:** Before production: results from representative conditions, measured review workload, incident and rollback rehearsal, monitoring and access controls, approvals from the responsible teams. Missing any? Extend, redesign or stop — do not widen the scope.

*"Do not quietly widen the scope."*

### 08 · Gate three: continued operation
**Why it goes wrong:** The go-live is treated as the finish line, and the evaluation never runs again.

**The move:** Continued operation requires scheduled and change-triggered evaluation, monitoring of relevant failures, current ownership, and action on threshold breaches. The question changes from "does it work?" to "is it still working, and how would I know if it stopped?"

*"Is it still working — and how would you know if it stopped?"*

### 09 · Re-baselining
**Why it goes wrong:** A disappointing result gets rescued by rewriting the acceptance rule.

**The move:** After any change to model, prompt, source or workflow: keep the old evidence and run a new comparison. A changed threshold is a new decision to explain, not a way to rescue a score.

*"A changed threshold is a new decision to explain."*

### 10 · The dangerous practitioner
**Why it goes wrong:** The line between prototype and production is invisible from the inside.

**The move:** The dangerous practitioner is the one who ships a polished prototype as if it were a production system. Say where the line is before you cross it.

*"Name the line before you ship."*

---

## MEASUREMENT · Headline numbers and the honest breakdown

### 11 · Headline accuracy is an assertion
**Why it goes wrong:** "90% accurate" lands as evidence, and nobody asks the rest of the sentence.

**The move:** 90% on which class, at what cost to the others? Never report an overall number without the per-class and per-group breakdown beneath it.

*"Headline accuracy is an assertion, not evidence."*

### 12 · A model without a threshold
**Why it goes wrong:** Evaluation without an acceptance rule can't fail, which means it can't pass either.

**The move:** State the threshold in the sentence: for this decision, good enough means this number, because this is the blast radius. And a changed threshold is a new decision to explain.

*"A model without a stated threshold is a demo, not an evaluation."*

### 13 · The worst-group gap
**Why it goes wrong:** The average hides the group the system fails.

**The move:** Compute accuracy per condition and per group. The worst-group gap — the spread between best and worst condition — is the honest headline.

*"The worst-group gap is the honest headline."*

### 14 · Adversarial testing
**Why it goes wrong:** Most testing asks "does it work on normal inputs?" — the conditions that actually bite are never tried.

**The move:** Ask the opposite: what inputs make it fail? A customer photographs the router in a dark cupboard at midnight, because that is when the fault showed up. A demo evaluated on the happy path has proven nothing about those conditions.

*"Break it on purpose, before someone else does it for you."*

### 15 · Small samples
**Why it goes wrong:** A perfect result on a handful of examples reads as dependability.

**The move:** A perfect score on three examples does not establish dependable performance, and a single successful test supports "it worked once", never "it is tested regularly".

*"A sample that cannot support the claim is an anecdote with a date."*

---

## RATINGS · The judgement about the evidence

### 16 · The defensible Partial
**Why it goes wrong:** Boards prefer clean ratings, and the auditor supplies the clean rating the evidence cannot carry.

**The move:** A defensible Partial says: this part works, this part does not, this part is unknown. It gives the board a decision — accept the gap, fund the fix, or investigate. A Met with no evidence gives comfort that has not been earned.

*"A defensible Partial is worth more than an unsupported Met."*

### 17 · Triangulation
**Why it goes wrong:** One source — a policy, an interview, a log — gets treated as the whole answer.

**The move:** Three evidence moves: inspect what is said, inquire what people believe, observe what the system recorded. Together they support a rating; alone, each is a claim, a belief or a partial record. If sources disagree, the disagreement is the finding.

*"If they disagree, the disagreement is the finding."*

### 18 · The limitation beside the rating
**Why it goes wrong:** Limitations get filed in an appendix nobody reads, far from the rating they qualify.

**The move:** Record the limitation beside the rating, plus one sentence on what would change it: "MFA moves to Met if the legacy exception is closed and the log gap is explained."

*"Limitations belong beside the rating."*

### 19 · Refusing to rate
**Why it goes wrong:** Thin evidence still pressures a rating, because a blank looks like failure.

**The move:** A good answer refuses to rate when the evidence is thin — and that refusal is itself a finding. Confidence is a delivery property, not a truth property.

*"A refusal to rate is a finding."*

---

## RECORDS · What you keep, and when you wrote it

### 20 · The proof brief, before building
**Why it goes wrong:** The reasoning gets reconstructed after the results are known, which is persuasion with extra steps.

**The move:** Write the brief before you build: intended use, affected people, baseline, acceptance rule with the blast radius, evaluation plan, data boundary, stop rule, evidence record.

*"Start the brief now. Don't reconstruct the reasoning after the results."*

### 21 · The dossier
**Why it goes wrong:** The evidence lives in twelve places and dies in none of them, so nothing can be defended.

**The move:** One cumulative dossier: brief · sources and boundaries · design · evaluation · review · decision and handover. The product of applied AI is not a model; it is a defensible judgement, and the dossier is where the defence lives.

*"The product is a defensible judgement."*

### 22 · The conversation log
**Why it goes wrong:** AI sessions get remembered as collaborations in which the assistant was right.

**The move:** Log per session: date, models, goal, the prompts that mattered, where the AI was wrong and how you corrected it, what you decided to trust and why — plus the unedited transcript. The unedited record is the integrity gate.

*"A demo persuades; a log proves."*

### 23 · The threshold sentence
**Why it goes wrong:** "Good enough" floats free of the decision, the number and the blast radius.

**The move:** One sentence per evaluation: "For [decision], good enough means [threshold], because [blast radius]." Then an accuracy figure measured once is a photograph — schedule the re-checks.

*"For this decision, good enough means this, because of this."*

---

**Anyone can demo AI. The edge is proving it works.**
