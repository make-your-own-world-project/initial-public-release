# What Is Running Now

![The local machinery organized by responsibility around a shared controlled backbone](assets/public-machinery-catalog.png)

## How to read this catalog

The catalog is the public counterpart of the Datacenter view in Mission Control. It
describes what each cog contributes and what would be lost if it disappeared,
without publishing private addresses, machine layout, credentials, file paths,
or operating cadence. The live graph remains the operational source of truth.

Component status matters. A tool may be active, retained as a source system,
evaluated but not adopted, or a retired predecessor. Presence in this catalog
does not grant a component authority beyond its stated role.

That rule includes external frontier capability. When used, it occupies a bounded
station and receives a purpose-built payload rather than unrestricted access to the
maintained corpus. The payload supports the declared operation but omits the durable
state needed to reconstruct the wider system or independently produce future
withdrawals. The station receives work, not custody of the human record from which a
centralized institution could extract durable value.

## Ways into and around the system

### Robot Brain (LibreChat)

**Responsibility.** Provide the replaceable human-facing conversation window. It carries requests and responses while durable memory, retrieval, reasoning, and verification remain in the services beneath it.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

**Principal public tools.** [LibreChat](https://github.com/danny-avila/LibreChat), [Node.js](https://github.com/nodejs/node)

### Conversation Splitter

**Responsibility.** Notices when a chat turned into two subjects and offers to file the finished one separately.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

**Principal public tools.** [FastAPI](https://github.com/fastapi/fastapi)

### Mission Control

**Responsibility.** The window onto the machine: what is running, what requires attention, and what it is doing right now. At this publication boundary, its status page reports all monitored systems operational on the local installation.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** Operational status reports service state; accepted artifacts and receipts establish the separate execution and semantic evidence boundaries.

**Principal public tools.** [FastAPI](https://github.com/fastapi/fastapi), [Graphviz](https://gitlab.com/graphviz/graphviz), [Psycopg](https://github.com/psycopg/psycopg)

### Semantic Router

**Responsibility.** Route bounded requests to the appropriate local engine and require explicit authorization before using external inference. Expensive capability is selected only when the request justifies its measured cost.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

**Principal public tools.** [FastAPI](https://github.com/fastapi/fastapi). Envoy and vLLM Semantic Router remain credited in the source index as inspected or retired predecessors, not current runtime dependencies.

### Complete Agent Histories

**Responsibility.** Preserve complete, ordered agent event streams as interaction evidence, including human turns, assistant turns, tools, errors, and corrections. The histories record what occurred; they do not turn agent statements into verified facts.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** Supplies only what its source and provenance establish; downstream interpretation remains separate.

### Project Documents

**Responsibility.** Preserve the private design, evidence, and project records that explain why the platform exists and how its architecture changed. Public products consume reviewed derivatives rather than exposing the private document location.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** Supplies only what its source and provenance establish; downstream interpretation remains separate.

### Vikunja

**Responsibility.** Preserve the external task system as an independently owned source that predates the platform. Integration may read authorized task evidence without absorbing the task system into the corpus or changing its lifecycle.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** Supplies only what its source and provenance establish; downstream interpretation remains separate.

**Principal public tools.** [Vikunja](https://github.com/go-vikunja/vikunja)

## Preservation and retrieval

### Knowledge Intake

**Responsibility.** The way things get in. Drop a document, an export, a pile of notes, and it lands somewhere findable instead of nowhere.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

### MongoDB

**Responsibility.** Holds the conversations themselves, as they were said.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** Availability and integrity are necessary; stored data does not interpret or verify itself.

**Principal public tools.** [MongoDB](https://github.com/mongodb/mongo)

### PostgreSQL

**Responsibility.** Hold durable structured project records, derived state, and search indexes intended to outlive replaceable application services. Stored records retain distinct authority and provenance rather than becoming one undifferentiated memory.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** Availability and integrity are necessary; stored data does not interpret or verify itself.

**Principal public tools.** [PostgreSQL](https://github.com/postgres/postgres), [pgvector](https://github.com/pgvector/pgvector)

## Reasoning and reconstruction

### Argument Relation Classifier

pinned AMF_ARI OpenVINO CPU classification of inference, conflict, rephrase, or no relation

**Responsibility.** Classify the relationship between two supplied propositions; it does not create either proposition or infer personal motive. Example: distinguish one statement supporting another from one contradicting it, or return no supported relation.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

**Principal public tools.** [AMF ARI RoBERTa OpenVINO model](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8)

### Human Artifacts

**Responsibility.** Define the human-facing products that the assembly line can construct. Each product carries its own receiver, purpose, structure, evidence policy, and delivery contract rather than sharing one generic outline.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

### Grounding + Delivery Validation

independent receipt gate over fidelity, provenance, loss, invention, weave, and comprehension checks

**Responsibility.** Independently check that the artifact preserves supported meaning and satisfies its declared delivery contract before release. Example: reject a readable paragraph that invents a conclusion, and separately reject a grounded document whose structure is unusable for its target reader.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

### Audience Resolution

receiver state, prerequisites, register, and relevance

**Responsibility.** Describe what the intended receiver is expected to know, need, and tolerate while keeping assumptions explicit. Example: require a homeowner guide to explain pH before using abbreviations familiar to a pool technician.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

### Whole-Tree Collapse + Packets

container-constrained partition, selection, gains, and losses

**Responsibility.** Select and balance what can fit the requested artifact while recording what was omitted and preserving the tree's meaningful shape. Example: keep each major branch represented in a 1,000-word article instead of letting the largest source branch consume the whole budget.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

**Principal public tools.** [submodlib](https://github.com/decile-team/submodlib), [kneed](https://github.com/arvkevi/kneed)

### Compact Working Model

portable request-scoped carrier for selected units, relations, trajectories, source blocks, plans, handles, and handoff ledgers

**Responsibility.** Package the selected facts, relationships, chronology, uncertainty, failures, and source handles into a portable job-specific context. Example: give the editor the pool-maintenance chain and why its steps connect without loading the entire corpus or dropping the links.

**Must preserve.** source_spans; relation_ids; chronology; uncertainty; failures; supersession; unknowns

**Resource shape.** CPU and RAM proportional to bounded selection; no GPU or lease

**Boundary.** quality is bounded by upstream relationship and deposit-state coverage

### Delivery Mechanics

register, modes, weave profiles, pacing, density, and deslop controls

**Responsibility.** Supply measured delivery constraints, such as pacing, density, register, and weave trajectory, for this product and audience. Example: give a children's explanation shorter packets and a different recurrence pattern than a technical report without changing the underlying facts.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

### Discourse Preprocessing

exact bounded slices, FastCoref reference candidates, and leased isanlp RST operand links

**Responsibility.** Identify candidate referents and discourse spans before reasoning classification while preserving exact source coordinates. Example: link 'it' to the named pump candidate and expose the two clauses joined by a causal discourse relation.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

**Principal public tools.** [IsaNLP RST](https://github.com/tchewik/isanlp_rst), [FastCoref](https://github.com/shon-otmazgin/fastcoref)

### Whole-Artifact Forward Reconstruction

prerequisites, referents, causal glue, progression, introduction, and conclusion

**Responsibility.** Rebuild the selected material in reader order, restoring prerequisites, referents, causal links, progression, and an honest ending. Example: introduce the goal before the procedure and close on an unresolved question when no conclusion exists.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

### Graph Why and Dependency Projection

deterministic view of classified graph edges that cannot introduce new reasoning claims

**Responsibility.** Translate accepted relation edges into inspectable dependency and why views without adding interpretation. Example: show that conclusion B depends on premise A because that exact classified edge exists.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

**Principal public tools.** [NetworkX](https://github.com/networkx/networkx)

### Grounded Interactive Answer

**Responsibility.** Return a conversational answer with the relevant reasoning, provenance, uncertainty, and expansion paths. The answer path may traverse complete conversations and evidence lifecycles without pretending to be a document-generation run.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

### Human Protocol Bridge

receiver-oriented encoding of the fixed supported payload

**Responsibility.** Convert a fixed, supported payload into a form the intended person can follow, using the product contract and measured delivery pattern; it cannot change the evidence. Example: turn the same grounded reasoning chain into a concise email or a staged guide by changing delivery structure, not conclusions.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

### Interactive Context Assembly

**Responsibility.** Build a bounded evidence and reasoning graph for the current question, preserving chronology, corrections, failures, source identity, and authorization. It supplies context to the answer without flattening the corpus into search snippets.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

### Lossless Accession

**Responsibility.** Admit original bytes and native events before interpretation, recording only observed arrival facts. Descriptions, timestamps inferred from content, identities, and relationships remain separate versioned observations.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

### Primary Evidence

**Responsibility.** Hold the authoritative deposits that later representations and products must be able to trace back to. Their existence has standing even when the system cannot yet explain their meaning or relationship.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

### Complete Provisional Tree

full pre-prune evidence, dependency, alternative, and failure structure

**Responsibility.** Hold the complete request-scoped candidate tree, including alternatives, failures, unknowns, and superseded views, so collapse can see what it would lose. Example: retain both a failed treatment and the later correction before selecting material for a guide.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

### Reasoning Graph

chronology, typed relations, claim lifecycles, failures, and uncertainty

**Responsibility.** Maintain the request-scoped map of propositions, chronology, attempts, outcomes, conflicts, dependencies, and uncertainty. Example: connect a failed treatment to the correction that superseded it without deleting either state.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

### Request + Artifact Contract

purpose, receiver, container, channel, budget, and veracity

**Responsibility.** Freeze the purpose, receiver, product, channel, budget, and truth standard so every downstream cog solves the same job. Example: distinguish a 500-word general-reader explanation from a technical incident report before evidence selection begins.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

### Reverse Expansion

gather backward without pruning; measure marginal contribution

**Responsibility.** Walk from the request or later evidence toward earlier related records and gather the complete candidate journey before anything is discarded. Example: follow a current algae question back through prior pH, pool-size, maintenance, and use-context records.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

### Typed Rhetorical Moves

semantic jobs and dependencies, never heading substrings

**Responsibility.** Assign each selected unit a communicative job and dependency based on the product contract, not a matching heading word. Example: mark evidence as supporting a claim and a failure as setting up recovery rather than calling both 'background.'

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

### Semantic Reconstruction

entities, propositions, episodes, attempts, results, and questions

**Responsibility.** Convert source observations into attributed semantic objects without deciding their final importance or presentation. Example: represent a proposed fix, the attempt, its failure, and the remaining question as separate linked records.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

### Versioned Representations

**Responsibility.** transcripts, structure, text, OCR, layout, and derived views

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

### Why It Mattered

attributed motivation, concern, consequence, and current relevance

**Responsibility.** Carry direct and explicitly attributed evidence about why attention was invested, leaving unsupported reasons unknown. Example: preserve that a maintenance task mattered because it protected people using shared equipment when the record supports it, rather than guessing that motive from a technical question alone.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

### Reasoning + Artifact Engine

receipt-gated reconstruction, collapse, Human Protocol, and atomic Markdown rendering

**Responsibility.** Coordinate the bounded reconstruction and rendering path and expose each stage's receipt; it does not replace specialist judgment. Example: carry a compose request through selection, planning, realization, validation, and atomic write.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

### Assembly + Capability Manager

walks required fields backward, prices prerequisites, selects truthful specialists, orders dependency waves, and skips zero-value work

**Responsibility.** Choose which specialists are needed, what order they run in, and which work adds no value; it does not perform their jobs. Example: schedule relation realization before sentence realization and skip an unavailable stylistic pass that contributes nothing required.

**Must preserve.** must_preserve_fields; field_lineage; explicit_unavailability

**Resource shape.** CPU; low memory; no GPU or lease

**Boundary.** cost and value observations expose decisions but never define human importance

### Atomic Carrier Budget Reconciler

measures indivisible source, glue, and relation carriers before realization and redistributes the fixed whole-product budget by genuine section slack

**Responsibility.** Check whether indivisible facts and relation carriers can fit each section, then move only available slack while preserving the total document budget. Example: enlarge a 90-word procedure section that contains a required 120-word atomic instruction by borrowing unused words from another section.

**Must preserve.** whole_artifact_budget; required_rhetorical_jobs; source_authority; graph_shape

**Resource shape.** CPU; near-zero runtime; prevents wasted Stage 8 GPU/model/verifier work

**Boundary.** cannot compress an indivisible proposition; fails if all required carriers exceed the declared product budget

### Source-Bound Rebinding Manager

moves only a complete isolated branch when its assigned product job is incompatible and one destination is provably compatible

**Responsibility.** Move a complete, isolated evidence branch to the one section whose job can legitimately use it, while refusing ambiguous or relation-bearing moves. Example: reassign a self-contained recovery note from setup to troubleshooting without duplicating it in both sections.

**Must preserve.** branch_identity; source_spans; relation_ids; marginal_gain_ledger

**Resource shape.** CPU; low latency; no GPU or lease

**Boundary.** refuses relation-bearing, ambiguous, partial, or over-capacity moves

### Document-Wide Relation Realizer

turns accepted same-section and cross-section reasoning edges into compact, independently replayable connective language without repeating both operands

**Responsibility.** Turn accepted graph relations into short connective language while keeping direction, operands, and source spans independently replayable. Example: realize A-causes-B as a bounded causal bridge instead of printing A and B as unrelated adjacent facts.

**Must preserve.** relation_direction; operand_identity; exact_carrier_spans; source_spans; section_lineage

**Resource shape.** CPU; near-zero runtime; no GPU or lease

**Boundary.** realizes only explicit accepted relation kinds; compact bridges preserve typed edge identity but remain mechanically worded; same-carrier, ambiguous, implicit, and unknown edges remain visible in the graph but unasserted as prose

### Knowledge Engine

**Responsibility.** Coordinate accession, derived representations, search, provenance, and durable jobs without merging those responsibilities into one truth state. It exposes supported interfaces to consumers while primary evidence remains independently addressable.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

### Typed Clause / Sentence Microplanner

assigns source-bound carriers to typed rhetorical jobs and compiles clause, sentence, and paragraph plans

**Responsibility.** Break approved meaning and relations into clause, sentence, and paragraph jobs while preserving their source bindings; it does not invent wording or claims. Example: plan a cause clause followed by its consequence and transition for the surface realizer.

**Must preserve.** semantic_unit_ids; relation_ids; source_forms

**Resource shape.** CPU; low latency; no GPU or lease

**Boundary.** does not invent a missing proposition or repair an unclassified relationship

**Principal public tools.** [spaCy](https://github.com/explosion/spaCy), [BlingFire](https://github.com/microsoft/BlingFire)

### Product Contract Manager

converts genre, receiver, purpose, channel, veracity, attention, and budget into required product fields and rhetorical work

**Responsibility.** Turn the request into a concrete checklist for the finished product without choosing evidence or writing it. Example: for a user manual, require prerequisites, ordered actions, recovery guidance, and a close before any editor starts.

**Must preserve.** declared_purpose; receiver; veracity; channel

**Resource shape.** CPU; near-zero runtime; no GPU or lease

**Boundary.** does not infer source meaning or choose facts

### Contract Surface Realizer

applies bounded grammar, morphology, typography, perspective, and typed transformations to delivery units

**Responsibility.** Apply grammar, morphology, typography, and permitted perspective to an already approved plan; it cannot decide new meaning. Example: turn a typed imperative plan into a grammatical instruction without adding a safety claim that was never supplied.

**Must preserve.** claim_authority; source_and_relation_bindings; rhetorical_job

**Resource shape.** CPU; optional candidate editor may use an existing GPU lease but has no authority

**Boundary.** closed grammar is faithful but can remain stylistically stiff

**Principal public tools.** [spaCy](https://github.com/explosion/spaCy)

## Management, verification, and operations

### Amf Ari

**Responsibility.** Run the pinned argument-relation classifier over supplied proposition pairs and return scored support, conflict, rephrase, or no-relation attempts. It does not create propositions, infer motives, or certify its own labels.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

**Principal public tools.** [OpenVINO](https://github.com/openvinotoolkit/openvino), [AMF ARI RoBERTa OpenVINO model](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8)

### Chat Indexer

**Responsibility.** Keeps conversations in the long record instead of leaving them in the chat window.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

### File Indexer

**Responsibility.** Discover eligible files and submit bounded, provenance-preserving indexing work. It must not treat filesystem dates, filenames, or extracted text as authoritative creation time, identity, or motive.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

### Hardware Telemetry

**Responsibility.** Record bounded machine-condition history so failures can be compared with power, temperature, memory, and accelerator state. The public description omits private sampling cadence and machine layout.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

**Principal public tools.** [psutil](https://github.com/giampaolo/psutil)

### Image

**Responsibility.** Produce images locally so a visual concept does not have to cross an external inference boundary. Image generation remains separate from evidence authority and publication permission.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

**Principal public tools.** [stable-diffusion.cpp](https://github.com/leejet/stable-diffusion.cpp), [Z-Image-Turbo](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo), [Z-Image-Turbo-Windows packaging reference](https://github.com/airesearch-official/Z-Image-Turbo-Windows)

### Ollama

**Responsibility.** The heavy mind. Slower and larger, kept for questions that genuinely need more thinking than speed.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

**Principal public tools.** [Ollama](https://github.com/ollama/ollama), [Qwen3](https://github.com/QwenLM/Qwen3)

### Ollama Embed

**Responsibility.** Makes writing searchable by meaning rather than by exact words.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

**Principal public tools.** [Ollama](https://github.com/ollama/ollama), [Nomic Embed Text](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5)

### Power Lease

**Responsibility.** Lets the machine idle quietly and wake fully for real work.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

### Conversation Retitler

**Responsibility.** Gives conversations names that mean something, so the list is findable rather than a wall of first sentences.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

### Semantic Observer

**Responsibility.** Checks whether an answer is supported by the material it claims to come from.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

**Principal public tools.** [Transformers](https://github.com/huggingface/transformers), [MiniCheck](https://github.com/Liyan06/MiniCheck), [FactCG](https://github.com/derenlei/FactCG)

### Slop Analysis

**Responsibility.** Keeps a record of how each mind fails and whether that is getting better or worse.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

**Principal public tools.** [spaCy](https://github.com/explosion/spaCy), [BlingFire](https://github.com/microsoft/BlingFire), [NLTK](https://github.com/nltk/nltk)

### Speaches

**Responsibility.** Turns speech into text, so talking is a way of writing things down.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

**Principal public tools.** [Speaches](https://github.com/speaches-ai/speaches), [faster-whisper](https://github.com/SYSTRAN/faster-whisper), [faster-distil-whisper-large-v3](https://huggingface.co/Systran/faster-distil-whisper-large-v3)

### Task Service

**Responsibility.** Read authorized task records as evidence about planned work without converting them into reminders, inferred motives, or corpus truth.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

### vLLM

**Responsibility.** The everyday mind. Fast, always loaded, answers almost everything.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

**Principal public tools.** [vLLM](https://github.com/vllm-project/vllm), [Qwen3](https://github.com/QwenLM/Qwen3)

### Durable Stage Jobs

bounded batches, checkpoints, cancellation, resume, and partial failure

**Responsibility.** Run long artifact stages as resumable bounded jobs with truthful terminal states instead of tying them to one browser request. Example: resume after a verified promotion checkpoint rather than repeating an expensive reasoning pass after interruption.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

### Execution + Manifest Manager

runs the assigned adapter and records physical method, endpoint, model revision, hashes, call edges, timing, retries, and disposition

**Responsibility.** Run each assigned specialist and record what physically executed, with its inputs, identity, timing, retries, and outcome. Example: show that the pinned AMF classifier handled Stage 2 instead of trusting a manifest label that merely says it did.

**Must preserve.** input_hashes; adapter_identity; failure_state

**Resource shape.** CPU coordinator; delegates GPU work only through declared lease owners

**Boundary.** records execution; cannot certify its own success

### GPU Lease Arbitration

**Responsibility.** Coordinate advisory handoffs between platform-managed accelerator workloads without exposing physical device identity or preempting work already in flight.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

### Power Residency Coordinator

**Responsibility.** Maintain one ACTIVE, WARM, IDLE, and NEVER state model across distributed platform power and residency mechanisms.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

### Expected / Observed Payload Ledger

joins each cog responsibility to its observed fields, readiness, omissions, value, cost, timing, retries, and repair request

**Responsibility.** Compare what every cog was expected to contribute with what it actually handed off, including cost and missing inputs. Example: expose that relation analysis ran for 40 seconds but supplied no usable connective edge to the editor.

**Must preserve.** handoff_identity; digests; missing_fields; cost_basis

**Resource shape.** CPU; near-zero relative to reasoning and verification

**Boundary.** portable section timing does not replace physical stage/model timing in the execution manifest

### Product-Aware Quality Manager

checks rhetorical completion, connective reasoning, readability, typography, duplication, attention, budget, weave, slop, and executable actions for the requested product

**Responsibility.** Evaluate whether this specific product works for its declared reader and purpose across separate quality axes, then identify the responsible repair stage. Example: a manual can fail missing recovery guidance even when every sentence is grammatical and grounded.

**Must preserve.** individual_axis_results; rejected_candidate_evidence

**Resource shape.** CPU plus bounded verifier/deslop HTTP; historically the largest Stage 8 share

**Boundary.** genre axes must be measured and versioned; one opaque quality score is forbidden

### Receipt + Promotion Manager

independently recomputes invariants and permits promotion and atomic artifact write only from a PASS receipt

**Responsibility.** Independently verify the bundle and write the artifact only after every required invariant passes. Example: refuse promotion when the renderer reports success but its receipt cannot reproduce a source binding.

**Must preserve.** failure_results; unknowns; release_identity; rollback_boundary

**Resource shape.** CPU and I/O; no GPU or lease

**Boundary.** manifest authenticity ultimately depends on reviewed immutable release/config binding

### Provenance + Loss Control

source identity, epistemic state, inference, invention, and rejected branches

**Responsibility.** Keep every statement tied to who or what supplied it, when it applied, and whether it was observed, inferred, superseded, rejected, or unknown. Example: preserve a later reinterpretation without overwriting the earlier belief that actually guided an action.

**Must preserve.** Exact graph identity, relationship provenance, and declared component boundary.

**Resource shape.** The live deployment records actual CPU, memory, storage, accelerator, and lease use; this public catalog does not expose machine placement.

**Boundary.** May perform only its declared graph responsibility and cannot repair missing or unsupported upstream evidence.

## Additional declared components

### Secure Web Gateway

Provides authenticated remote access from approved clients without directly exposing private platform services to the public internet.

### Platform Supervisor

Starts services in dependency order, observes their health, and performs bounded restart actions. Its failure removes coordinated supervision without redefining the state of services that remain running.

## Completeness boundary

The catalog covers active logical components in the maintained architecture graph,
not every transitive package installed by every runtime. A future software release
requires an exact software bill of materials and license bundle generated from the
specific bytes being distributed.
