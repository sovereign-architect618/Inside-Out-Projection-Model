# IOM Repository Workspace Status

**Workspace established:** 2026-10-06  
**Current status:** recovery, clarification, and review  
**Not yet:** a final engineering handoff, a canonical replacement release, or a silent rewrite of the published v12.5 materials

## What this repository now represents

The repository's `main` branch is preserved as the public v12.5 historical snapshot released on 2026-08-12. Its `README.md`, `engine.py`, license, and commit history remain unchanged.

The `workspace/*` branches provide a separate development area for reconstructing the Inside-Out Model (IOM) from the full surviving record. Their purpose is to:

- recover relationships and mechanisms that were omitted, compressed, displaced, or misdefined in the published briefing;
- clarify the intended architecture without rewriting the historical release;
- preserve competing, unresolved, and historically important equation families;
- distinguish author-originated concepts and corrections from AI-generated formalizations, interpretations, or notation;
- compare the recovered architecture with the released repository before any future integration decision; and
- prepare reviewable material for a later engineering handoff without treating these branches as that handoff.

The current reconstruction is a recovery and clarification of the model's intended relationships, not evidence that the model was newly redesigned after publication.

## Branch roles

| Branch | Role | Relationship to `main` |
|---|---|---|
| `main` | Preserved v12.5 public release | Historical snapshot; unchanged |
| `workspace/recovery-foundation` | Public workspace charter and two cohesive theory summaries | Additive branch created from the current `main` head; the full forensic recovery map remains private pending review |
| `workspace/post-github-formalization` | Proposed equations and representative relationship maps based on the recovered recursive architecture | Additive child branch created from `workspace/recovery-foundation` |

No branch is merged merely because it exists. Review, correction, and explicit approval precede any future integration into `main` or a successor release branch.

## Interpretation and provenance rules

1. **Omission is not abandonment.** Absence from a later briefing may reflect audience, scope, condensation, relocation, or version loss.
2. **Original contribution and formalization remain distinct.** A useful AI-generated equation does not become author-originated through later reuse.
3. **Relationships take precedence over inherited labels.** Where later summaries retained components but altered their placement or function, the recovery record preserves the corrected relationship and documents the discrepancy.
4. **Conflicts remain visible.** Incompatible equations, terminology, and proposed implementations are retained with status labels rather than silently reconciled.
5. **Current architecture begins the reconstruction.** Earlier materials are used to restore missing definitions, chronology, code, equations, and links—not to overwrite the most recently clarified architecture without evidence.
6. **Empirical and conceptual tracks remain separate but connected.** Testable claims can be specified and evaluated while currently untestable mechanisms are examined for internal logic, constraints, correspondence, and explanatory structure.

## Status vocabulary

| Label | Meaning |
|---|---|
| `CORE-RELATION` | Recovered relationship currently treated as part of IOM |
| `SYNTHESIS-DRAFT` | New notation or equation proposed to express a recovered mechanism |
| `HISTORICAL-CANDIDATE` | Earlier or post-release proposal retained for investigation |
| `UNRESOLVED/CONFLICT` | Incomplete, incompatible, disputed, or explicitly not adopted |

## Publication boundary

The full forensic recovery map is not included on the public branches. It remains a private working artifact because its chronology, source annotations, and contextual detail require a separate privacy and publication review. Public omission of that map does not reduce its evidentiary or architectural role in the reconstruction.

## Current recovered architecture

The working information pathway is:

$
\text{Higher-Dimensional Geometry}
\rightarrow
\text{Dimensional Boundary}
\rightarrow
L_1
\rightarrow
T_C
\rightarrow
L_2
\rightarrow
\Psi/\mathcal A
\rightarrow
\text{Observable Projection},
$

with integration and non-integration both capable of returning information through the recursive structure. The boundary, first lens, Clifford-torus carrier, second lens, and eigenstate/aperture are retained as distinct mechanisms.

## Review order

1. Review the two public cohesive summaries for conceptual fidelity.
2. Privately review the full recovery map and chronology before deciding which portions are suitable for later publication.
3. Review the recursive relationship maps.
4. Review each proposed equation against its provenance and status.
5. Resolve definitions, tests, and conflicts before preparing the engineering handoff.

This file describes the workspace contract. It does not declare the reconstruction complete and does not supersede the preserved historical record.
