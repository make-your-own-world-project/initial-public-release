# Keeping Reasoning Inspectable

![Independent specialists tracing accepted and rejected reasoning paths back to exact evidence](assets/reasoning-engine-inspectable-path.png)

## Inspectable reasoning

The reasoning engine is a sequence of bounded specialists and deterministic
projections. Its purpose is to build an inspectable proposition-and-relation graph
from exact source evidence. It is not a generic completion prompt asked to infer the
whole document.

```text
EXACT EVIDENCE ITEMS AND SOURCE SPANS
        |
DISCOURSE AND REFERENCE PREPROCESSING
        |
PROPOSITION AND RELATION CANDIDATES
        |
ARGUMENT RELATION CLASSIFICATION
        |
TYPED PROVENANCE GRAPH
        |
DETERMINISTIC DEPENDENCY AND WHY PROJECTION
        |
PRODUCT-SPECIFIC SELECTION AND RECONSTRUCTION
        |
INDEPENDENT VERIFIER AND RECEIPT
```

## Linguistic preprocessing

Evidence is divided into bounded, gapless slices tied to immutable source identities
and character offsets. Coreference analysis proposes reference chains. Rhetorical
Structure Theory analysis proposes discourse structure and operand pairs. Oversized
or unbound structures remain explicit rather than being silently truncated or mapped
to the first matching phrase.

These tools expose linguistic structure. They do not establish personal motive or
argument truth by themselves.

## Argument relation classification

Discourse-derived proposition pairs are classified into a small relation inventory,
including support, conflict, equivalence, or no authoritative relation. Every attempt
retains its operands, score distribution, model identity, and disposition. A
below-threshold result remains visible and does not create an edge.

Accepted relations become directed graph edges with exact source spans and method
identity. Ambiguous source binding fails closed.

## Graph projection

The dependency and “why” view is a deterministic projection of already classified
edges. It may expose a support or conflict chain in a more usable form. It may not
invent new reasons, stakes, or consequences and claim that a specialist derived
them.

The graph can be exported through established argument interchange structures, but
an interchange representation is not a second truth store and does not require a
model or accelerator.

## Resource boundaries

Coreference and discourse parsing can use leased accelerator capacity because those
models are loaded for bounded preprocessing jobs. Argument classification is designed
to run through a compact specialist inference path. Graph projection, selection,
constraint solving, provenance checks, and receipt verification are ordinary CPU
work.

The design avoids keeping every model resident and prohibits starting duplicate
workers to evade the shared lease mechanism.

## What the verifier proves, and does not prove

The verifier can prove that required components ran, exact spans survived, graph
projection is reproducible, product bindings are consistent, and promoted bytes match
the accepted bundle. It can reject fabricated manifests, unsupported prose, wrong
edge direction, hidden fallbacks, and missing capabilities within its policy.

Structural correctness does not automatically prove that every relation label agrees
with expert human judgment. Relation-quality evaluation requires independently
labelled examples and precision, recall, direction, and calibration analysis. That
semantic-quality gate remains a distinct responsibility.

This boundary also keeps a downstream external model from becoming the reasoning
authority. It may receive supported propositions and typed relations for a bounded
realization task, while the evidence, attempts, graph, and acceptance criteria remain
independently available. Fluency does not take ownership of the reasoning that made
the payload useful.
