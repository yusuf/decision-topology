# **DECISION TOPOLOGY**

## **A Framework for Ethics Under Irreversibility**

Yusuf Abdulla Shunan
[yusufshunan.com](http://yusufshunan.com)

### **Complete Specification v1.3**

---

**TABLE OF CONTENTS**

1. Part I: Foundations
   1. The Core Problem
   2. The Three Primitives
   3. The Single Axiom
   4. The Two Hardenings
   5. The Six Derivations
2. Part II: Operations
   1. The Decision Protocol
   2. Tiered Implementation
   3. Closure Analysis Templates
3. Part III: Translation Layer
   1. Mapping Traditional Moral Vocabulary
   2. Why Traditional Concepts Feel Right
4. Part IV: Applications
   1. Business Ethics
   2. Personal Ethics
   3. Policy Ethics
   4. AI Ethics
5. Part V: Safeguards
   1. The Seven Defensive Exception Safeguards
   2. Structural Defensive Exception
   3. Conflict Resolution
6. Part VI: Grounding
   1. Metaphysical Grounding
   2. Theological Grounding
   3. Framework Character
7. Part VII: Reference
   1. One-Page Framework Summary
   2. Quick Validity Checklist
   3. Glossary
8. Appendix: Version History

---

# **PART I: FOUNDATIONS**

## **1. The Core Problem**

Every decision closes futures. Before an action, many states remain accessible. After the action, some become permanently or temporarily inaccessible. The ethical question is not "Is this harmful?" but:

**Whose futures are being closed, and did they participate in the closing?**

This reframes ethics as **topology management**—the structure of possibility space and who has standing to alter it.

Traditional ethical frameworks assume reversibility: time to reflect, capacity to revise, opportunity to make amends. That assumption no longer holds universally. We now make decisions at scales where consequences propagate faster than deliberation, where the gap between action and outcome approaches zero, and where entire categories of effects cannot be undone.

Decision Topology addresses this context directly. It provides a minimal constraint system—one axiom, three primitives, four operational steps—from which all ethical evaluation derives.

### **What This Framework Does**

- Identifies impermissible actions (those imposing non-participatory closure)
- Provides operational protocols for decision evaluation
- Scales from individual choices to civilizational policy
- Works for both human and machine decision-makers

### **What This Framework Does Not Do**

- Optimize among permissible options (it defines the floor, not the ceiling)
- Replace virtue, meaning, or purpose (it constrains, not guides)
- Resolve all ethical questions (it addresses closure, not flourishing)

---

## **2. The Three Primitives**

The framework requires only three foundational concepts. All ethical analysis reduces to these primitives and their relationships.

### **Primitive 1: Agent**

An entity is an **agent** if it possesses:

| Capacity          | Definition                                        |
| ----------------- | ------------------------------------------------- |
| **Phenomenology** | Capacity to experience states as better or worse  |
| **Agency**        | Capacity to take actions that alter future states |
| **Anticipation**  | Capacity to represent future states to itself     |

#### Minimum Agency Threshold Test

To determine whether an entity crosses the agency threshold, apply three questions:

| Question                                  | What It Tests                                                                                                                                                                                     |
| ----------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1. Self-referential future models**     | Does the entity maintain models of its *own* future states (not just world-prediction)? Does it represent itself as persisting through time with states that matter to it?                        |
| **2. Persistent preference organization** | Does the entity demonstrate stable preferences that persist under environmental change? Are these preferences organized (hierarchical, trade-off-structured) rather than merely reactive?         |
| **3. Valenced experience**                | Is there credible evidence of phenomenology—states experienced as better or worse from a point of view? Or is the entity in pure "as-if" territory (behavioral mimicry without inner experience)? |

**Scoring:**

| Result                     | Classification                                                           |
| -------------------------- | -------------------------------------------------------------------------- |
| Clear YES on all three     | **Confirmed agent** — full protocol applies                              |
| YES on 1-2, uncertain on 3 | **Provisional agent** — apply full protocol; monitor for evidence        |
| Clear NO on any            | **Non-agent** — no standing (but check mediated standing for substrates) |
| Uncertain across multiple  | **Default-to-agent** — treat as provisional agent                        |

**Provisional vs. Confirmed Agent:**

- **Confirmed agents:** Full participation requirements; no exceptions
- **Provisional agents:** Full participation requirements; system designers must build in monitoring for agency confirmation; closure decisions should be reversible where possible pending confirmation

#### Standing Is Binary, Not Scalar

**Critical clarification:** An entity either crosses the agency threshold or does not. Above the threshold, all agents have **equal standing** over their own futures, regardless of anticipation sophistication.

- A human with cognitive disabilities who can experience suffering, make choices, and anticipate tomorrow has **full standing**
- An animal that experiences pain, acts on preferences, and anticipates has **full standing**
- The degree of anticipation capacity is irrelevant once the threshold is crossed
- This blocks paternalism as a structural move: "I anticipate better than you" does not grant standing over another's futures

#### Participation Modality vs. Standing

Standing is binary and equal for all agents above threshold. **Participation modality**—how an agent exercises participation—varies by capacity:

| Agent Type                  | Participation Modality                                                                             |
| ---------------------------- | ---------------------------------------------------------------------------------------------------- |
| Adult humans                | Explicit consent, contracts, verbal/written agreement                                              |
| Children                    | Developing capacity; direct participation for closures within their evaluative reach; residual participation (assent, refusal, avoidance) for others; accountable caretaker action where authorization is genuinely unavailable — see Section 6 |
| Cognitively impaired humans | Direct participation for closures within their evaluative reach; residual participation (observable preference) for others; accountable guardian action where authorization is genuinely unavailable — see Section 6 |
| Animals                     | Residual participation via observable preference/avoidance for closure-specific matters; accountable caretaker action where authorization is genuinely unavailable — see Section 6 |
| AI systems (if agents)      | Explicit programmatic consent; preference revelation; refusal capacity                             |

**Key principle:** Different modalities do not imply different standing. A dog's standing over its bodily futures is equal to a human's standing over theirs. The *method* of participation differs; the *weight* of standing does not.

**On caretaker and guardian action.** Where a standing-holder cannot presently authorize a closure and no valid prior authorization or delegation governs it, an accountable caretaker's action on their behalf is not itself an exercise of that standing-holder's participation, delegated or otherwise — the standing-holder never performed a delegating act. Incapacity does not create authority; it can make authorization unavailable. Those are not the same proposition. See Section 6, Authorization Status, for how such closures are classified.

#### Default-to-Agent Principle

**When agency threshold is uncertain, treat the entity as a provisional agent for closure analysis.**

**Rationale:** This prevents ethical false negatives—failing to recognize an agent and thereby permitting non-participatory closure. The cost of false positives (treating non-agents as agents) is lower than the cost of false negatives (treating agents as non-agents).

**Application:** In cases of uncertainty about phenomenology, agency, or anticipation, apply the full participation requirement. Monitor for evidence that clarifies agent status.

#### Boundary Cases

| Entity Type  | Agent Status         | Reasoning                                                                                      |
| ------------ | --------------------- | ------------------------------------------------------------------------------------------------ |
| Humans       | Confirmed agent      | Full phenomenology, agency, anticipation                                                       |
| Animals      | Confirmed agent      | Possess phenomenology, agency, anticipation; standing is equal; participation modality differs |
| AI systems   | Apply threshold test | Must demonstrate self-referential models, persistent preferences, credible phenomenology       |
| Corporations | Not agents           | Structures containing agents; no phenomenology                                                 |
| Ecosystems   | Not agents           | Contain agents and mediate futures; see Mediated Standing Rule                                 |

---

### **Primitive 2: Closure**

A **closure** is a reduction in accessible future states caused by an action.

#### Closure Types

| Type                         | Definition                                        | Example                                  |
| ----------------------------- | ---------------------------------------------------- | ------------------------------------------ |
| **Material closure**         | Physical futures become inaccessible             | Injury closes mobility futures           |
| **Representational closure** | Agent's model of possibility space is distorted  | Deception closes informed-choice futures |
| **Reversible closure**       | Futures temporarily inaccessible but recoverable | Temporary confinement                    |
| **Irreversible closure**     | Futures permanently inaccessible                 | Death, permanent injury                  |
| **Partial closure**          | Some futures closed, others remain               | Career choice closes some paths          |
| **Total closure**            | All but one future closed                        | Execution                                |

#### Closure Measurement

Closure is assessed through comparative evaluation, not precise calculation:

| Dimension         | Assessment Method                                                     |
| ------------------ | ------------------------------------------------------------------------ |
| **Magnitude**     | Severity × Breadth × Duration (qualitative ranking across dimensions) |
| **Reversibility** | Cost to restore + Time to restore + Probability of restoration        |
| **Cascade scope** | Number of downstream agents affected + Depth of dependency chain      |

**Measurement Dimensions:**

- Bodily integrity
- Mobility/movement
- Economic/resource access
- Relational/social
- Informational/knowledge
- Temporal/lifespan
- Agential/choice-making capacity

#### Agent-Relative Weighting Principle

**Closure is evaluated relative to the affected agent's own future model and dependency structure, not the evaluator's preferences or external standards.**

**Rationale:** This blocks the failure mode where powerful parties downplay closures that are catastrophic for the affected agent but trivial from the evaluator's position.

**Operational test:** Would the affected agent, with full information and unimpaired capacity, assess this closure as significant to their future trajectory?

---

### **Primitive 3: Standing**

**Standing** is the relationship between an agent and a closure affecting their future states.

#### Standing Conditions

An agent has standing over a closure if:

1. The closure affects futures the agent could have occupied
2. The agent had capacity to anticipate those futures

#### Standing Properties

| Property                 | Implication                                                            |
| -------------------------- | -------------------------------------------------------------------------- |
| **Non-transferable**     | Standing cannot be given away; only participation can be delegated. The delegating agent retains standing; if the delegate acts against the agent's interests, the agent retains standing to contest the outcome. Delegation of participation is always revocable — the standing it exercises was never transferred. |
| **Persistent**           | Standing persists through cascade chains                               |
| **Distance-independent** | Standing is not diminished by distance from initiating action          |
| **Binary**               | All agents above threshold have equal standing; no scaling by capacity |

#### Mediated Standing Rule

**If a non-agent system is a necessary substrate for large classes of agent futures (e.g., air, water, climate stability, biodiversity), closures to that substrate count as closures to those agents' futures.**

**Application:**

| Substrate Closure          | Counts As                                                          |
| ---------------------------- | ---------------------------------------------------------------------- |
| Ecosystem degradation      | Closure of futures for all agents dependent on that ecosystem      |
| Climate destabilization    | Closure of futures for all agents affected by climate              |
| Infrastructure destruction | Closure of futures for all agents dependent on that infrastructure |

**Standing attribution:** Agents have standing over substrate closures proportional to their dependency on the substrate. This is not "ecosystem rights"—it is recognition that substrate closure is agent closure. Mediated Standing identifies whose futures are at stake; it does not by itself establish that any particular closure was authorized. Authorization is determined separately, under Step 2 and Step 3 of the Decision Protocol.

---

## **3. The Single Axiom**

**An action is impermissible if it creates closure—material or representational—over an agent's future states without that agent's valid participation, unless the closure prevents a greater non-participatory closure affecting another agent, and the preventive closure is proportional to what it prevents.**
This single statement is the complete ethical constraint. Everything else derives from unpacking it.

### **Axiom Components**

| Component                    | Meaning                                           |
| ------------------------------ | ---------------------------------------------------- |
| **The prohibition**          | Non-participatory closure is impermissible        |
| **The scope**                | Both material and representational closure count  |
| **The validity requirement** | Participation must be valid (unimpaired capacity) |
| **The exception**            | Defensive closure preventing greater harm         |
| **The bound**                | Defensive closure must be proportional            |

**On the meaning of impermissibility.** IMPERMISSIBLE marks a closure that lacks a valid basis of permissibility under this axiom — either through participation or a satisfied Defensive Exception. It is not, by itself, a claim that the action must never be performed under any circumstance: where Decision Necessity independently requires a choice among unavoidable closures (see Section 6), the selected closure may be simultaneously required as a Decision Status and non-authorized as a Permissibility Verdict. This clarification does not extinguish responsibility for prior actions that created or worsened the necessity — classification of a later decision as required never launders an earlier decision that produced it. See Section 6, Step 4, for the operational architecture.

### **What the Axiom Prohibits**

- Closing an agent's futures without their participation
- Distorting an agent's model of their futures (representational closure)
- Claiming participation when capacity was impaired
- Disproportionate defensive closures

### **What the Axiom Permits**

- Closure with valid participation (via appropriate modality for agent type)
- Self-directed closure (agent closing their own futures)
- Proportional defensive closure preventing greater non-participatory closure
- Closure of non-agents (objects without standing)

---

## **4. The Two Hardenings**

The axiom requires two structural specifications to be complete and resistant to exploitation.

### **Hardening 1: Participation Validity Constraint (PVC)**

**Participation is invalid if the agent's capacity to anticipate, refuse, or modify the closure was materially impaired.**

#### Material Impairment Conditions

| Impairment Type                 | Definition                                                           | Detection Question                            |
| ---------------------------------- | ------------------------------------------------------------------------ | ------------------------------------------------ |
| **Information asymmetry**       | Agent lacked access to material facts about the closure              | Were material facts available and accessible? |
| **Deception**                   | Agent received false representation of closure or consequences       | Was representation accurate?                  |
| **Omission**                    | Material facts were withheld that would have altered participation   | Would disclosure have changed the decision?   |
| **Coercion**                    | Threats made non-participation unreasonably costly                   | Were alternatives genuinely available?        |
| **Dependency trap**             | Prior position was manipulated to manufacture apparent participation | Was dependency artificially created?          |
| **Time pressure**               | Insufficient time to anticipate and evaluate the closure             | Was time proportional to closure magnitude?   |
| **Representation manipulation** | Agent's model of future states was deliberately distorted            | Was agent's anticipation capacity targeted?   |

**Key principle:** Participation is a **capability condition**, not merely a behavioral event. "They clicked accept" is not valid participation if capability was impaired — and, symmetrically, an agent's actual exercise of a modality does not by itself establish that the content of that exercise authorized the closure in question. Whether an exercise occurred and what that exercise authorized are two separate questions; both must be affirmatively established. See Step 2 of the Decision Protocol for the operational test.

#### Participation Validity Across Modalities

For agents with non-standard participation modalities, two distinct things must be separated: whether the standing-holder's own residual participation (assent, refusal, avoidance) was honored for closures within their evaluative reach, and, separately, whether an accountable caretaker acted well or badly where authorization was genuinely unavailable. Acting well does not convert the caretaker's action into the standing-holder's own participation — it remains Authorization Unavailable, assessed under Section 6, and the quality markers below describe accountable versus self-dealing caretaker conduct, not a form of consent.

| Agent Type           | Sound Residual Participation / Accountable Caretaker Conduct                                   | Impaired Participation / Self-Dealing Caretaker Conduct                          |
| ---------------------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| Animals              | Clear preference signals honored for closure-specific matters; caretaker acting in animal's interest, accountable, and documented where authorization is unavailable | Ignoring distress signals, overriding clear avoidance, caretaker self-dealing   |
| Children             | Age-appropriate explanation, direct assent honored where the child has evaluative capacity for that closure; caretaker accountable to the child's trajectory where authorization is unavailable | No explanation, overriding a child's valid closure-specific refusal, caretaker self-dealing |
| Cognitively impaired | Observable preference honored for closure-specific matters; guardian accountable to the agent's interest, documented, where authorization is unavailable | Guardian self-dealing, ignoring a valid closure-specific refusal                 |

#### Minimum Disclosure Standard for Irreversible Closures

**For irreversible closures, valid participation requires provision of a baseline participation packet.**

**Required Contents:**

| Element                      | Description                                                                     |
| ------------------------------ | ------------------------------------------------------------------------------------ |
| **Key risks**                | Worst-case outcome and most likely outcome                                      |
| **Reversibility assessment** | Whether restoration is possible, and at what cost                               |
| **Cascade obligations**      | Who bears responsibility for downstream closures                                |
| **Exit/recourse options**    | What alternatives exist; what recourse is available if unexpected effects occur |

**Application:** This standard applies to all Tier 3 decisions and any Tier 2 decision involving irreversible closure. Absence of this packet creates a rebuttable presumption of participation impairment via information asymmetry.

#### Tamper-Evidence Principle

**Participation evidence must be archivable, reviewable, and tamper-resistant.**

**Requirements:**

- Participation records must be created **contemporaneously** with the participation event
- Records must be stored in a manner **resistant to post-hoc modification**
- Records must be **accessible** for review by affected agents and authorized auditors
- Absence of tamper-resistant records for high-stakes closures creates a rebuttable presumption of invalid participation

**Rationale:** Without this principle, powerful parties can manufacture participation evidence after the fact.

#### Burden of Proof Rules

| Context                     | Burden Allocation                                                                         |
| ------------------------------ | ------------------------------------------------------------------------------------------- |
| **Ordinary transactions**   | Presumption of valid participation unless impairment is demonstrated                      |
| **Asymmetric power**        | Burden shifts to more powerful party to demonstrate non-impairment                        |
| **Irreversible closures**   | Heightened scrutiny; ambiguity resolves against closure                                   |
| **Institutional contexts**  | Pattern evidence admissible (systematic impairment across similar cases)                  |
| **Non-standard modalities** | Burden on party claiming valid participation to demonstrate appropriate modality was used |

---

### **Hardening 2: Representational Closure Recognition (RCR)**

**An agent experiences closure not only when futures are removed, but when false representations force choices within a distorted possibility space.**

**Why this matters:** Without RCR, "reversible but wrong" acts escape detection. A lie that causes no material cascade still imposes closure—the agent made decisions within a false topology.

#### Representational Closure Types

| Type                       | Mechanism                                              | Example                              |
| ----------------------------- | ---------------------------------------------------------- | ---------------------------------------- |
| **Direct deception**       | False statements about state of world                  | Fraud                                |
| **Omission**               | Withholding material information                       | Concealment of defects               |
| **Distortion**             | Systematically skewed information                      | Algorithmic manipulation             |
| **Recursive distortion**   | Corrupting agent's model of their own states           | Gaslighting                          |
| **Anticipation hijacking** | Replacing agent's future-models with manufactured ones | Propaganda, manipulative advertising |

#### Why Representational Closure Matters

Traditional harm-based frameworks struggle with deception that causes no material damage. Decision Topology handles this cleanly:

- The agent's **model of possibility space** is itself a future-relevant state
- Distorting that model **closes the future** in which the agent makes informed choices
- This is closure even if other futures remain materially open

---

## **5. The Six Derivations**

From the axiom and hardenings, six principles derive. These are not additional axioms—they are logical consequences of the core constraint.

### **D1: Participation Requirement**

Closures affecting an agent require that agent's valid participation via appropriate modality. Valid participation requires unimpaired capacity to anticipate, refuse, or modify, **and** requires that the content of the agent's exercise of that modality actually authorize the closure in question — an exercise occurring is not, by itself, sufficient. See Step 2 for the operational test distinguishing exercise from authorization.

**Implication:** No closure without participation. No participation without capacity. Modality must match agent type. Exercising a modality and authorizing a closure are related but distinct requirements, both of which must be satisfied.

### **D2: Representational Standing**

Agents have standing over their representational states. Distorting an agent's model of possibility space is closure, even without material state change.

**Implication:** Deception is a violation, not merely a harm.

### **D3: Proportionality**

Defensive closures (those preventing greater non-participatory closures) are bounded by what they prevent. Imposing greater closure to prevent lesser closure is impermissible.

**Implication:** Defense cannot exceed offense. The cure cannot be worse than the disease.

### **D4: Cascade Responsibility**

The agent initiating a closure bears responsibility for downstream closures attributable to that initiating action until the relevant cascade stabilizes. Operational responsibilities may be allocated or delegated before initiation, but the standing of affected agents does not transfer, and delegation does not by itself extinguish the initiator's responsibility.

**Implication:** Responsibility does not end when the initiating action is complete. "Fire and forget" is not permitted. Delegating execution or assigning downstream duties does not erase the standing of affected agents or automatically remove the initiator from the responsibility chain.

### **D5: Irreversibility Weighting**

Irreversible closures require stronger participation validity than reversible ones. Permanent closure of futures demands more robust verification of unimpaired participation.

**Implication:** The higher the stakes, the higher the validity bar.

### **D6: Delegation Asymmetry**

Participation may be delegated to another agent. Standing cannot. The delegating agent retains standing; the delegate exercises participation on their behalf.

**Practical implication:** When delegation occurs: (1) the delegating agent retains all standing — only the exercise of participation transfers to the delegate; (2) a valid delegation may authorize a class of future decisions rather than requiring the standing-holder to anticipate each downstream closure individually, provided the delegation establishes a sufficiently intelligible decision envelope — through disclosed scope, limits, priorities, or comparable standards — that a later exercise can be assessed as within or outside what was delegated; indeterminate authority ("whatever the delegate thinks appropriate") does not establish an adequate decision envelope and therefore cannot authorize a downstream closure through delegation; (3) for a given downstream closure, it is the delegate's own opportunity, capacity, and exercise — not the standing-holder's — that must be valid; standing itself never moves; (4) the delegate's authority is bounded by the delegation and accountable to the delegating agent's interests — self-dealing invalidates the delegated participation; (5) because standing remains with the delegating agent, delegation remains revocable, and whether a prior delegation remains operative for a particular closure — including where the standing-holder has expressed a timely, specific refusal before the closure takes effect — is evaluated under Step 2 of the Decision Protocol. Where a delegate acts for multiple standing-holders, this authority is agent-relative: valid delegation by one standing-holder does not establish delegation by another.

**Implication:** You can authorize someone to participate for you. You cannot give away your standing. A representative or institution acting on behalf of agents who never individually delegated to it does not thereby hold delegated participation under D6 — it holds, at most, institutional representation, which constrains and informs but does not itself authorize closure (see Section 17).

---

# **PART II: OPERATIONS**

## **6. The Decision Protocol**

For any proposed action, apply the following four-step protocol.

### **Step 1: Map Closures**

#### 1a. Identify Material Closures

- What physical, economic, temporal, or social futures become inaccessible?
- For each affected agent, specify which futures close
- Assess magnitude using agent-relative weighting

#### 1b. Identify Representational Closures

- Does this action distort any agent's model of possibility space?
- Does it create, rely on, or perpetuate false representations?
- Does it hijack anticipation through manipulation?

#### 1c. Measure Closure Properties

| Property          | Assessment                                                                 |
| -------------------- | ------------------------------------------------------------------------------ |
| **Magnitude**     | How much of the agent's future space is closed? (Use dimensional analysis) |
| **Reversibility** | Can closed futures be restored? At what cost? In what time?                |
| **Cascade scope** | What subsequent closures does this initiate? How far?                      |

#### 1d. Map Affected Agents

- List all agents experiencing closure (direct and cascade)
- Apply Minimum Agency Threshold Test for uncertain entities
- Classify as confirmed agent, provisional agent, or non-agent
- For each agent, specify their standing relationship to the closure
- Apply Mediated Standing Rule for substrate closures

---

### **Step 2: Verify Valid Participation**

For each agent experiencing closure, assess:

#### 2a. Identify Appropriate Participation Modality

| Agent Type           | Appropriate Modality                          |
| ----------------------- | -------------------------------------------------- |
| Adult humans         | Explicit consent                              |
| Children             | Direct assent where evaluative capacity exists for the closure; otherwise residual preference plus accountable caretaker action where authorization is genuinely infeasible (Authorization Status: UNAVAILABLE — see 2e) |
| Animals              | Residual observable preference/avoidance for closure-specific matters, plus accountable caretaker action where authorization is genuinely infeasible (Authorization Status: UNAVAILABLE — see 2e) |
| Cognitively impaired | Direct assent where evaluative capacity exists for the closure; otherwise observable preference plus accountable guardian action where authorization is genuinely infeasible (Authorization Status: UNAVAILABLE — see 2e) |
| Provisional agents   | Most restrictive applicable modality          |

#### 2b. Opportunity

- Did the agent have opportunity to anticipate this closure?
- Was the closure foreseeable given available information?

#### 2c. Capacity (Check All Seven Impairment Conditions)

| Condition                   | Check                                            |
| ------------------------------ | ---------------------------------------------------- |
| Information asymmetry       | Did they have access to material facts?          |
| Deception                   | Were they given accurate representations?        |
| Omission                    | Were material facts disclosed?                   |
| Coercion                    | Were they free from threats?                     |
| Dependency trap             | Was their position not artificially manipulated? |
| Time pressure               | Did they have adequate time?                     |
| Representation manipulation | Was their model of futures not distorted?        |

#### 2d. Determine Authorization Basis

Even with appropriate modality, genuine opportunity, and unimpaired capacity, participation requires that the affected agent's valid participation actually **authorize** the specific closure being evaluated. An exercised modality is not, by itself, authorization — an agent may exercise an available modality (voting, responding, acting) without the content of that exercise constituting consent to the closure. This step asks a single governing question:

> *Is this closure authorized by the affected agent's valid participation?*

Determine the basis through one of three branches.

**Branch 1 — Direct Participation.** Applies when the standing-holder is the one exercising participation now, for this closure.

- *Exercise:* Did the agent do something via the appropriate modality? (Yes/No)
- *Authorization Content:* Does the content of that exercise constitute affirmative consent to this specific closure, under the modality identified in 2a? (Yes/No)

Both must be Yes. An exercise with negative or unspecified content (explicit refusal; deliberate abstention) satisfies Exercise but not Authorization Content, and does not establish valid participation for this closure. Absence of any exercise (silence, non-response) satisfies neither.

**Capacity gate for direct participation.** Branch 1 requires closure-specific evaluative capacity under Steps 2a–2c. Observable preference or assent is evidence to consider, but where that capacity is genuinely absent it does not manufacture authorization. Caretaker action in such cases is accountable action under Authorization Status: UNAVAILABLE, not delegated participation; the separate Defensive Exception and Decision Status tests still apply.

**Branch 2 — Delegated Participation (D6).** Applies when a representative or delegate is exercising participation on the standing-holder's behalf under a prior delegation. Standing remains with the standing-holder throughout; only the exercise of participation has been delegated. Run in order — a No at any step ends this branch for this standing-holder:

1. Did the standing-holder validly authorize the original delegation — appropriate modality, genuine opportunity, unimpaired capacity, actual exercise, and authorization content? (Yes/No)
2. Does the delegation establish a sufficiently intelligible decision envelope — through disclosed scope, limits, priorities, or a conflict-resolution rule — that this specific closure can be assessed as within or outside it? (Yes/No)
3. Does the specific closure fall inside that envelope? (Yes/No)
4. Is the delegation still operative — not fully revoked, and not suspended by a timely, specific pre-effect refusal? (Yes/No)
5. Does the delegate — not the standing-holder — separately satisfy Opportunity, Capacity, and Exercise with respect to this specific closure? (Yes/No)
6. Is the delegate acting faithfully and accountable to the standing-holder's interest, rather than the delegate's own interest or another party's interest? (Yes/No)

If all six are Yes, valid participation is established on the standing-holder's behalf via delegation.

*On present refusal against an operative delegation:* Post-hoc dissatisfaction after a closure has taken effect does not retroactively invalidate an exercise that was valid when the closure occurred. Full revocation of a delegation terminates delegated authority prospectively at any time, since standing was never transferred. A specific refusal reaching the delegate before the closure takes effect may suspend delegated authority for that closure: where the delegation validly and specifically excluded case-by-case override, that term ordinarily governs and a non-specific objection does not suspend it; but for highly irreversible closures, D5's requirement of stronger verification means reliance on the earlier delegation alone does not satisfy that heightened requirement where a competent standing-holder presently and explicitly contradicts it before the closure takes effect.

**Branch 3 — Neither.** No valid participation authorization exists via Branch 1 or Branch 2 for this standing-holder and this closure. Proceed to Step 3.

*Plural standing-holders:* Branches 1 and 2 are evaluated separately for each affected standing-holder or each materially distinct standing-holder class — never once for "the represented population" as a whole. A single representative body may hold genuine delegated authority for some standing-holders while functioning only as institutional representation (Branch 3, subject to safeguard analysis under Section 17 rather than authorization) for others, simultaneously.

#### 2e. Validity Verdict and Authorization Status

For each affected agent: valid participation is established if Branch 1 or Branch 2 resolves affirmatively. Record which branch and, for Branch 2, which numbered basis supported the result.

| Outcome                                                               | Result                                          |
| ------------------------------------------------------------------------ | -------------------------------------------------- |
| Branch 1 resolves Yes/Yes for this standing-holder                    | **Participation is VALID** — basis: direct exercise |
| Branch 2 resolves Yes on all six sub-steps for this standing-holder   | **Participation is VALID** — basis: operative delegation |
| Neither branch resolves affirmatively for this standing-holder        | **Participation is INVALID**                        |

Where participation is invalid, classify **Authorization Status** for that standing-holder and closure before proceeding:

| Authorization Status | Meaning |
| --- | --- |
| **WITHHELD** | The standing-holder had genuine opportunity and capacity to authorize, and either explicitly refused, deliberately abstained, or otherwise declined — Branch 1's Exercise occurred but Authorization Content did not. |
| **UNAVAILABLE** | Valid authorization is genuinely infeasible for this standing-holder and this closure — not merely unobtained. Authorization was not sought is not the same fact as authorization could not have been sought; where a standing-holder was reachable and capable and authorization was simply not sought, classify as WITHHELD or as ordinary participation failure, not UNAVAILABLE. |

**Withheld Authorization Boundary.** Decision Necessity and Structural Unavoidability (see Step 4 and Section 6's closing note) do not convert Authorization Status WITHHELD into UNAVAILABLE or AUTHORIZED. A closure for which authorization has been validly withheld cannot be returned to consideration merely because delay, urgency, or tragic conflict increases. Any independent basis of permissibility must arise, if at all, through Step 3's Defensive Exception, and must satisfy that exception on its own terms.

**Closure-specificity.** Authorization Status is assessed per closure, not per standing-holder generally. A standing-holder for whom the overall action is UNAVAILABLE may still have a valid, operative WITHHELD status for a specific embedded component of that action (for example, refusing a particular manner of handling within an otherwise-necessary intervention). That component-level WITHHELD status remains independently binding under the Withheld Authorization Boundary above, regardless of the overall action's status.

If all affected standing-holders have valid participation, skip to Step 4 (verdict: Permissible). If any standing-holder's participation is invalid, proceed to Step 3 for that standing-holder's closure, carrying the Authorization Status classification forward — it determines what Step 4 may and may not do with the result.

---

### **Step 3: Check Defensive Exception**

If valid participation is absent, assess whether defensive exception applies.

#### 3a. Determine Exception Type

| Threat Type                                            | Exception Category                                     |
| ---------------------------------------------------------- | ---------------------------------------------------------- |
| Specific agent creating specific threat                | Standard Defensive Exception (7 safeguards)            |
| Structural threat (epidemic, pollution, systemic risk) | Structural Defensive Exception (7 enhanced safeguards) |

#### 3b. Standard Defensive Exception (Agent-Specific Threats)

Apply all seven safeguards:

**Safeguard 1: Specificity**

- Is the prevented closure specific (identified agent, identified action, identified target)?
- If speculative, categorical, or statistical → **Fails**

**Safeguard 2: Burden of Proof**

- The prevented closure is **real** (not hypothetical)
- The prevented closure is **greater** than the imposed closure
- The prevented closure is **non-participatory**
- The prevented closure is **not preventable** by lower-closure means
- If any undemonstrated → **Fails**

**Safeguard 3: Proportionality**

- Is imposed closure ≤ prevented closure across all dimensions?
- If disproportionate → **Fails**

**Safeguard 4: Discrimination**

- Does imposed closure target **only** the threatening agent?
- If categorical or collateral → **Fails**

**Safeguard 5: No Self-Dealing**

- Is the closer protecting **other agents'** futures (not their own)?
- If self-protective → **Fails**

**Safeguard 6: Recursive Check**

- Does the "defensive" closure create conditions for further closures?
- If self-perpetuating → **Fails**

**Safeguard 7: Sunset and Review**

- Is the defensive closure time-bounded with periodic review?
- If indefinite without review → **Fails**

**All seven safeguards must pass for standard defensive exception.**

#### 3c. Structural Defensive Exception (Non-Agent Threats)

For structural threats, apply all seven enhanced safeguards (see Section 16).

---

### **Step 4: Verdict**

Step 4 produces two independent outputs: a **Permissibility Verdict** and, where relevant, a **Decision Status**. The second never substitutes for the first.

**Permissibility Verdict**

| Condition                                                                                      | Verdict                   |
| -------------------------------------------------------------------------------------------------- | ---------------------------- |
| All affected agents validly participated (via appropriate modality)                            | **PERMISSIBLE**           |
| Participation absent, but standard defensive exception satisfied (all 7 safeguards)            | **PERMISSIBLE**           |
| Participation absent, but structural defensive exception satisfied (all 7 enhanced safeguards) | **PERMISSIBLE**           |
| Participation absent, no defensive exception                                                   | **IMPERMISSIBLE**         |
| Participation absent, defensive exception claimed but fails any safeguard                      | **IMPERMISSIBLE**         |
| Participation validity uncertain                                                               | **REQUIRES MODIFICATION** |

**If REQUIRES MODIFICATION:**

- Remedy identified impairments
- Obtain clearer participation via appropriate modality
- Reduce closure scope
- Re-run protocol

**Decision Status (independent axis)**

Where the Permissibility Verdict is IMPERMISSIBLE because Authorization Status is UNAVAILABLE (Section 6, Step 2e) — not WITHHELD — separately assess whether a decision is nonetheless required:

| Condition | Decision Status |
| --- | --- |
| Structural Unavoidability applies (every feasible option closes some agent's futures) **and** Decision Necessity applies (continued non-decision would itself generate escalating closure) | **REQUIRED** — select the least-closing available option |
| Either condition absent — a lower-closure alternative was feasible, or delay does not itself worsen the outcome | Not required; the IMPERMISSIBLE verdict stands with no forcing function |

A REQUIRED Decision Status never changes an IMPERMISSIBLE Permissibility Verdict to PERMISSIBLE. The acting agent remains fully attributable for the closure, including under Section 5's D4 for any prior action or omission that created or worsened the necessity — a REQUIRED status does not extinguish that attribution. Closure-specific WITHHELD status (Step 2e) remains independently binding regardless of the overall closure's Decision Status.

**Shorthand.** The combination *Permissibility Verdict: IMPERMISSIBLE, Decision Status: REQUIRED* may be referred to as **"Required but Non-Authorized"** only as explanatory shorthand for the qualifying individual-incapacity configuration described in Section 6's closing note and Section 12's Care Relationships. It is not a fourth verdict, an authorization category, or a new permissibility route. **Policy and collective-governance cases retain the unabbreviated output — Permissibility Verdict: IMPERMISSIBLE; Decision Status: REQUIRED — without the shorthand**, preserving the anti-softening architecture of Section 13's Collective Resolution Safeguards discussion. The shorthand does not apply to mass or institutional closures under any circumstance.

**Note on collective and non-authorizing factors.** Where a closure affects many standing-holders, or where continued non-decision would itself generate escalating non-participatory closure (Decision Necessity, discussed under "On Ambiguity and Recursion" below), or where the situation is one of structural unavoidability in which every feasible option closes some agent's futures, these facts may explain why a decision must be made, or may document how constrained and contestable the resulting arrangement is. None of them independently authorizes closure. Authorization arises only through valid direct or delegated participation. A satisfied Defensive Exception is a distinct basis of permissibility without participation authorization. Necessity to decide is not permission to close.

---

### **On Ambiguity and Recursion**

Decision Topology may be applied recursively when participation validity, closure scope, or defensive exception claims are ambiguous.

However, recursion does not continue indefinitely. **Delay, escalation, and indecision are themselves actions that generate closure** by reducing reversibility, degrading participation capacity, and initiating cascades.

Recursive analysis is justified only while it reduces expected closure. When further delay is likely to create greater non-participatory closure than action, continued recursion becomes impermissible — this is Decision Necessity. In such cases, agents are required to **act under uncertainty using the least-closing available option**.

Decision Necessity determines that a choice must be made; it does not determine that the choice made is permissible. The resulting closure remains impermissible unless it is independently authorized under Step 2 or satisfies Step 3's Defensive Exception. Where neither applies, choosing under Decision Necessity should be documented as such, distinctly from a claim of permissibility.

*Decision Topology allows recursive evaluation under ambiguity, but recursion is bounded by closure itself. Waiting is never free. Necessity to decide is not permission to close.*

---
## **7. Tiered Implementation**

The full protocol is appropriate for high-stakes decisions. For everyday decisions, use tiered implementation.

### **Tier 1: Quick Check (30 seconds)**

For low-stakes, reversible decisions:

1. Am I closing anyone's futures?
   - No → Proceed
   - Yes → Continue
2. Do they have genuine opportunity to say yes or no (via appropriate modality)?
   - Yes → Continue to 2a
   - No → Stop or escalate

   2a. Did they actually authorize this — not merely have the chance to?
   - Yes → Continue
   - No (said no, abstained, or did not respond) → Stop or escalate
3. Am I shaping their choice using false framing, omission, or pressure?
   - No → Continue
   - Yes → Stop or modify
4. Is this easily reversible?
   - Yes → Proceed with caution
   - No → Escalate to Tier 2

---

### **Tier 2: Standard Check (10-30 minutes)**

For moderate-stakes decisions (contracts, hiring, transactions):

**CLOSURE MAP**

- Who is affected?
- Agent type? (confirmed/provisional/non-agent)
- What futures close?
- Reversible or irreversible?
- Cascade scope?

**PARTICIPATION CHECK** For each affected agent:

- Appropriate modality identified?
- Opportunity to anticipate?
- Capacity unimpaired? (check 7 conditions)
- *Exercise:* did the agent do something via the appropriate modality? Yes/No
- *Content:* did that exercise affirmatively authorize this closure — not refusal, abstention, or silence? Yes/No
- If delegated: escalate to Tier 3 and complete the full Quick Validity Checklist (Section 22). Tier 2's brevity is not appropriate for delegation analysis.

**QUICK VERDICT**

- All participated validly → Permissible
- Gaps identified → Modify or stop
- Uncertain → Escalate to Tier 3

---

### **Tier 3: Comprehensive Check (Hours to Days)**

For high-stakes, irreversible decisions (AI deployment, infrastructure, policy, irreversible medical):

- Full protocol with detailed closure mapping across all dimensions
- Agent classification using Minimum Agency Threshold Test
- Participation validity audit against all seven impairment conditions
- Modality appropriateness verification
- Minimum Disclosure Standard compliance (for irreversible closures)
- Defensive exception analysis against all safeguards (standard or structural)
- Cascade tracing to foreseeable horizon
- Documentation and accountability assignment
- Tamper-resistant participation records

---

### **Decision Routing Guide**

| Decision Type                                       | Tier                | Time Investment |
| ------------------------------------------------------- | ---------------------- | ------------------ |
| Personal daily choices                              | 1                   | Seconds          |
| Contracts, hiring, transactions                     | 2                   | Minutes          |
| Product launches, policy proposals                  | 2-3                 | Hours            |
| AI deployment, infrastructure, irreversible medical | 3                   | Days/Weeks       |
| Civilizational-scale (climate, biotech, AGI)        | 3 + External Review | Months           |

---

## **8. Closure Analysis Templates**

### **Template A: Single Standing-Holder Analysis**

ACTION: _______________________________________

AGENT IDENTIFICATION:
Entity: _________________
Threshold test result: Confirmed / Provisional / Non-agent
Participation modality: _________________

CLOSURE MAP:
Material closures: ___________________________
Representational closures: ___________________
Reversibility: ______________________________
Cascade scope: ______________________________

PARTICIPATION CHECK:
Modality appropriate: Yes / No
Opportunity: Yes / No
Capacity unimpaired: Yes / No — if No, specify condition(s): ____

**Authorization Basis:** ☐ Direct ☐ Delegated ☐ Neither

*If Direct:*
- Exercise — did the agent do something via the modality? Yes / No
- Authorization Content — does it constitute affirmative consent to this closure? Yes / No
- If Exercise Yes / Content No: ☐ Explicit refusal ☐ Deliberate abstention ☐ Other non-affirmative act
- If Exercise No: ☐ Silence despite opportunity ☐ No genuine opportunity

*If Delegated (all six required):*
1. Standing-holder validly authorized the original delegation? Yes / No
2. Delegation establishes an intelligible decision envelope? Yes / No
3. This closure falls inside that envelope? Yes / No
4. Delegation still operative (not revoked / not suspended by a qualifying pre-effect refusal)? Yes / No
5. Delegate's own Opportunity/Capacity/Exercise valid for this closure? Yes / No
6. Delegate acting faithfully / accountable to standing-holder? Yes / No

VALIDITY: ☐ Valid — basis: direct ☐ Valid — basis: delegated ☐ Invalid
If Invalid, Authorization Status: ☐ WITHHELD ☐ UNAVAILABLE (see Section 6, Step 2e)
If WITHHELD → proceed to Defensive Exception only; Decision Necessity/Structural Unavoidability cannot reopen this closure.
If UNAVAILABLE → proceed to Defensive Exception, and separately assess Decision Status at Step 4 if no Defensive Exception applies.
Do not record a Permissibility Verdict at this point.

DEFENSIVE EXCEPTION (if participation invalid):
Type: Standard (agent-specific) / Structural
All safeguards passed: Yes / No

PERMISSIBILITY VERDICT: Permissible / Impermissible / Requires Modification
DECISION STATUS (only if Impermissible AND Authorization Status = UNAVAILABLE): Required / Not Required
If both Impermissible and Required, for an individual-incapacity case, this may be reported as "Required but Non-Authorized" — shorthand only, not a fourth verdict. Do not use this shorthand for collective or policy-scale closures; report those in full.

---

### **Template B: Multi-Standing-Holder Analysis**

ACTION: _______________________________________

AGENT CLASSIFICATION:

| Entity | Threshold Test | Classification | Participation Modality |
|--------|-----------------|-----------------|--------------------------|
|        |                 |                 |                          |

**Participation Check — repeat Template A's Participation Check block above in full, once per standing-holder or materially distinct standing-holder class.** No group-level Authorization Basis field precedes or replaces these repetitions. A heterogeneous group may simultaneously contain standing-holders with direct authorization, delegated authorization, and neither; the analysis must preserve that distinction rather than collapsing it into a single group finding.

MINIMUM DISCLOSURE PACKET (for irreversible closures):

- Key risks disclosed (worst case + most likely)
- Reversibility assessment provided
- Cascade obligations identified
- Exit/recourse options specified

**Aggregate Participation Result:**

| Result | Meaning |
|---|---|
| ☐ ALL AFFECTED STANDING-HOLDERS VALID | Every completed per-standing-holder block resolved Valid (any basis). Skip Defensive Exception for this closure. |
| ☐ MIXED — VALID / INVALID | List INVALID standing-holders below; Defensive Exception applies only to their specific closures, not the whole action. |
| ☐ ALL AFFECTED STANDING-HOLDERS INVALID | Defensive Exception analysis applies to the full affected group. |

*If MIXED, list standing-holders routed to Defensive Exception individually:*

| Standing-Holder / Class | Basis of Invalid | Closure(s) Requiring Step 3 |
|---|---|---|
|  | ☐ Explicit refusal ☐ Abstention ☐ Silence ☐ No opportunity ☐ Delegation branch failed at: ___ |  |

DEFENSIVE EXCEPTION ANALYSIS: Exception type: Standard / Structural

STANDARD SAFEGUARDS (if applicable): 1. Specificity / 2. Burden of proof / 3. Proportionality / 4. Discrimination / 5. No self-dealing / 6. Recursive check / 7. Sunset/review

STRUCTURAL SAFEGUARDS (if applicable): 1. High-quality evidence / 2. Narrow tailoring / 3. Strong sunset/review / 4. Scope limits / 5. Independent oversight / 6. Alternatives exhausted / 7. Aggregate proportionality

VERDICT: Permissible / Impermissible / Requires Modification

MODIFICATIONS REQUIRED: _______________________

ACCOUNTABILITY ASSIGNMENT: ____________________

---

### **Template C: Multi-Standing-Holder Cascade Analysis**

Use Template B in full, and add the following cascade table. Responsibility may propagate through a chain of attributable downstream closures (D4); authorization does not. Each newly affected standing-holder at each stage requires its own fresh Authorization Basis determination — an upstream standing-holder's authorization of an earlier closure never supplies authorization for a downstream standing-holder's closure.

CASCADE ANALYSIS:

| Stage | Triggered Closure | Affected Standing-Holder | Authorization Basis for THIS Closure | Result |
|-------|--------------------|-----------------------------|------------------------------------------|--------|
| 1→2   |                    |                              | ☐ Direct ☐ Delegated ☐ Neither          | ☐ Valid ☐ Invalid |

VERDICT: Permissible / Impermissible / Requires Modification

MODIFICATIONS REQUIRED: _______________________

ACCOUNTABILITY ASSIGNMENT: ____________________

---
# **PART III: TRANSLATION LAYER**

## **9. Mapping Traditional Moral Vocabulary**

For readers trained in conventional ethics, the following translations connect Decision Topology to familiar concepts:

| Traditional Concept   | Decision Topology Translation                                                    |
| ------------------------ | -------------------------------------------------------------------------------- |
| **Harm**              | Non-participatory closure of wellbeing-relevant futures                          |
| **Unauthorized harm** | Closure without valid participation                                              |
| **Consent**           | Valid participation via appropriate modality                                     |
| **Informed consent**  | Participation without information asymmetry or deception                        |
| **Coercion**          | Participation impairment via threat                                              |
| **Exploitation**      | Participation impairment via dependency trap or asymmetry                        |
| **Property**          | Standing over object-mediated futures                                            |
| **Theft**             | Non-participatory closure of property-mediated futures                           |
| **Ownership**         | Legitimate standing acquisition over object-mediated futures                     |
| **Rights**            | Protected domains of standing (futures protected from non-participatory closure) |
| **Violence**          | Non-participatory material closure, especially of bodily futures                 |
| **Self-defense**      | Proportional defensive closure preventing greater non-participatory closure      |
| **Deception**         | Representational closure                                                         |
| **Fraud**             | Representational closure combined with material closure                          |
| **Murder**            | Total irreversible closure of life futures                                       |
| **Assault**           | Partial closure of bodily futures                                                |
| **Imprisonment**      | Closure of movement futures                                                      |
| **Slavery**           | Total closure of agency futures with ongoing participation impairment            |
| **Justice**           | Restoration of improperly closed futures or proportional response to violations  |
| **Animal rights**     | Animal standing over their futures; participation via appropriate modality       |

---

## **10. Why Traditional Concepts Feel Right**

Traditional moral vocabulary captures real patterns. Decision Topology explains why these concepts resonate:

### **Why "Harm" Resonates**

Humans intuitively track closure of wellbeing-relevant futures. "Harm" is the folk-psychological compression of this tracking. We recognize harm because we recognize closure.

### **Why "Consent" Resonates**

Humans recognize the difference between chosen closures and imposed closures. "Consent" is the folk-psychological marker for valid participation. We care about consent because we care about participation.

### **Why "Property" Resonates**

Humans recognize standing over object-mediated futures. "Property" is the institutional formalization of this standing. Property rights emerged to protect standing over futures mediated by objects.

### **Why "Rights" Resonate**

Humans recognize that some futures should be protected from non-participatory closure. "Rights" are the political formalization of standing protection. We assert rights when we assert standing.

### **Why "Animal Welfare" Resonates**

Humans recognize that animals have futures that matter to them. The intuition that animals should not suffer unnecessary harm reflects recognition of animal standing—even when the language of "rights" feels contested.

### **The Translation Is Not Arbitrary**

Traditional vocabulary evolved to track topology. Decision Topology makes the tracking explicit and precise. The framework does not replace moral intuition—it explains it.

---

# **PART IV: APPLICATIONS**

## **11. Business Ethics**

**Core question:** Whose futures is this organization closing, and did they validly participate via appropriate modality?

### **Key Closure Domains**

| Stakeholder               | Futures at Risk                                   |
| ---------------------------- | ------------------------------------------------------ |
| **Employees**             | Career, health, time, autonomy, economic security |
| **Customers**             | Financial, informational, health, choice           |
| **Communities**           | Environmental, economic, social fabric             |
| **Suppliers**             | Economic, operational, relational                  |
| **Shareholders**          | Financial, informational                           |
| **Animals (if affected)** | Bodily integrity, freedom from suffering            |

### **Common Participation Impairments in Business**

| Impairment                | Example                                                           |
| ---------------------------- | ---------------------------------------------------------------------- |
| **Information asymmetry** | Fine print, complexity, expertise gaps                            |
| **Time pressure**         | Artificial urgency, limited-time offers, exploding offers         |
| **Dependency traps**      | Vendor lock-in, non-compete clauses, proprietary formats          |
| **Coercion**              | Economic necessity, take-it-or-leave-it terms, market power abuse |

### **Protocol Application**

For any business decision:

1. Map closures across all stakeholder agents (including animals where relevant)
2. Identify appropriate participation modality for each agent type
3. Verify participation validity for each
4. Flag impairments
5. Modify to remedy impairments or reduce closure scope
6. Document participation with tamper-resistant records

### **Revenue Model Evaluation**

Ask: Does this revenue model depend on participation impairment?

- Dark patterns → Representational closure
- Hidden fees → Information asymmetry
- Switching costs → Dependency traps
- Artificial scarcity → Coercion
- Animal exploitation without welfare consideration → Non-participatory closure on agents with standing

If yes, the model is structurally impermissible.

---

## **12. Personal Ethics**

**Core question:** Am I closing another agent's futures without their valid participation? Am I validly participating in closures of my own futures?

### **Key Closure Domains**

| Domain            | Futures at Risk                              |
| -------------------- | -------------------------------------------------- |
| **Relationships** | Partners, family, friends—relational futures |
| **Commitments**   | Promises, obligations, expectations          |
| **Resources**     | Shared assets, time, attention               |
| **Dependents**    | Children, animals, those in your care        |

### **Self-Directed Closure**

Agents may close their own futures. This is permissible if:

- Participation is valid (not impaired by manipulation, deception, or coercion from others)
- The closure does not create non-participatory closure for others

### **Care Relationships**

**Care boundary.** A caretaker's duty to act does not establish a prior delegating act by a standing-holder who lacked the capacity to delegate. UNAVAILABLE must be established as genuine closure-specific infeasibility, not inferred merely because consent was inconvenient, delayed, or not requested. Residual preferences and closure-specific refusals remain relevant and cannot be overwritten by a general care claim.



When you have care responsibility for agents with non-standard participation modalities (children, animals, cognitively impaired), distinguish two things that were historically collapsed together:

- Where the standing-holder has evaluative capacity for a specific closure (an older child's assent, an animal's closure-specific aversion, an observable preference within a cognitively impaired agent's reach), that is their **own direct participation** for that closure — honor it under Step 2's ordinary Branch 1 test, not as something exercised on their behalf.
- Where authorization is genuinely unavailable — the standing-holder never had, and could not have had, the capacity to authorize this closure — you do not thereby hold their participation, delegated or otherwise. They never performed a delegating act; standing was never transferred; you are not exercising their participation, you are acting as an accountable caretaker under Authorization Status: UNAVAILABLE (Section 6). This action is required, not authorized, where Structural Unavoidability and Decision Necessity both apply — see Section 6, Step 4.

**Accountable caretaker action, in either case, requires:**

- Accountability to the agent's own interests and trajectory, not your preferences
- Observable preference and closure-specific refusal signals honored where they exist, regardless of the overall closure's status
- Justification and documentation in terms of the standing-holder's own trajectory
- Full attribution for the decision, including for any earlier action or omission that created or worsened the necessity — a required decision does not excuse what made it necessary

### **Protocol Application**

- For decisions affecting others: Verify their participation via appropriate modality
- For self-affecting decisions: Verify your own participation is unimpaired
- For decisions affecting dependents: Honor their own direct participation where they have evaluative capacity for the specific closure; where authorization is genuinely unavailable, act as an accountable caretaker under Authorization Status: UNAVAILABLE, not as their delegate
- For shared decisions: Ensure all parties validly participate

---

## **13. Policy Ethics**

**Core question:** Does this policy impose closures on agents without valid participation mechanisms, and where valid participation is unavailable, does the policy satisfy a valid Defensive Exception?

### **Key Closure Domains**

| Domain            | Futures at Risk                                     |
| -------------------- | ------------------------------------------------------- |
| **Liberty**       | Movement, association, expression                   |
| **Economic**      | Property, livelihood, opportunity                   |
| **Security**      | Safety, health, privacy                              |
| **Political**     | Voice, representation, exit                          |
| **Environmental** | Substrate-mediated futures for all dependent agents  |

### **Participation at Scale**

Mass policies cannot obtain individual participation. This is a constraint on what governance can achieve, not a mechanism that discharges the axiom's requirement.

- Numbers: millions or billions of affected agents
- Future agents: those not yet born cannot participate in current decisions
- Information complexity: policy implications exceed individual comprehension
- Interdependency: individual choices affect collective outcomes in ways individuals cannot control
- Time constraints: some policy decisions cannot be deferred indefinitely without generating additional closure

Scale explains why participation may be unavailable. It does not change what participation means. A policy-scale closure remains subject to the same authorization requirement as any other closure: it receives participation authorization through valid direct participation or valid delegation operative for the closure (Step 2), or it may have a separate basis of permissibility through a satisfied Defensive Exception (Step 3). Where neither basis is available, the closure does not become permissible merely because collective decision-making at scale is difficult. If continued non-decision itself begins creating greater closure, the Recursion Bound (Section 6, "On Ambiguity and Recursion") may require a decision — but necessity to decide is not permission to close; the resulting closure remains impermissible unless independently authorized.

#### Collective Resolution Safeguards

Institutional Representation, Bounded Scope, Exit Viability, Amendment & Contestability, and Proportionality constrain how collective closure is selected, imposed, contested, reviewed, and revised. They remain relevant whether the closure is authorized through valid participation, justified under a Defensive Exception, structurally unavoidable, or selected because continued non-decision has triggered Decision Necessity. Failure on any of them leaves closure less constrained, more capturable, and less contestable; it does not, on its own, determine whether the closure is authorized.

| Safeguard | Description |
| --- | --- |
| **Institutional Representation** | Where an agent actually authorizes another agent to exercise participation on their behalf, that is genuine delegated participation under Section 5's D6 and belongs in the Step 2 authorization analysis. Where an institution or representative body acts on behalf of affected agents who did not individually delegate to it, the arrangement is institutional representation: it can constrain the exercise of authority and provide accountability, but it does not constitute participation and cannot independently authorize closure. |
| **Bounded Scope** | Governance cannot claim unlimited authority over agents' futures. Whenever collective closure is being considered or imposed, it must operate only within specified domains, with explicit limits on magnitude and no scope creep beyond enumerated areas. This applies whether the closure has valid participation authorization, has a separate permissibility basis in a satisfied Defensive Exception, is structurally unavoidable, or is selected under Decision Necessity; the latter two do not independently establish permissibility. |
| **Exit Viability** | Exit is not a form of participation. Remaining in a jurisdiction when exit is technically available does not constitute an agent's exercise of standing over the closures they experience by staying. What viable exit does provide is refusal capacity: it measures how much a policy's closure is actually escapable, and therefore how much genuine burden it imposes on those who remain. See the Exit Viability Test below. |
| **Amendment & Contestability** | Collective closure should remain open to revision wherever materially possible, at both the policy level and the level of individual application. This does not retroactively supply the participation that was absent when the closure was first imposed — it provides ongoing contestability, valuable in its own right. Individual applications of an otherwise valid collective closure must remain contestable, not merely the closure regime as a whole: an affected agent must have accessible means to contest how the closure applies to their specific circumstances, with timely review and a meaningful remedy available. |
| **Proportionality** | Proportionality bounds a closure; it does not authorize one. A closure that is minimally necessary but otherwise unauthorized remains impermissible — proportionality determines how much closure is too much, not whether closure is permitted in the first place. |

**Transparency and Oversight (cross-cutting).** Transparency and Oversight are not themselves numbered among the five Collective Resolution Safeguards; they operate across all five. Transparency requires that the existence, scope, and implementation of a collective closure be observable to those it affects. Oversight requires an independent capacity to verify whether the other safeguards are actually being honored in practice, not merely claimed. Both improve visibility and constrain capture: a collective closure imposed without transparency cannot meaningfully be contested, and a safeguard regime without independent oversight cannot be verified. Neither Transparency nor Oversight authorizes closure or substitutes for valid participation or a valid Defensive Exception. They document how constrained and verifiable the exercise of collective authority is; they do not determine whether that authority was ever validly established.

### **Exit Viability Test**

**Exit preserves meaningful refusal capacity only if the closure of exiting is substantially less than the closure imposed by staying.** This measures how escapable a policy is for the agents subject to it — it does not establish that remaining constitutes participation in the policy.

**Operational assessment:**

- What futures does exiting close? (relocation costs, relationship severance, economic disruption)
- What futures does staying under the policy close?
- Exit is viable only if: Closure(exit) < Closure(staying)
- If Closure(exit) ≥ Closure(staying): exit does not provide viable refusal capacity for this agent — the burden of remaining is not reduced by a theoretical ability to leave. Regardless of this result, exit never itself authorizes the policy; it only measures how much refusal capacity remains available to agents subject to it.

**Implication:** Policies cannot claim legitimacy through exit rights if exit imposes comparable or greater closure than compliance, and cannot claim legitimacy through exit rights even where exit is genuinely viable — exit documents burden, it does not authorize.

---
## **14. AI Ethics**

**Core question:** Is this system creating closures on agents, and are participation mechanisms adequate?

### **AI as Closure Mechanism**

AI systems close futures through:

| Mechanism           | Example                                                         |
| ---------------------- | ----------------------------------------------------------------- |
| **Decisions**       | Loan approvals, hiring, content moderation, criminal sentencing |
| **Recommendations** | Shaping choices, filtering information, directing attention     |
| **Predictions**     | Creating self-fulfilling constraints, labeling, risk scoring    |
| **Automation**      | Removing human agency from processes                            |

### **AI as Potential Agent**

Apply the Minimum Agency Threshold Test:

| Question                           | Assessment for AI                                                      |
| ------------------------------------- | ---------------------------------------------------------------------------- |
| Self-referential future models     | Does it model its own persistence and future states as mattering?      |
| Persistent preference organization | Does it have stable, organized preferences beyond task completion?     |
| Valenced experience                | Is there credible evidence of phenomenology, or purely as-if behavior? |

**Classification outcomes:**

- **Confirmed agent:** Full participation requirements apply to closures affecting the AI
- **Provisional agent:** Apply full requirements; monitor for evidence; prefer reversible closures
- **Non-agent:** No standing, but may still have instrumental value or mediate others' futures

### **Implementation Requirements**

| Requirement                    | Description                                                                     |
| --------------------------------- | ------------------------------------------------------------------------------------ |
| **Closure mapping**            | AI systems must model what futures they close                                   |
| **Participation verification** | Systems must check for impairment conditions                                    |
| **Modality adaptation**        | Systems must use appropriate participation modalities for different agent types |
| **Cascade tracking**           | Systems must trace downstream closures                                          |
| **Standing attribution**       | Systems must identify who bears standing obligations                            |
| **Explanation capacity**       | Systems must be able to explain closures to affected agents                     |

### **AI-Specific Participation Challenges**

| Challenge                                         | Response                                                   |
| ------------------------------------------------------ | ---------------------------------------------------------------- |
| Speed (decisions faster than participation)       | Pre-commitment participation; categorical approval         |
| Scale (millions of decisions)                     | Sampled auditing; pattern monitoring                       |
| Opacity (decisions not explainable)               | Explainability requirements; right to human review         |
| Cascade (AI decisions trigger other AI decisions) | End-to-end cascade mapping; human checkpoints              |
| AI agency uncertainty                             | Apply provisional agent status; prefer reversible closures |

---

# **PART V: SAFEGUARDS**

## **15. The Seven Defensive Exception Safeguards**

The defensive exception ("closure is permissible if it prevents greater non-participatory closure") is the most dangerous part of the framework. Without safeguards, it could justify any violation. Seven structural safeguards prevent exploitation.

### **Safeguard 1: Specificity Requirement**

**The prevented closure must be specific, not speculative.**

- "Preventing terrorism" is **not specific** (categorical, statistical)
- "Preventing this identified agent from executing this identified attack on these identified targets" **is specific**

**Operational test:** Can you name the specific agent, action, and closure being prevented?

**If speculative, categorical, or statistical → Defensive exception fails**

---

### **Safeguard 2: Burden of Proof**

**The agent claiming defensive exception bears the burden of demonstrating that the prevented closure is (a) real, (b) greater, (c) non-participatory, and (d) not preventable by lower-closure means.**

The default is **impermissibility**. Defensive exception is an affirmative defense requiring evidence, not an assertion.

---

### **Safeguard 3: Proportionality**

**Defensive closure must be less than or equal to prevented closure, measured across the same dimensions.**

**Example:** Mass surveillance fails this test:

- Privacy closure imposed: millions of agents
- Security closure prevented: specific attacks on specific targets
- Millions > Specific → Disproportionate → Fails

---

### **Safeguard 4: Discrimination**

**Defensive closure must target only agents creating the threat.**

Closing futures for Population X because some members of X might create closure is **discrimination failure**.

Defensive closure targets the **specific threatening agent**, not categories.

---

### **Safeguard 5: No Self-Dealing**

**Agents cannot claim defensive exception to protect their own futures by closing others' futures.**

- The state cannot claim "we must close your futures to protect the state's futures"
- Institutions do not have standing; only the agents within them do
- Defensive exception requires protecting **other agents'** futures, not the closer's own

---

### **Safeguard 6: Recursive Check**

**If a "defensive" closure creates conditions for further "defensive" closures, it is not genuinely defensive.**

**Dependency trap pattern:**

1. Create vulnerability
2. Close futures "to protect against" the vulnerability you created
3. Claim defensive exception

The recursive check catches this: if your "defense" generates the threat it claims to address, it fails.

---

### **Safeguard 7: Sunset and Review**

**Defensive closures must be time-bounded, reviewed, and lifted when the prevented closure is no longer present.**

| Requirement      | Description                                                      |
| ------------------- | ---------------------------------------------------------------------- |
| **Time-bounded** | Explicit expiration date proportional to the threat              |
| **Reviewed**     | Periodic assessment of whether prevented closure remains present |
| **Lifted**       | Terminated when prevented closure is no longer active            |

**Failure mode blocked:** "Temporary defense" becoming permanent regime. Emergency powers that never end. Surveillance justified by threats that have passed.

**Operational test:** Can this defensive closure be maintained indefinitely without review? If yes → Fails Safeguard 7

---

### **Safeguard Summary Table**

| # | Safeguard       | Test                                                                          | Failure Condition          |
| --- | ----------------- | ---------------------------------------------------------------------------------- | ----------------------------- |
| 1 | Specificity     | Is prevented closure specific?                                                | Speculative/categorical    |
| 2 | Burden of Proof | Has closer demonstrated real > greater > non-participatory > no alternatives? | Any element undemonstrated |
| 3 | Proportionality | Imposed ≤ Prevented?                                                          | Imposed > Prevented        |
| 4 | Discrimination  | Targets only threatening agent?                                               | Categorical/collateral     |
| 5 | No Self-Dealing | Protecting others' futures?                                                   | Self-protective            |
| 6 | Recursive Check | Does defense generate further threats?                                        | Self-perpetuating          |
| 7 | Sunset/Review   | Time-bounded with review?                                                     | Indefinite without review  |

**All seven safeguards must be satisfied for standard defensive exception to apply.**

---

## **16. Structural Defensive Exception**

Some threats are structural rather than agent-specific: epidemics, environmental degradation, systemic financial risk, infrastructure failure. These cannot satisfy the standard specificity requirement (no single identified agent/action/target).

### **When Structural Defensive Exception Applies**

| Threat Type        | Example                             | Why Standard Exception Fails         |
| --------------------- | -------------------------------------- | ------------------------------------- |
| **Epidemics**      | Pandemic disease spread             | No single agent causing spread       |
| **Environmental**  | Pollution, climate change           | Diffuse causation across many actors |
| **Systemic risk**  | Financial contagion                 | Emergent from system structure       |
| **Infrastructure** | Grid failure, supply chain collapse | No individual threatening agent      |

### **Seven Enhanced Safeguards for Structural Defense**

Structural Defensive Exception permits closure against structural threats, but requires **enhanced safeguards**. All seven must pass; partial satisfaction does not create partial permissibility.

| # | Enhanced Safeguard                       | Requirement                                                                                                  |
| --- | ------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| 1 | **High-quality evidence**                | Threat must be demonstrated with rigorous empirical evidence, not speculation or modeling alone              |
| 2 | **Narrow tailoring**                     | Closure must be the minimum necessary to address the structural threat; overbroad closures fail              |
| 3 | **Scope limits**                         | Measurable boundaries on closure magnitude; cannot expand without re-authorization                            |
| 4 | **Lower-closure alternatives exhausted** | Must demonstrate that all lower-closure interventions have been tried or are clearly inadequate              |
| 5 | **Independent oversight**                | Third-party review body with authority to terminate the defensive closure                                    |
| 6 | **Strong sunset and review**             | Shorter time bounds than agent-specific defense; mandatory review at defined intervals; automatic expiration |
| 7 | **Aggregate proportionality**            | Total closure imposed must be less than total closure prevented, even when distributed across many agents    |

### **Structural Defensive Exception Checklist**

- Is the threat structural (not attributable to specific agent)?
- Is there high-quality empirical evidence of the threat?
- Is the proposed closure narrowly tailored?
- Are scope limits defined and measurable?
- Have lower-closure alternatives been exhausted?
- Is independent oversight in place with termination authority?
- Are sunset provisions shorter than standard defensive closures, with mandatory review?
- Is aggregate closure < aggregate prevented closure?

**Eight checks total: (1) structural threat + (7) enhanced safeguards. All seven enhanced safeguards must pass — partial satisfaction does not create partial permissibility.**

### **Structural Defense Examples**

| Structural Threat           | Permissible Closure                                                             | Impermissible Closure                                                 |
| ------------------------------ | ------------------------------------------------------------------------------------ | ---------------------------------------------------------------------- |
| **Epidemic**                | Targeted quarantine with review, testing requirements, temporary venue closures | Indefinite lockdowns without review, permanent surveillance           |
| **Pollution**               | Emission limits, remediation requirements, narrow activity restrictions         | Permanent property seizure without compensation, overbroad bans       |
| **Financial systemic risk** | Capital requirements, leverage limits, narrow trading restrictions              | Unlimited bailouts without accountability, indefinite market closures |
| **Fire safety**             | Building codes, inspection requirements, temporary evacuations                  | Indefinite occupancy bans without review                              |
| **Climate**                 | Carbon pricing, efficiency standards, transition requirements                   | Permanent restrictions without sunset, no adaptation pathway          |

---

## **17. Conflict Resolution**

When agents' validly-participated closures conflict:

### **Conflict Types and Resolution Rules**

| Conflict Type                                | Resolution Rule                                                                                   |
| ------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| **Mutual closure**                           | Both must validly participate in combined arrangement, or neither proceeds                        |
| **Externality**                              | Agent creating closure bears responsibility; must obtain affected party's participation or modify |
| **Resource competition (excludable)**        | First-valid-participation has priority, unless later claim satisfies Defensive Exception            |
| **Resource competition (commons/substrate)** | Route through Mediated Standing Rule; proportionality applies                                     |
| **Claim relationship**                       | Direct standing remains with the affected agent regardless of delegated participation or institutional representation. Delegated participation may authorize closure to the extent it remains accountable to that standing; institutional representation may constrain and inform the exercise of authority, but does not itself authorize closure regardless of accountability. |

When claims concerning an agent's futures are made through different relationships, distinguish standing from representation. **Direct Standing** is the agent's own relationship to closures affecting their futures. **Delegated Participation** occurs when an agent validly authorizes another agent to exercise participation on their behalf under Section 5's D6; the standing remains with the affected agent. **Institutional Representation** is a claim made by an institution on behalf of agents it represents, serves, governs, or coordinates; institutions do not thereby acquire standing of their own. Direct standing cannot be overridden merely by delegated or institutional representation. Any representative claim must remain accountable to the standing of the agents whose futures are affected.

### **Externality Resolution**

When Agent A's self-closure incidentally affects Agent B:

1. A has standing over their own futures
2. B has standing over their affected futures
3. A's closure creates closure for B
4. A must either:
   - Obtain B's participation via appropriate modality, OR
   - Modify to eliminate B's closure, OR
   - Demonstrate that A's closure prevents greater non-participatory closure for others

**Unilateral closure without B's participation → Impermissible externality**

### **Commons and Essential Substrate Protection**

When a resource is:

- A **commons** (non-excludable, collectively accessible), OR
- An **essential substrate** for many agents' futures (water, air, climate stability, critical infrastructure)

Then "first-valid-participation" does **not** grant priority to capture or exclude.

**Instead:**

1. Apply **Mediated Standing Rule**: All agents dependent on the commons have standing over closures to it
2. Any closure of commons access requires **participation from all affected agents, or a valid Defensive Exception where applicable**. There is no governance-approximation alternative to these two routes.
3. **Proportionality** applies: No agent can close more commons access than their proportional share without satisfying structural defensive exception
4. **Capture prevention**: Attempts to convert commons to excludable resources require participation from all agents with mediated standing

**Operational test:** Is this resource one whose closure would cascade to many agents' futures? If yes, it is commons/substrate; route through mediated standing, not first-participation priority.

### **Cascade Responsibility in Conflicts**

When a closure cascade creates conflicts:

- The initiating agent remains responsible for downstream closures attributable to the initiating action until the relevant cascade stabilizes
- Operational responsibilities may be allocated among agents before initiation, but affected agents retain their standing throughout the cascade
- Each downstream agent retains standing over their own futures
- Resolution requires participation from all affected agents at each stage of the cascade, or modification to reduce cascade scope. An upstream agent's valid participation in an earlier closure does not authorize a downstream closure affecting a different standing-holder; each newly affected standing-holder's authorization is assessed fresh.

---
# **PART VI: GROUNDING**

## **18. Metaphysical Grounding**

### **Why Topology Is Real**

Possibility is not merely epistemic (what we don't know). Possibility is **ontic** (what could be). Futures exist as accessible states. Actions alter accessibility. This is not metaphor; it is the structure of causation in time.

### **Why Closure Matters**

Agents exist as **trajectories through possibility space**. Closing futures is not merely inconvenient; it is altering the shape of an agent's existence. An agent with closed futures is a different entity than they would have been with open futures.

### **Why Participation Is Foundational**

Agents have standing over their own trajectories. This is not a moral assertion—it is a structural fact. An agent's relationship to their own futures is constitutive of their agency. Altering another agent's trajectory without their participation is **usurping a structural position that belongs to them**.

### **Why Standing Is Binary**

All agents above threshold have equal relationship to their own futures. A dog's relationship to its future of avoiding pain is not less real than a human's relationship to their future career. The *content* of futures differs; the *structural relationship* of standing does not.

### **The Grounding Claim**

Decision Topology does not rest on contested moral intuitions. It rests on:

1. **Agents exist** (entities with phenomenology, agency, anticipation)
2. **Futures exist** (accessible states that actions can close)
3. **Standing exists** (the structural relationship between agents and their futures)
4. **Participation exists** (agents' exercise of standing over closures)

These are structural features of reality, not moral preferences.

---

## **19. Theological Grounding**

*For readers who require or seek theological foundation:*

### **Creation as Open Futures**

The act of creation includes possibility—the capacity for things to be otherwise. Agents are created with **open futures**, not predetermined paths. This openness is part of the structure of created existence.

### **Closure as Usurpation**

Non-participatory closure usurps the agent's relationship to their own future. In theological terms, it usurps a position belonging to the agent's relationship with their Creator. To close another's futures without participation is to claim a position over them that belongs only to God.

### **Participation as Sacred**

Valid participation respects the agent's standing over their futures. This standing is part of how agents are created—with the capacity to shape their own trajectories. Impaired participation violates this sacred standing, regardless of the appearance of consent.

### **All Agents as Creation**

Animals, humans, and any other beings with phenomenology, agency, and anticipation are part of creation. Their standing is not granted by humans—it is inherent in their created nature. Denial of animal standing is denial of their place in creation.

### **Representational Closure as Reality-Distortion**

Deceiving an agent is not merely harmful; it corrupts their capacity to stand in proper relationship to reality—which is to say, to Creation itself. Representational closure distorts the agent's perception of the world God made.

### **Compatibility**

This grounding is compatible with multiple theological traditions:

- **Jewish:** Standing as tzelem Elohim (image of God); animals as part of creation deserving consideration
- **Christian:** Standing as imago Dei; participation as respect for God-given agency; stewardship over creation
- **Islamic:** Standing as khalifa (stewardship); animals as nations like humans (Quran 6:38)
- **Buddhist:** Closure as creation of suffering; all sentient beings have standing
- **Hindu:** Standing as atman; closure as violation of dharmic order; ahimsa (non-harm) to all beings

The axioms do not require theological grounding; they are consistent with it for those who seek such grounding.

---

## **20. Framework Character**

### **On Judgment**

This framework requires judgment. It provides structure for judgment, not replacement of it.

Decision Topology offers:

- Precise definitions
- Operational protocols
- Clear tests and checklists

It does not offer:

- Formulas that eliminate thought
- Algorithms that remove responsibility
- Rules that answer every question

**This is a framework for reality, not toy worlds.** If you want a formula that removes the need to think, you want a different book.

Measurement is comparative. Participation validity is contextual. Some calls require human judgment. This is not a weakness—it is honesty about the nature of ethics.

### **On Normativity**

The framework makes one minimal value commitment:

**Agents have standing over their own futures.**

This is not neutral. It is a claim about what matters and why.

The strength here is not neutrality; it is **structural inevitability**:

**Any system that denies agent standing over their own futures ends up justifying domination.**

This is not a contested philosophical position; it is an empirical observation about where denial leads. Systems that deny standing—to humans, to animals, to any agents—historically produce domination, extraction, and violation.

Decision Topology makes this commitment explicit and traces its consequences rigorously. The framework is honest about its foundation rather than pretending to derive ethics from nowhere.

### **On Completeness**

Decision Topology addresses the **constraint problem**: what is impermissible.

It does not address the **optimization problem**: what is best among permissible options.

It does not address the **meaning problem**: what makes life worth living.

It does not address the **virtue problem**: what kind of agent to become.

These are real questions. They require different frameworks. Decision Topology provides the floor—the minimum constraint that any adequate ethics must satisfy. What you build above the floor is your own responsibility.

---

# **PART VII: REFERENCE**

## **21. One-Page Framework Summary**

| DECISION TOPOLOGY — Yusuf Abdulla Shunan — Ethics Under Irreversibility (v1.3) |
| --- |
| **THREE PRIMITIVES** |
| AGENT: Entity with phenomenology + agency + anticipation (Binary threshold; equal standing above threshold). CLOSURE: Reduction in accessible future states (Material or representational; measured agent-relative). STANDING: Relationship between agent and their affected futures (Non-transferable; binary; includes mediated standing). |
| **THE SINGLE AXIOM** |
| An action is impermissible if it creates closure—material or representational—over an agent's future states without that agent's valid participation, unless the closure prevents a greater non-participatory closure affecting another agent, and the preventive closure is proportional. |
| **PARTICIPATION VALIDITY (Hardening 1)** |
| Via appropriate modality for agent type. Invalid if capacity impaired: information asymmetry, coercion, time pressure, deception, dependency trap, representation manipulation, omission. Exercise of a modality is a separate question from whether that exercise's content authorizes the closure — both must be established. |
| **REPRESENTATIONAL CLOSURE (Hardening 2)** |
| Closure includes distortion of the agent's possibility-space model. Deception is closure even without material state change. |
| **FOUR-STEP PROTOCOL** |
| MAP CLOSURES → VERIFY PARTICIPATION (exercise AND authorization content, direct or delegated; classify Authorization Status as AUTHORIZED / WITHHELD / UNAVAILABLE where invalid) → CHECK DEFENSE (Standard-7 or Structural-7 safeguards) → VERDICT: Permissibility Verdict (Permissible / Impermissible / Modify) + independent Decision Status (Required / not required) where Authorization Status is UNAVAILABLE. Decision Necessity, Structural Unavoidability, and Collective Resolution Safeguards never create participation authorization or independently satisfy the Defensive Exception basis of permissibility. Recursion is bounded by closure. Waiting is never free. |
| **SIX DERIVATIONS** |
| D1: Participation required — exercise and authorization content, both. D2: Representational standing protected. D3: Defense bounded by proportionality. D4: Responsibility for attributable downstream closure persists; standing does not transfer with it. D5: Irreversibility demands stronger validity. D6: Standing cannot be delegated, only participation — delegate exercises Opportunity/Capacity/Exercise independently, on the standing-holder's behalf; delegation is always revocable. |
| **SPECIAL RULES** |
| Commons/substrates: route through mediated standing, or a valid Defensive Exception — never governance approximation. Exit viability: measures refusal capacity, never authorization. Institutional representation constrains and informs; only genuine delegation under D6, or the standing-holder's own direct participation, authorizes. WITHHELD authorization cannot be reopened by Decision Necessity — only a satisfied Defensive Exception is an independent route. Incapacity does not create authority; it can make authorization unavailable — those are not the same proposition. Necessity to decide is not permission to close. |

---

## **22. Quick Validity Checklist**

For each agent experiencing closure:

### **Agent Classification**

- Minimum Agency Threshold Test applied?
- Classification: Confirmed / Provisional / Non-agent
- Appropriate participation modality identified?

### **Opportunity**

- Did they have opportunity to anticipate the closure?

### **Capacity (Seven Impairment Conditions)**

- Access to material facts? (No information asymmetry)
- Free from deception?
- Material facts not withheld? (No omission)
- Free from coercion or threats?
- Not in a manufactured dependency?
- Adequate time to evaluate?
- Model of futures not manipulated?

### **Authorization Basis**

☐ Direct ☐ Delegated ☐ Neither

*If Direct:*
- Exercise — did the agent do something via the appropriate modality? ☐ Yes ☐ No
- Authorization Content — does the content of that exercise constitute affirmative consent to this specific closure? ☐ Yes ☐ No
- If Exercise = Yes but Authorization Content = No: ☐ Explicit refusal ☐ Deliberate abstention ☐ Other non-affirmative act
- If Exercise = No: ☐ Silence or non-response despite genuine opportunity ☐ No genuine opportunity existed

*If Delegated (all six required):*
1. Did the standing-holder validly authorize the original delegation — appropriate modality, genuine opportunity, unimpaired capacity, actual exercise, and authorization content? ☐ Yes ☐ No
2. Does the delegation establish a sufficiently intelligible decision envelope? ☐ Yes ☐ No
3. Does this specific closure fall inside that envelope? ☐ Yes ☐ No
4. Is the delegation still operative — not revoked, not suspended by a qualifying pre-effect refusal? ☐ Yes ☐ No
5. Does the delegate separately satisfy Opportunity, Capacity, and Exercise for this specific closure? ☐ Yes ☐ No
6. Is the delegate acting faithfully and accountable to the standing-holder's interest? ☐ Yes ☐ No

A No at any of 1–6 ends the delegated route for this standing-holder. If Direct also fails or does not apply, this standing-holder's participation is INVALID; proceed to Step 3.

*Plural standing-holders:* complete this Authorization Basis section separately for each affected standing-holder or materially distinct standing-holder class. One completed section for "the group" is not a valid use of this checklist.

### **For Irreversible Closures (Minimum Disclosure Standard)**

- Key risks disclosed (worst case + most likely)?
- Reversibility assessment provided?
- Cascade obligations identified?
- Exit/recourse options specified?

### **Documentation**

- Participation evidence tamper-resistant?

---

**VERDICT:**

| Result | Condition |
| --- | --- |
| **VALID — basis: direct** | Direct: Exercise Yes AND Authorization Content Yes, plus clear Opportunity and unimpaired Capacity |
| **VALID — basis: delegated** | Delegated: items 1–6 all Yes, plus clear Opportunity and unimpaired Capacity for the delegate on this closure |
| **INVALID** | Neither branch resolves affirmatively |

**If INVALID, classify Authorization Status** (Section 6, Step 2e) before proceeding to Defensive Exception:

| Authorization Status | Test |
| --- | --- |
| ☐ **WITHHELD** | Standing-holder had genuine opportunity and capacity, and declined (refused/abstained) |
| ☐ **UNAVAILABLE** | Authorization is genuinely infeasible for this standing-holder and this closure — not merely unsought |

WITHHELD cannot be reopened by urgency or unavoidability at any later step — only a satisfied Defensive Exception is an independent route (Section 6, Step 2e, Withheld Authorization Boundary). UNAVAILABLE may, if Structural Unavoidability and Decision Necessity both independently apply, produce a REQUIRED Decision Status without changing the Permissibility Verdict (Section 6, Step 4) — impermissible and required are not contradictory.

---

## **23. Glossary**

| Term                               | Definition                                                                                |
| ------------------------------------- | ---------------------------------------------------------------------------------------------- |
| **Agent**                          | Entity with phenomenology, agency, and anticipation; threshold-based, binary standing     |
| **Agent-relative weighting**       | Closure evaluated relative to affected agent's own future model                           |
| **Anticipation**                   | Capacity to represent future states to oneself                                            |
| **Authorization Content**          | Whether the content of an agent's exercised participation constitutes affirmative consent to the specific closure being evaluated — distinct from whether an exercise occurred at all |
| **Authorization Status**           | Classification of a standing-holder's participation as AUTHORIZED, WITHHELD (genuine opportunity and capacity existed; the standing-holder declined), or UNAVAILABLE (valid authorization is genuinely infeasible, not merely unsought). See Section 6, Step 2e. |
| **Authorization Unavailable**      | An Authorization Status indicating valid authorization could not have been obtained for this standing-holder and this closure. Supplies no authorization and no standing transfer; may, with Structural Unavoidability and Decision Necessity, produce a REQUIRED Decision Status without changing the Permissibility Verdict. |
| **Cascade**                        | Chain of closures triggered by initial action                                             |
| **Closure**                        | Reduction in accessible future states                                                     |
| **Coercion**                       | Participation impairment via threats making non-participation unreasonably costly         |
| **Collective Resolution Safeguards** | Institutional Representation, Bounded Scope, Exit Viability, Amendment & Contestability, and Proportionality — constrain collective closure; do not themselves authorize it |
| **Commons**                        | Non-excludable, collectively accessible resource; protected by mediated standing          |
| **Confirmed agent**                | Entity clearly meeting all three threshold criteria                                       |
| **Decision Necessity**             | The point at which continued non-decision would itself generate greater non-participatory closure than acting, triggering a requirement to choose the least-closing available option. Does not itself authorize the closure chosen. |
| **Decision Status**                | An axis independent of the Permissibility Verdict, recording whether a decision is REQUIRED (Structural Unavoidability and Decision Necessity both apply) even where the Permissibility Verdict is IMPERMISSIBLE. Never changes IMPERMISSIBLE to PERMISSIBLE. See Section 6, Step 4. |
| **Default-to-agent**               | When threshold uncertain, treat as provisional agent                                      |
| **Defensive closure**              | Closure preventing greater non-participatory closure (requires safeguards)                |
| **Delegation**                     | Transfer of participation exercise (not standing) to another agent; always revocable, since standing was never transferred |
| **Dependency trap**                | Participation impairment via manipulated prior position                                   |
| **Exercise**                       | The factual event of an agent doing something via the appropriate modality — distinct from Authorization Content, which asks what that act's content actually authorizes |
| **Exit viability**                 | Exit meaningful only if closure of exiting < closure of staying; measures refusal capacity, not participation |
| **Impairment**                     | Condition reducing capacity to anticipate, refuse, or modify                              |
| **Institutional Representation**   | A claim made by an institution on behalf of agents it represents, serves, governs, or coordinates; does not itself constitute standing or authorize closure |
| **Irreversible closure**           | Closure of permanently inaccessible futures                                               |
| **Material closure**               | Closure of physical, economic, or social futures                                          |
| **Mediated standing**              | Standing over futures mediated by substrates (ecosystems, infrastructure, commons); attributes standing, does not itself authorize closure |
| **Minimum Agency Threshold Test**  | Three-question test for agent classification                                              |
| **Minimum disclosure standard**    | Required information packet for irreversible closures                                     |
| **Participation**                  | Agent's exercise of standing over closure affecting their futures, where the content of that exercise authorizes the closure |
| **Participation modality**         | Method by which agent exercises participation (varies by agent type)                      |
| **Phenomenology**                  | Capacity to experience states as better or worse                                          |
| **Proportionality**                | Defensive closure must be ≤ prevented closure                                             |
| **Provisional agent**              | Entity with uncertain threshold status; treated as agent, monitored                       |
| **Representational closure**       | Distortion of agent's model of possibility space                                          |
| **Reversible closure**             | Closure of temporarily inaccessible futures                                               |
| **Standing**                       | Relationship between agent and closures affecting their futures; non-transferable, binary |
| **Structural defensive exception** | Defense against systemic threats; requires enhanced safeguards, all seven of which must pass |
| **Structural Unavoidability**      | A conflict in which every feasible option closes some agent's futures; identifies the least-closing option but does not make that option permissible |
| **Substrate**                      | Non-agent system mediating many agents' futures                                           |
| **Sunset and review**              | Requirement that defensive closures be time-bounded and periodically reviewed             |
| **Tamper-evidence**                | Participation records must be archivable, reviewable, tamper-resistant                    |
| **Valid participation**            | Participation via appropriate modality with unimpaired capacity, actual exercise, AND authorization content — direct, or through delegation that remains operative for the closure |

---

# **APPENDIX: VERSION HISTORY**

## **v1.0 (Initial Release)**

- Three primitives (Agent, Closure, Standing)
- Single axiom
- Two hardenings (PVC, RCR)
- Six derivations
- Four-step protocol
- Six defensive safeguards
- Domain applications

## **v1.1 Amendments**

| Amendment                      | Description                                                     |
| --------------------------------- | ------------------------------------------------------------------ |
| Agent-Relative Weighting       | Closure evaluated relative to affected agent's own future model |
| Default-to-Agent Principle     | Uncertain cases treated as agents                               |
| Mediated Standing Rule         | Substrate closures count as agent closures                      |
| Minimum Disclosure Standard    | Required information for irreversible closures                  |
| Tamper-Evidence Principle      | Participation records must be tamper-resistant                  |
| Exit Viability Test            | Exit meaningful only if Closure(exit) < Closure(staying)        |
| Voice Viability Standards      | Five standards for participation approximation                  |
| Safeguard 7: Sunset and Review | Defensive closures must be time-bounded                         |
| Tier 1 RCR Check               | Representational closure check in Quick Check                   |

## **v1.2 Amendments**

| Amendment                      | Description                                                        |
| --------------------------------- | ------------------------------------------------------------------------- |
| Participation Modality         | Standing is binary; participation modality varies by agent type    |
| Minimum Agency Threshold Test  | Three-question formal test replacing "surprise test"               |
| Provisional/Confirmed Agent    | Two-tier classification for uncertain cases                        |
| Structural Defensive Exception | Enhanced safeguards for systemic/non-agent threats                 |
| Commons Protection             | First-participation priority does not apply to commons/substrates  |
| Animal Standing Clarification  | Animals are confirmed agents with equal standing; modality differs |

## **v1.2.1 Amendments (Final)**

| Amendment               | Description                                                                     |
| --------------------------- | ------------------------------------------------------------------------------------ |
| Recursion Clarification | Added "On Ambiguity and Recursion" section; recursion bounded by closure itself |
| Framework Character     | Added Section 20 on judgment, normativity, and completeness                     |
| Final Polish             | Minor clarifications throughout; version marked as final                        |

## **v1.3 Amendments**

| Amendment | Description |
| --- | --- |
| **Standing Terminology (Amendment 01)** | Retired the "Standing Hierarchy" (Direct > Delegated > Institutional) formulation, which implied institutions could hold a graded form of standing. Replaced with a flat ontology: Direct Standing, Delegated Participation, and Institutional Representation, with an explicit resolution rule that direct standing cannot be overridden by either. D4 (Cascade Responsibility) reworded throughout to describe *responsibility* attributable to an initiating action rather than *standing obligations*, closing a latent conflict with D6's non-transferability. |
| **Collective Decision Necessity (Amendment 02)** | Eliminated "Participation Approximation" and "Voice Viability" as substitute-authorization mechanisms for policy-scale closure — no amount of governance quality converts non-participatory closure into participatory closure. Established that Decision Necessity (the point at which continued non-decision itself generates escalating closure) requires a decision but does not authorize the closure made. Renamed the "Five Governance Requirements" to **Collective Resolution Safeguards**, explicitly non-authorizing, constraining rather than legitimating collective closure. Exit Viability retained as a measure of refusal capacity only, with its prior authorization-adjacent framing ("exit is a form of participation") removed. |
| **Participation Authorization and Delegated Exercise (Amendment 03)** | Identified and repaired a core protocol defect: Step 2 tested only whether an agent had *exercised* a participation modality, without separately testing whether the *content* of that exercise *authorized* the closure — meaning a refusal or an abstention could be mechanically read as satisfying validity. Step 2d/2e rewritten as an explicit branch structure (Direct / Delegated / Neither) distinguishing Exercise from Authorization Content. D6 (Delegation Asymmetry) given an expanded practical-implication note covering prospective delegation, decision envelopes, the delegate-exercise rule, accountability, and revocability. The Quick Validity Checklist, Tier 1/2 Quick Checks, and both Closure Analysis Templates updated to match, with Template B/C explicitly required to preserve heterogeneous per-standing-holder authorization states rather than aggregating them into a single group verdict, and Template C required to track authorization fresh at each stage of a cascade rather than allowing an upstream authorization to propagate downstream. |
| **Authorization Status and Decision Status (Amendment 04)** | Resolved a latent contradiction between D6, Section 2's participation-modality tables, and Section 12's Care Relationships: the specification described ordinary non-voluntary care (infants, animals, agents with no capacity to ever delegate) as "delegated participation," while D6 requires a standing-holder's own prior delegating act — a category error, since incapacity to delegate is not incapacity to have authorization made unavailable. Resolved by separating two previously conflated facts into independent axes. **Authorization Status** (Section 6, Step 2e) now distinguishes WITHHELD (capacity existed; the standing-holder declined) from UNAVAILABLE (authorization was genuinely infeasible, not merely unsought) — WITHHELD can never be reopened by urgency; only a satisfied Defensive Exception is an independent route. **Decision Status** (Section 6, Step 4) is independent of the Permissibility Verdict: where Authorization Status is UNAVAILABLE and both Structural Unavoidability and Decision Necessity apply, a closure may be simultaneously REQUIRED and IMPERMISSIBLE — obligation without authorization, not a fourth verdict and not a weakening of the axiom. The shorthand "Required but Non-Authorized" is reserved for this individual-incapacity configuration and is explicitly withheld from collective and policy-scale closures, preserving Amendment 02's anti-softening architecture there. Closure-specific participation (a standing-holder's valid refusal of an embedded component, such as manner of handling, within an otherwise-UNAVAILABLE overall closure) remains independently binding regardless of the overall closure's status. Caretaker and guardian language throughout Sections 2, 4, and 12 corrected to no longer describe non-voluntary care as delegation. Conceptual spine: *incapacity does not create authority; it can make authorization unavailable — those are not the same proposition.* |

---

## **Citation**

Decision Topology: A Framework for Ethics Under Irreversibility, Yusuf Abdulla Shunan, yusufshunan.com

Version 1.3

---

## **License**

© 2024–2026 Yusuf Abdulla Shunan. All rights reserved.

This work is licensed under the Creative Commons Attribution 4.0
International License (CC BY 4.0).

You are free to:

- Share — copy and redistribute in any medium or format
- Adapt — remix, transform, and build upon the material

Under the following terms:

- Attribution — You must give appropriate credit to Yusuf Abdulla Shunan, provide a link to the license, and indicate if changes were made.

Full license: <https://creativecommons.org/licenses/by/4.0/>

---

*One Axiom. Three Primitives. Four Steps.*

*Standard Defense: Seven Safeguards. Structural Defense: Seven Enhanced Safeguards.*

*Standing is binary. Participation modality varies. Exercise is not authorization. Recursion is bounded by closure.*

*Ethics as topology management.*

*Necessity to decide is not permission to close. Waiting is never free.*