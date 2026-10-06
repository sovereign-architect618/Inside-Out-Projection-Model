# IOM Current Recursive Relationship Maps

**Status:** representative maps for review  
**Basis:** the most current recovered recursive mechanism, with historical mathematical candidates shown separately from the accepted relationship structure

**Reading rule:** solid structural relationships represent the recovered current architecture; equations and diagnostics in the companion formalization remain proposals unless explicitly marked otherwise. Dotted candidate branches do not acquire canonical status merely by appearing on a map.

---

## Map 1 — Current architecture and return path

```mermaid
flowchart TD
    H["Higher-dimensional geometry / source-side structure"]
    B["Dimensional boundary: collective content + rules"]
    L1["L₁: boundary-side transformation"]
    TC["T_C: Clifford-torus relational carrier"]
    L2["L₂: pre-eigenstate transformation"]
    PA["Ψ/𝒜: eigenstate + aperture/antenna"]
    O["Observable projection / experience"]

    H --> B --> L1 --> TC --> L2 --> PA --> O
    PA -. "integration and non-integration records" .-> L2
    L2 -.-> TC
    TC -.-> L1
    L1 -.-> B
```

Solid arrows show the forward projective order. Dotted arrows show return information; they do not assert literal inverse operators.

---

## Map 2 — One local recursive encounter

```mermaid
flowchart TD
    E["Encountered information"]
    OR["Orientation: desire + willingness"]
    A["Aperture / admission"]
    D["Discernment"]
    J["Integration"]
    G["Geometric relevance to current deficit"]
    U["Updated eigenstate structure"]
    R["Unresolved return record"]

    E --> OR --> A --> D --> J --> G
    G -->|"nonredundant contribution"| U
    A -->|"not admitted"| R
    D -->|"rejected or misclassified"| R
    J -->|"not integrated"| R
    G -->|"integrated but redundant"| R
```

This map preserves the distinction between failure to admit, failure to discern, failure to integrate, and successful integration that does not contribute to the presently missing geometry.

---

## Map 3 — Structural completion and unresolved loops

```mermaid
flowchart TD
    G["Required geometry graph Gᵢᵏ"]
    SCC["Strongly connected components: local recursive loops"]
    DAG["Condensation graph: global directional order"]
    C["Accepted nonredundant contributions"]
    Q["Loop and graph completion Γᵢᵏ"]
    X["Expansion Uᵢᵏ → Uᵢᵏ⁺¹"]

    G --> SCC
    G --> DAG
    SCC --> Q
    DAG --> Q
    C --> Q
    Q -->|"Γ = 1"| X
    Q -->|"Γ < 1"| G
```

Local cycles and an overall arrow can coexist. Unresolved loops remain active; completed loops are incorporated into structure rather than erased.

---

## Map 4 — Recursive stability and entrainment

```mermaid
flowchart TD
    R["Unresolved vector rₙ"]
    B["Carry-forward and coupling matrix B"]
    H["Resolution matrix H: efficiency × success"]
    M["Effective update M = B − H"]
    S["Spectral test ρ(M)"]
    T["Target dominant unstable mode"]
    C["Contracting recursive structure"]

    R --> M
    B --> M
    H --> M
    M --> S
    S -->|"ρ ≥ 1"| T
    T -->|"change processing or coupling"| H
    S -->|"ρ < 1"| C
```

Entrainment need not copy another eigenstate or maximize every variable. It can improve a bottleneck, increase resolution efficiency, or weaken a self-reinforcing coupling aligned with the dominant unstable mode.

---

## Map 5 — Individual influence to boundary transition

```mermaid
flowchart TD
    I["Individual completed recursion"]
    V["Changed boundary-relevant contribution vᵢ"]
    K["Aggregate boundary content K"]
    GD["Aggregate completion test Γ_D"]
    C["Content update; same governing rules"]
    T["Boundary-rule transition Θᵏ → Θᵏ⁺¹"]

    I --> V --> K --> GD
    GD -->|"incomplete"| C
    GD -->|"aggregate condition complete"| T
    C --> K
```

An individual can change its contribution and thereby inform collective content. Boundary-rule authority remains an aggregate operation.

---

## Map 6 — Scale-recursive hierarchy

```mermaid
flowchart TD
    E["Encounter contribution cᵢ"]
    U["Individual structure ΔUᵢ"]
    K["Aggregate structure ΔK_D"]
    B["Boundary rule/state ΔΘ"]
    N["New conditions for next recursion"]

    E --> U --> K --> B --> N
    N --> E
```

The abstract completion rule may repeat across scale, but each scale can use a different state space, deficit, and completion functional.

---

## Map 7 — Conditional inverse operation

```mermaid
flowchart TD
    S["Current state + conditions + relationships"]
    V["Context-dependent viable region"]
    O["Admissible operation family"]
    P["Predict next state under each operation"]
    M["Minimize distance to viability + operation cost"]
    U["State-specific operation u*"]

    S --> V
    S --> O
    O --> P
    V --> M
    P --> M
    M --> U
```

This is the current representative meaning of inverse operation: solve backward for a conditionally viable corrective operation. It is not the reciprocal \(1/D\) of a discrepancy score and does not prescribe one ideal state for every system.

---

## Map 8 — Bounded asymmetric entropy/coherence dynamics

```mermaid
flowchart LR
    R["Rigidity / stagnation"]
    W["Viable moving window"]
    L["Loss of organization"]

    R <-->|"state-dependent correction"| W
    W <-->|"state-dependent correction"| L
```

The viable regime is neither equality nor rest. It is a bounded nonequilibrium region in which enough coherence remains to preserve organization and enough entropy/variation remains to sustain differentiation and movement.

---

## Map 9 — Observation and representation layers

```mermaid
flowchart TD
    X["Originating event or information"]
    S["Signal available to eigenstate"]
    R["Local representation"]
    I["Interpretation / source attribution"]
    J["Integration or non-integration"]
    H["Updated history and processing state"]

    X --> S --> R --> I --> J --> H
```

The event, available signal, constructed representation, interpretation, and integration outcome remain separate. An internally generated component and an external component may both participate in one experienced event.

---

## Map 10 — Optional mathematical realizations

```mermaid
flowchart TD
    C["Current relationship architecture"]
    W["Winding / Gram aggregate"]
    P["Prime finite-torus selector"]
    H["Hodge experimental pipeline"]
    Z["Zeta / variational selector"]
    T["Temporal and spatial projective maps"]

    C -. "candidate realization" .-> W
    C -. "candidate realization" .-> P
    C -. "candidate realization" .-> H
    C -. "candidate realization" .-> Z
    C -. "candidate realization" .-> T
```

These families are evaluated independently. Failure or replacement of one does not erase the accepted recursive relationships.

---

## Compact relationship ledger

| Relationship | Current treatment |
|---|---|
| `Boundary ≠ L₁ ≠ T_C ≠ L₂ ≠ Ψ/𝒜` | Preserved architectural constraint |
| Torus between two lenses | Current recovered topology |
| Aperture belongs with eigenstate | Current recovered topology |
| Integration and non-integration both return information | Current recursive mechanism |
| Integration ≠ homogenization | Current recursive mechanism |
| Successful integration ≠ expansion contribution | Current recursive mechanism |
| Geometry determines requirements; processing/history determine traversal | Current recursive mechanism |
| Recursive depth ≠ required count ≠ elapsed count | Current recursive mechanism |
| Entrainment ≠ copying | Current recursive mechanism |
| Individual influence ≠ boundary authority | Current collective constraint |
| Content update ≠ governing-rule transition | Current collective constraint |
| Dynamic balance ≠ equality or fixed equilibrium | Current discrepancy/inverse interpretation |
| Same observable output ≠ same internal mechanism | Current processing constraint |
| Winding/Gram, prime, Hodge, ζ, and temporal operators | Candidate mathematical realizations |
