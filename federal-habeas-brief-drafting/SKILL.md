---
name: federal-habeas-brief-drafting
description: Use whenever drafting, editing, reformatting, or reviewing a federal habeas corpus petition or Brief in Support under 28 U.S.C. § 2254 (state prisoner) or § 2255 (federal prisoner), or any related filing (response, reply, motion for evidentiary hearing, certificate of appealability). Trigger this even if the user just says "habeas brief," "§ 2254 brief," "petition for writ of habeas corpus," "AEDPA," or pastes a rough draft/outline of a ground for relief and asks to have it formatted, polished, or turned into "a real brief." Also trigger for questions about federal habeas document structure, AEDPA standard-of-review framing, exhaustion/procedural default argument structure, or Schlup/actual-innocence gateway argument structure, even outside the context of a specific brief.
---

# Federal Habeas Corpus Brief Drafting (28 U.S.C. § 2254 / § 2255)

This skill governs both the **document structure** and the **prose voice** for a professional federal habeas Brief in Support. The single most common failure mode is treating this like a general legal-writing task and defaulting to explanatory, narrated prose — a habeas brief in front of an experienced district judge must read like it was written by a seasoned appellate litigator who has done this hundreds of times, not like a study guide walking a reader through the reasoning.

**Before writing anything, read `references/prose-voice.md`.** Getting the voice wrong is the failure mode most likely to make a user reject the output outright, even when the legal content is correct.

## Document Skeleton

Assemble in this order. Do not skip a section; do not add sections not listed here without the user's request.

1. **Caption** — court name centered, party block (Petitioner v. the state officer with custody — the warden, not "State of ___," per Rule 2(a), Rules Governing § 2254 Cases), case number, document title in full caps ("BRIEF IN SUPPORT OF PETITION FOR WRIT OF HABEAS CORPUS UNDER 28 U.S.C. § 2254").
2. **Table of Contents** — every heading/subheading verbatim, with page numbers. Each Ground's point-heading should be a complete, argumentative sentence — read straight through, the TOC should function as an outline of the whole argument.
3. **Table of Authorities** — categorized (Cases; Constitutional Provisions; Statutes; Rules; Other Authorities), alphabetical within each category, page references, "passim" for scattered heavy use. Case names italicized exactly as in the body.
4. **Jurisdictional Statement** — short. § 2254(a)/§ 2241 basis, custody pursuant to a state judgment, venue, timeliness under § 2244(d)(1) if it's in play.
5. **Statement of the Case / Procedural History** — neutral, chronological: charges, verdict, sentence, direct appeal and disposition, state post-conviction proceedings and disposition, this filing. Save characterization for the Argument.
6. **Statement of Facts** — sourced to the record with pincites throughout. This is where credibility is built or lost — every material fact needs a citation.
7. **Standard of Review** — a standalone AEDPA section, written once, before the Grounds (see below).
8. **Argument** — organized as "GROUND ONE," "GROUND TWO," etc. (federal practice; do not use "Proposition," which is Oklahoma/state appellate usage, unless the filing is actually in state court). See internal structure below.
9. **Prayer for Relief** — formal: issuance of the writ, vacatur, evidentiary hearing if warranted, discovery if warranted, "such other relief as the Court deems just and proper." Do not request a Certificate of Appealability here — that's post-denial, under Rule 11.
10. **Certificate of Service** — date/manner of service on respondent and state AG; pair with a 28 U.S.C. § 1746 prison-mailbox declaration for pro se petitioners.

## Standard of Review Section (write this before touching the Grounds)

Must include, in this order:
- Quote 28 U.S.C. § 2254(d) directly (both prongs).
- Define "contrary to" vs. "unreasonable application" via *Williams v. Taylor*, 529 U.S. 362, 405–13 (2000).
- "Clearly established Federal law" = Supreme Court holdings as of the state-court decision (*Greene v. Fisher*, 565 U.S. 34 (2011)).
- The high bar: *Harrington v. Richter*, 562 U.S. 86, 103 (2011) — state decision must be "so lacking in justification that there was an error well understood and comprehended in existing law beyond any possibility for fairminded disagreement."
- Record limitation: *Cullen v. Pinholster*, 563 U.S. 170 (2011) — § 2254(d) review is confined to the state-court record.
- Factual findings: § 2254(e)(1) presumption of correctness, rebuttable only by "clear and convincing evidence."
- **Flag explicitly** any Ground that was never adjudicated on the merits in state court — those get *de novo* review, not AEDPA deference. Don't bury this; state it as its own sentence.

## Internal Structure of Each Ground (CREAC + AEDPA overlay)

1. **Point-heading**: one sentence, argumentative, states the violation and the theory (e.g., "GROUND TWO: TRIAL COUNSEL WAS CONSTITUTIONALLY INEFFECTIVE FOR FAILING TO INVESTIGATE AND PRESENT AN AVAILABLE ALIBI DEFENSE").
2. **Rule**: the controlling constitutional standard, full-cite on first use (*Strickland v. Washington*, 466 U.S. 668, 687 (1984); *Brady v. Maryland*, 373 U.S. 83 (1963); *Napue v. Illinois*, 360 U.S. 264 (1959); etc.).
3. **Application**: record facts, pincited, applied element-by-element. This is where the actual evidence lives — quotes, exhibit numbers, transcript cites. No summarizing away detail the user has already verified; no adding interpretive narration around a quote that isn't itself in the quote.
4. **AEDPA overlay** (for merits-adjudicated claims): argue specifically why the state court's resolution was *unreasonable*, not just wrong — this is the single most common gap in weak habeas briefs. Doubly-deferential framing for Strickland claims per *Richter*.
5. **Prejudice/materiality**: close on the governing prejudice standard — *Strickland*'s "reasonable probability of a different result"; Napue's more petitioner-favorable "any reasonable likelihood" of affecting the judgment; *Brecht v. Abrahamson*, 507 U.S. 619 (1993), "substantial and injurious effect" for collateral-review harmless error.

## Exhaustion, Default, and the Actual-Innocence Gateway

- State exhaustion affirmatively for each Ground (fairly presented to the state's highest court — *O'Sullivan v. Boerckel*, 526 U.S. 838 (1999)).
- Where default is a live issue: *Coleman v. Thompson*, 501 U.S. 722, 750 (1991) bars review absent cause-and-prejudice or a fundamental-miscarriage-of-justice showing. If post-conviction counsel's ineffectiveness is the cause, *Martinez v. Ryan*, 566 U.S. 1 (2012) — but flag *Shinn v. Ramirez*, 596 U.S. 366 (2022) candidly: it limits federal evidentiary development based on state PCR-counsel ineffectiveness under § 2254(e)(2).
- Gateway innocence (to reach a defaulted claim, not freestanding relief): *Schlup v. Delo*, 513 U.S. 298, 327 (1995) — "more likely than not that no reasonable juror would have found petitioner guilty beyond a reasonable doubt" in light of new evidence; *House v. Bell*, 547 U.S. 518 (2006) — holistic weighing of all evidence, old and new, admissible and inadmissible; *McQuiggin v. Perkins*, 569 U.S. 383 (2013) — equitable exception to the one-year bar, no diligence requirement, but unjustified delay bears on credibility of the new evidence.
- Distinguish gateway innocence from a freestanding *Herrera v. Collins*, 506 U.S. 390, 417 (1993) claim (assumed-but-never-squarely-held to be cognizable) if the user wants to preserve one.

## Formatting Mechanics

**These vary by district — confirm current local rules before filing. Do not assume the numbers below transfer to a different court.**

For the Western District of Oklahoma specifically (confirm against the current Local Rules before filing, as these are periodically amended):
- Type: 13-point minimum (not 12 — this is higher than most districts' floor), including footnotes (LCvR7.1(e)).
- Margins: one inch minimum, all sides.
- Spacing: double-spaced, one side of the page, 8½×11 (LCvR5.2).
- Page limit: 25 pages for briefs generally (30 for summary-judgment opening/response) absent leave of court, stated as a specific requested page count (LCvR7.1(e)). Capital habeas gets a separate, much larger allowance under General Order 24-3 (petition/opening 100 pages).
- If a filing plus exhibits exceeds 40 pages, a paper courtesy copy is typically required.
- § 2254 filing fee is $5.00, or IFP — § 2254/§ 2241 IFP is NOT governed by the PLRA (unlike ordinary prisoner civil-rights IFP).

## Citation Conventions

- Case names italicized in both full and short form.
- Full cite on first use: *Strickland v. Washington*, 466 U.S. 668, 687 (1984). Short form after: *Strickland*, 466 U.S. at 694.
- Pincite every specific proposition — never cite just the first page of a case for a specific holding.
- *Id.* only for the immediately preceding single authority; not after a string cite.
- OCCA/state cites: regional reporter is sufficient (no parallel cite required) — e.g., *Anderson v. State*, 130 P.3d 273, 277–83 (Okla. Crim. App. 2006).
- Define record abbreviations at first use and hold them constant: "(Tr. __)" for trial transcript, "(O.R. __)" for original record, "(Ex. __)" for exhibits, "(Prelim. Hr'g Tr. __)" / "(PO Hr'g Tr. __)" etc. for other hearing transcripts. **Convert exhibit-style citations to the actual transcript/pincite format whenever the underlying material is testimony, not a document** — this is a frequent correction needed when working from a party's rough notes.

## Working From a User's Rough Draft (this comes up constantly)

When a user pastes their own draft of a ground and asks to have it "cleaned up," "formatted," or "converted to a brief":

- **Do not add interpretive narration, transitional scaffolding, or explanations of your own reasoning inside the document.** No "three things place this in context," no "this shows," no "considered holistically." State the rule, state the fact with its citation, move to the next point. Let the citation and the quote do the work.
- **Do not soften, hedge, or insert unrequested concessions.** A brief is one-sided advocacy by design; inserting a qualifier the user didn't ask for reads as building the other side's argument for them.
- **Do not strip factual detail for length or "brief economy" unless the user says to.** Pro se and small-firm habeas petitioners frequently have unlimited pages via a motion for leave to file oversized brief (see Formatting Mechanics) and specifically do NOT want compression — always ask, or check for signals, before assuming length is a constraint.
- **Preserve the user's argument structure and analytical sequence** unless asked to reorganize it. Converting their content into a different structure "for consistency" without being asked is a common overstep — verify citations, convert exhibit refs to proper pincites, match the surrounding document's heading conventions, and stop there.
- **Verify every citation the user includes** (real case, right court, right year, right proposition) before incorporating it — a wrong or fabricated citation is a serious, credibility-destroying error in a real filing. Use available search tools to check anything not independently well-known.

## Sample Sources and Deeper Formatting Notes

See `references/samples-and-caveats.md` for links to real, publicly accessible § 2254 petitions/memoranda and USCOURTS opinions that model this structure, plus jurisdiction-specific caveats and known limitations of this guidance (e.g., which sample sources predate *Richter*/*Pinholster*/*Shinn* and need their AEDPA framing updated before use as a model).
