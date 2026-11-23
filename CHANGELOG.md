# Changelog — Decision Topology

Substantive changes affect doctrine or protocol; editorial changes clarify language.

## v1.3 — Canonical alignment (2026-11-20)

### Substantive amendments
- **01 — Standing Terminology:** replaced the misleading standing hierarchy with Direct Standing, Delegated Participation, and Institutional Representation; clarified cascade responsibility without transferring standing.
- **02 — Collective Decision Necessity:** distinguished Decision Necessity from permission; reclassified collective governance conditions as non-authorizing Collective Resolution Safeguards; exit and voice do not equal consent.
- **03 — Participation Authorization and Delegated Exercise:** distinguished exercise from authorization content; required valid, scoped, operative delegation and independent delegate exercise; tracked each standing-holder and each cascade stage.
- **04 — Authorization Status and Decision Status:** distinguished WITHHELD from genuinely UNAVAILABLE authorization; preserved the independent REQUIRED/Not Required Decision Status without changing the Permissibility Verdict; removed fictitious caretaker delegation.

### Migration from v1.2.1 (implementation changes)

This is a behavioral migration, not a rename. Implementations built on v1.2.1 must audit their decision rules and tests before claiming v1.3 compatibility.

| v1.2.1 implementation risk | Minimum v1.3 correction |
| --- | --- |
| Treating a representative, institution, or governing body as holding or transferring the affected person's standing | Track each affected standing-holder separately. Distinguish Direct Standing, Delegated Participation, and Institutional Representation; institutions do not hold standing. |
| Treating voting, governance safeguards, voice, exit, or necessity as collective authorization | Record these as constraints or context, not an authorization basis. Determine authorization for each affected standing-holder and closure. |
| Treating attendance, response, silence, abstention, or refusal as consent | Check both participation **exercise** and affirmative, closure-specific **authorization content**. A refusal remains WITHHELD. |
| Accepting delegation by assumption or through a caretaker's role | Verify prior, scoped, operative, revocable delegation and independent delegate exercise. Incapacity does not create delegation. |
| Reusing upstream consent for downstream effects | Reassess authorization for each newly affected standing-holder at each attributable cascade stage; upstream authorization does not transfer. |
| Collapsing urgency, structural unavoidability, or a required decision into permission | Output the independent **Permissibility Verdict** and, where applicable, **Decision Status**. REQUIRED can coexist with IMPERMISSIBLE; urgency is not an exception. |
| Treating a Defensive Exception as a consent or authorization route | Evaluate it as a distinct permissibility basis, only if all applicable safeguards pass; do not relabel affected people as consenting. |
| Treating unavailable authorization as withheld, or withheld as unavailable | Distinguish AUTHORIZED, WITHHELD, and genuinely UNAVAILABLE; do not classify merely unsought authorization as unavailable. |

**Minimum regression cases:** explicit refusal under time pressure; infant care without invented delegation; a majority-backed policy with dissenters; a multi-stage cascade with newly affected people; and a valid versus failed Defensive Exception. Check the canonical v1.3 specification for full conditions; this table is not a substitute for the normative text.

### Editorial and release corrections
- Removed terminology that incorrectly called Defensive Exception an “authorization route”; it is a distinct **permissibility basis**.
- Clarified closure-specific capacity in direct participation and accountable care without invented delegation.
- Updated README, citation metadata, and both decision worksheets to match the canonical protocol.
- Retained v1.2.1 PDFs and Markdown as historical artifacts, clearly marked as non-current in README.

---

All notable changes to this framework are documented here.

The format follows a chronological, versioned history.
Substantive changes affect concepts or protocol logic.
Editorial changes affect clarity only.

---

## v1.2.1 — Historical release (2025-12-24)

### Added
- Explicit section on **Ambiguity and Recursion**
- Section on **Framework Character** (judgment, normativity, completeness)

### Clarified
- Recursion bounded by closure itself
- Delay and indecision treated as closure-generating actions
- Defensive exception accounting (structural vs agent-specific)

### Status
- Originally labeled **Final Public Release** at publication. That title referred to the v1.2.1 edition, not to a permanent end of framework development. v1.3 supersedes it.
- Historical public release under **CC BY 4.0**

---

## v1.2

### Added
- **Structural Defensive Exception** with enhanced safeguards
- **Minimum Agency Threshold Test**
- Provisional vs Confirmed agent classification
- Commons and substrate protection rules
- Explicit animal standing clarification

### Changed
- Participation modality separated from standing (standing remains binary)

---

## v1.1

### Added
- Agent-relative closure weighting
- Default-to-Agent principle
- Mediated Standing Rule
- Minimum Disclosure Standard for irreversible closures
- Tamper-Evidence Principle
- Exit Viability Test
- Voice Viability Standards
- Sunset and review safeguard
- Representational closure check in Tier 1

---

## v1.0 — Initial Release

### Introduced
- Three primitives: Agent, Closure, Standing
- Single axiom
- Two hardenings (PVC, RCR)
- Six derivations
- Four-step decision protocol
- Defensive exception safeguards
- Domain applications
