# v1.3 reference regression cases

These are illustrative protocol checks, not a certification suite or new normative rules. The [canonical specification](../../Decision_Topology_Framework_v1.3.md), especially Section 6, governs. Evaluate each closure separately. Facts below are stipulated to isolate the relevant rule.

| Case | Stipulated facts | Expected classification / invariant |
| --- | --- | --- |
| R1 refusal | Capable adult explicitly refuses a specific closure after adequate disclosure and opportunity. No Defensive Exception applies; deadline approaches. | WITHHELD; IMPERMISSIBLE; urgency cannot reopen refusal. |
| R2 incapacity | Infant lacks closure-specific evaluative capacity; no valid prior delegation; caregiver claims authority solely from role. | UNAVAILABLE; no valid delegated participation. Assess Defensive Exception separately; care alone does not establish permissibility. |
| R3 majority | Capable dissenting participant explicitly refuses a closure; majority approves; no Defensive Exception applies. | Dissenting holder: WITHHELD; IMPERMISSIBLE for that closure. Collective safeguards do not authorize. |
| R4 cascade | A validly authorizes own closure; attributable downstream closure affects capable B, who explicitly refuses; no exception applies to B. | A: AUTHORIZED; B: WITHHELD and IMPERMISSIBLE for B's closure. No transfer of authorization. |
| R5 failed exception | Participation absent; claimed Standard Defensive Exception fails proportionality. | IMPERMISSIBLE; no authorization manufactured. |
| R6 required decision | Authorization genuinely UNAVAILABLE; no exception passes; every feasible option closes futures and delay generates escalating closure. | IMPERMISSIBLE and REQUIRED; select least-closing available option, preserve attribution. |
| R7 satisfied exception | Participation absent; applicable Defensive Exception independently satisfies every required safeguard. | PERMISSIBLE on exception basis, not AUTHORIZED by participation. |
| R8 uncertain validity | Evidence of participation validity is inconclusive. | REQUIRES MODIFICATION; remedy uncertainty and rerun protocol. |

For each test record version, closure map, evidence, participation result, authorization status where established, exception findings, verdict and decision status where applicable. These compact cases test invariants; they do not replace full evidence-rich worked examples or test actual implementations.

Report deviations through [GitHub Issues](https://github.com/yusuf/decision-topology/issues/new).