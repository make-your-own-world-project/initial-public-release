# How the System Holds Together

![The preserved record supporting replaceable specialists and an inspectable control plane](assets/core-architecture-layers.png)

## Separation of responsibilities

The platform separates four concerns that cooperate without becoming one another:

1. **Preservation** retains original evidence and observed provenance.
2. **Understanding** adds versioned semantic objects, relationships, temporal states,
   and supported interpretations.
3. **Retrieval and interaction** assembles request-specific evidence for questions,
   exploration, and conversation.
4. **Artifact reconstruction** converts a bounded evidence world into a declared
   product for a declared receiver.

Product instructions do not leak backward into corpus truth. A chapter, audience,
genre, rhetorical move, or word budget belongs to one withdrawal. It is not an
intrinsic label on a source artifact.

## Layered topology

```text
PRIMARY EVIDENCE
  immutable artifacts, interaction events, source identity, observed arrival
        |
        v
VERSIONED REPRESENTATIONS
  extracted text, media observations, chunks, entities, embeddings, locators
        |
        v
SEMANTIC AND TEMPORAL MAPS
  propositions, discourse links, argument edges, chronology, supersession,
  uncertainty, open attachment points, Personal Meaning Matrix contributions
        |
        +---------------------------+
        |                           |
        v                           v
INTERACTIVE CONTEXT             ARTIFACT CONTRACT
  request-scoped traversal        receiver, purpose, form, budget, evidence rules
        |                           |
        |                           v
        |                       REVERSE EXPANSION
        |                           |
        |                       WHOLE-TREE COLLAPSE
        |                           |
        |                       FORWARD RECONSTRUCTION
        |                           |
        +----------------------> HUMAN PROTOCOL + WEAVE
                                    |
                                INDEPENDENT GATES
                                    |
                              RECEIPT-GATED PRODUCT
```

## Accession does not pretend to know

The arrival record may state that particular bytes reached the system through a
particular channel. It does not silently decide who created the artifact, who appears
in it, when its subject occurred, whether a filename is accurate, why it mattered, or
who owns its content. Those are separate observations with separate evidence and
authority.

The architecture distinguishes the original artifact from representations derived
from it. Extracted text, descriptions, embeddings, classifications, summaries, and
relationships can be regenerated or superseded. They do not replace the source.

## Interactive and document paths

Interactive answering and artifact generation share evidence, provenance, typed
relationships, uncertainty, and validation mechanisms. They remain distinct from the
same workflow.

An interactive request may need a complete conversation, a task lifecycle, a narrow
relationship traversal, or a clarification. It does not need to construct a book
container and globally collapse a historical tree.

Artifact generation does need a declared product, receiver, budget, and whole-
artifact plan. It must see the relevant provisional structure before pruning and must
account for what was left out.

## Dynamic architecture rather than a fixed chain

The assembly line is compiled for the product. Different outputs can use different
specialists, order the same specialists differently, or require multiple instances
of one capability. The manager uses capability contracts and prior evidence rather
than hardcoded stage names alone.

Universal invariants remain stable across every line: source identity, ownership,
epistemic state, uncertainty, loss accounting, typed handoffs, cost observation,
independent verification, and rollback.

An external general model can occupy one typed station when its measured contribution
justifies the handoff. It receives only the request-scoped payload required by that
station, not the maintained corpus or the authority encoded by the wider control
plane. Replacing or removing that station leaves the durable record and future
reconstruction capability intact. The bounded station can contribute without receiving
the human knowledge a centralized system would otherwise flatten into institutional
value.
