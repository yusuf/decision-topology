# Decision Topology

**A Framework for Ethics Under Irreversibility**  
**Current specification: v1.3**

Decision Topology is a minimal operational ethics framework for choices that close agents' accessible futures. Its architecture is **one axiom, three primitives (Agent, Closure, Standing), and a four-step decision protocol**.

## Read the framework

- [Canonical specification v1.3](Decision_Topology_Framework_v1.3.md) (Markdown; authoritative)
- [Version history and v1.2.1 → v1.3 migration guide](CHANGELOG.md)
- [v1.3 release notes](docs/v1.3-release-notes.md)
- [Implementation regression cases](examples/regression/README.md)
- [Versioning and compatibility guidance](docs/versioning.md)
- [Report an implementation issue or test result](https://github.com/yusuf/decision-topology/issues/new)
- [Simple decision worksheet](templates/simple_decisions.md)
- [Complex decision worksheet](templates/complex_decision.md)

**Version-pinned distribution:** [v1.3 release page](https://github.com/yusuf/decision-topology/releases/tag/v1.3) · [Tagged canonical specification](https://github.com/yusuf/decision-topology/blob/v1.3/Decision_Topology_Framework_v1.3.md). Use the tagged specification for reproducible citations and implementations.

The original [v1.2.1 Markdown](Decision_Topology_Framework_v1.2.1.md) and [v1.2.1 PDF](Decision_Topology_Framework_v1.2.1.pdf) remain available **as historical editions, not current guidance**. The existing [one-page PDF](One_Page_Framework_Summary.pdf) also predates v1.3 and is retained for historical reference only; **do not distribute it as the v1.3 summary**. For the current one-page summary, see **Section 21** of the canonical v1.3 Markdown.

## Core axiom

> An action is impermissible if it creates closure, material or representational, over an agent's future states without that agent's valid participation, unless the closure prevents a greater non-participatory closure affecting another agent and the preventive closure is proportional.

## What changed in v1.3

1. **Standing is not an institutional hierarchy.** Direct standing belongs to agents. Delegated participation transfers exercise, never standing; institutional representation is not authorization.
2. **Collective safeguards constrain but do not authorize.** Participation approximation, voice, exit, and decision necessity cannot manufacture consent. Necessity to decide is not permission to close.
3. **Exercise is not authorization.** A refusal, abstention, silence, or representative process does not itself authorize closure. Direct participation and operative delegation must be checked per affected standing-holder and per cascade stage.
4. **Authorization Status and Decision Status are distinct.** WITHHELD is not UNAVAILABLE. Where authorization is genuinely unavailable, a decision may be REQUIRED yet the closure IMPERMISSIBLE. This does not introduce a new permissibility route.

**Two distinct bases must not be conflated:** valid direct/delegated participation provides *authorization*; a satisfied Defensive Exception can provide a separate *basis of permissibility without authorization*. Urgency alone supplies neither.

## Protocol

1. Map direct, representational, and cascading closures, identifying each standing-holder.
2. Verify participation, including opportunity, capacity, exercise, authorization content, and any operative delegation; classify authorization status per closure.
3. Where participation is invalid, test the appropriate Defensive Exception with its safeguards.
4. Record the **Permissibility Verdict**, and where applicable the independent **Decision Status**. Document unresolved impermissibility rather than relabeling it as consent.

Decision Topology sets an ethical floor; it does not optimize among permissible choices, replace virtues or purposes, or remove the need for judgment.

## License and citation

Licensed under [CC BY 4.0](LICENSE). Cite: **Yusuf Abdulla Shunan, _Decision Topology: A Framework for Ethics Under Irreversibility_, v1.3**. Machine-readable metadata: [CITATION.cff](CITATION.cff).

*One axiom. Three primitives. Four steps. Necessity to decide is not permission to close.*

## Implementations and feedback

If you build a decision tool using DT, please [open an issue](https://github.com/yusuf/decision-topology/issues/new) with the DT version, use case, expected result, observed result, and a minimal reproducible scenario. Remove private or identifying information before posting. Report protocol ambiguity and disagreements as well as software defects. An issue is a request for review, not an endorsement of the implementation.
