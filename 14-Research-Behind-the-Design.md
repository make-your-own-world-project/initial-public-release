# Research Behind the Design

![Distinct academic traditions contributing bounded methods without losing their lineages](assets/academic-framework-lineages.png)

## Reciprocity and status

The architecture borrows mechanisms because researchers, authors, maintainers, archives,
and communities chose to make their work inspectable or reusable. Each entry records
the mechanism taken, its bounded adaptation, and the limit that prevents credit from
turning into an unsupported claim of adoption or endorsement.

The first section contains established research lineages used in the architecture.
The second contains frameworks inspected or experimentally adapted but not necessarily
installed. This distinction is part of implementation truth.

The same distinction applies to general external models. A model may contribute
realization quality over an authorized payload without becoming the architecture or
memory system. The payload contains enough information for the bounded contribution,
not the omitted corpus-level state from which continuing project value is derived.

## Research lineages

### [Carlota S. Smith: Modes of Discourse (2003)](https://www.cambridge.org/core/books/modes-of-discourse/B9BC09A509E912E3E2433188D332E3F0)

**Mechanism contributed.** Five passage modes distinguished through grammatical features.

**Role here.** Supplies typed narrative, description, report, information, and argument observations.

**Boundary.** Mixed passages require distributions; mode is not genre or authorial intent.

### [Mann & Thompson: Rhetorical Structure Theory (1988)](https://aclanthology.org/J88-2003/)

**Mechanism contributed.** Span relations, nuclearity, and whole-text organization.

**Role here.** Supplies candidate edges and preservation pressure for evidence, contrast, concession, and purpose.

**Boundary.** Automatic RST parsing is fallible; candidates require exact spans and independent gates.

### [John Swales: Genre Analysis (1990)](https://books.google.com/books/about/Genre_Analysis.html?id=shX_EV1r3-0C)

**Mechanism contributed.** Genres as ordered communicative moves and optional steps.

**Role here.** Supplies product-specific move contracts instead of one universal outline.

**Boundary.** Move inventories are genre-specific and must be derived/calibrated, not guessed.

### [M. A. K. Halliday: register: field, tenor, mode](https://www.routledge.com/Language-as-Social-Semiotic-The-Social-Interpretation-of-Language-and/Halliday/p/book/9780713162592)

**Mechanism contributed.** Language choices vary with social action, participant relationship, and channel.

**Role here.** Conditions receiver, channel, and vocabulary/grammar targets in the product contract.

**Boundary.** Register constrains delivery; it does not establish factual support or source meaning.

### [Halliday & Hasan: Cohesion in English (1976)](https://www.routledge.com/Cohesion-in-English/Halliday-Hasan/p/book/9780582550414)

**Mechanism contributed.** Reference, substitution, ellipsis, conjunction, and lexical cohesion; cohesion differs from coherence.

**Role here.** Supplies cohesion measurements and the warning that fluent linkage can still go nowhere.

**Boundary.** Surface cohesion alone cannot certify conceptual progression.

### [Douglas Biber: Variation across Speech and Writing (1988)](https://www.cambridge.org/core/books/variation-across-speech-and-writing/A546CF5ED8F8E62F1432CB2F369CF356)

**Mechanism contributed.** Corpus-derived multidimensional register measurement.

**Role here.** Weave profiles are measured feature distributions rather than hard-coded style adjectives.

**Boundary.** Requires representative calibration corpora; English dimensions are not universal constants.

### [Gérard Genette: Narrative Discourse (1972/1980), after Russian Formalism](https://www.cornellpress.cornell.edu/book/9780801492594/narrative-discourse/)

**Mechanism contributed.** Story/discourse separation; order, duration, frequency, and focalization.

**Role here.** Supplies source-versus-render separation, temporal reordering, compression modes, and perspective checks.

**Boundary.** Narratology transfers imperfectly to argument and technical explanation.

### [H. P. Grice: Logic and Conversation (1975)](https://doi.org/10.1163/9789004368811_003)

**Mechanism contributed.** Purpose-relative quantity, quality, relation, manner; flouting, violation, opting out, and clash.

**Role here.** Organizes delivery faults and prevents intentional rhetoric from being treated as automatic slop.

**Boundary.** A diagnostic taxonomy, not a complete automatic detector.

### [Douglas Walton: Argumentation Schemes for Presumptive Reasoning](https://www.cambridge.org/core/books/argumentation-schemes/86B181C5382B8FE5D38EBEF057A4397A)

**Mechanism contributed.** Recurring argument schemes paired with critical questions.

**Role here.** Supplies inspectable challenges for argument records and unresolved support.

**Boundary.** Scheme classification is uncertain and cannot create missing premises.

### [Alexandra Aikhenvald: Evidentiality (2004)](https://global.oup.com/academic/product/evidentiality-9780199204334)

**Mechanism contributed.** Grammatical marking of witnessed, inferred, reported, and assumed knowledge.

**Role here.** Motivates explicit evidential status on claims and preservation of uncertainty.

**Boundary.** English does not obligatorily mark evidentiality, so metadata must be reconstructed.

### [Claude Shannon: A Mathematical Theory of Communication (1948)](https://people.math.harvard.edu/~ctm/home/text/others/shannon/entropy/entropy.pdf)

**Mechanism contributed.** Information, entropy, channel capacity, and redundancy.

**Role here.** Supplies bounded redundancy and attention-channel measurements.

**Boundary.** Symbol entropy is not semantic meaning; prose use is an engineering analogy.

### [Bloom taxonomy, revised by Anderson & Krathwohl](https://www.loc.gov/item/00063423/)

**Mechanism contributed.** Reader capability progression from remember through create.

**Role here.** Sets intended receiver action/depth separately from age or register.

**Boundary.** Educational objectives are not directly inferable from finished text.

### [Jaime Carbonell & Jade Goldstein: Maximal Marginal Relevance (1998)](https://aclanthology.org/X98-1025/)

**Mechanism contributed.** Selection balances relevance with novelty.

**Role here.** Supplies gain terms for packet/material selection without duplicate coverage.

**Boundary.** Similarity quality bounds the result; MMR does not preserve reasoning by itself.

### [Lin & Bilmes: Submodular document summarization (2011)](https://aclanthology.org/P11-1052/)

**Mechanism contributed.** Diminishing-return subset selection under a budget.

**Role here.** Supplies auditable budgeted coverage selection in the derivation/collapse walk.

**Boundary.** The objective must not collapse human importance into corpus volume.

### [Min et al.: FActScore (2023)](https://aclanthology.org/2023.emnlp-main.741/)

**Mechanism contributed.** Atomic factual claims checked against a knowledge source.

**Role here.** Influences per-claim support ledgers and bounded verification packets.

**Boundary.** Atomic factual precision does not validate literary function or complete reasoning.

### [Liu, Wang & Demberg: RSTformer (2023)](https://aclanthology.org/2023.acl-long.306/)

**Mechanism contributed.** RST relation distributions and discourse-aware long-document summarization.

**Role here.** Motivates retaining uncertainty and protecting contrast/concession candidates.

**Boundary.** Does not make automatically inferred RST relations authoritative.

### [Reiter & Dale: Building Natural Language Generation Systems (2000)](https://www.cambridge.org/core/books/building-natural-language-generation-systems/638187D3AE5DB0A0B8F5E4E94D98F3A7)

**Mechanism contributed.** Separates document planning, microplanning, and surface realization.

**Role here.** Defines assembly-line responsibility boundaries and typed handoffs.

**Boundary.** A reference architecture; concrete product contracts and gates remain project work.

### [Moryossef, Goldberg & Dagan: Step-by-Step NLG (2019)](https://aclanthology.org/N19-1236/)

**Mechanism contributed.** Separates planning from faithful realization.

**Role here.** Supports keeping content decisions upstream of the editor/realizer.

**Boundary.** Data-to-text findings do not establish faithfulness for arbitrary corpus prose.

### [Puduppully & Lapata: Data-to-text macro planning](https://aclanthology.org/D19-1318/)

**Mechanism contributed.** Explicit macro plans precede linguistic realization.

**Role here.** Supports section ordering and dependency-bound realization contracts.

**Boundary.** Plans still require grounded source selection and product-specific calibration.

### [Clark & Haviland: given/new information contract](https://doi.org/10.1017/CBO9780511620560.004)

**Mechanism contributed.** Comprehension links new material to information presumed available to the receiver.

**Role here.** Supplies checks for unexplained facts, missing antecedents, and source-bound cross-section rebinding.

**Boundary.** Receiver knowledge is uncertain; the system must expose assumptions rather than invent background.

### [Morton Ann Gernsbacher: Structure Building Framework](<https://doi.org/10.1016/0010-0285(90)90008-7>)

**Mechanism contributed.** Readers lay foundations, map coherent material, and shift structures when coherence breaks.

**Role here.** Supplies progression and excessive-reset observations for Human Protocol quality management.

**Boundary.** A cognitive model is not a license to infer an individual reader's internal state.

### [Martha Palmer, Daniel Gildea & Paul Kingsbury: Proposition Bank](https://aclanthology.org/J05-1004/)

**Mechanism contributed.** Predicate/argument roles provide a shallow representation of who did what to whom.

**Role here.** Informs imperative and proposition typing before verification and realization.

**Boundary.** Semantic roles do not establish truth, motivation, or discourse function.

### [McNamara, Graesser, McCarthy & Cai: Coh-Metrix](https://www.cambridge.org/core/books/automated-evaluation-of-text-and-discourse-with-cohmetrix/9E064589C5A2C999E894CAE7452E8182)

**Mechanism contributed.** Multi-level cohesion, narrativity, syntax, and readability measurements.

**Role here.** Provides a comparison vocabulary for measured text quality and fragmentation.

**Boundary.** Metrics are diagnostic signals, not an automatic editorial verdict.

### [Kristopher Kyle: Tool for the Automatic Analysis of Cohesion (TAACO)](https://www.linguisticanalysistools.org/taaco.html)

**Mechanism contributed.** Automated local/global cohesion indices over text.

**Role here.** Informs cohesion observations and evaluation baselines for product-quality management.

**Boundary.** Not a runtime authority and cannot distinguish meaningful recurrence from empty repetition.

### [Carnegie Mellon DocuScope](https://docuscope.github.io/)

**Mechanism contributed.** Lexical/rhetorical categories support corpus comparison and genre observations.

**Role here.** Informs interpretable delivery-feature categories used during literary calibration.

**Boundary.** Dictionary categories are language/domain bounded and are not direct measures of intent.

## Analyzed or adapted frameworks

### [Graphiti temporal knowledge-graph mechanisms](https://github.com/getzep/graphiti)

**Mechanism examined.** Episode/source attribution, temporal invalidation history, local candidate blocking, and bounded neighborhood retrieval.

**What carried forward.** Its inspectable mechanisms informed bounded candidate neighborhoods and superseding temporal observations.

**Status and boundary.** Graphiti is not installed and is not a chatbot-memory authority; project code must independently prove each adopted mechanism.

### [oAMF / xAIF argument interchange patterns](https://github.com/arg-tech/oAMF)

**Mechanism examined.** Typed argument nodes, relations, and interoperable AIF-family graph records.

**What carried forward.** Interface and relation-shape lessons informed typed AMF/ARI handoffs and inspectable graph edges.

**Status and boundary.** The GPL orchestrator was not adopted wholesale; AMF-ARI is separately credited where it actually executes.

### [Weighted RST (W-RST) research method](https://aclanthology.org/2021.acl-long.302/)

**Mechanism examined.** Overlays continuous auxiliary-task importance on an RST structure instead of treating nuclearity as only binary.

**What carried forward.** Evaluated as a possible auditable prominence contribution over IsaNLP trees.

**Status and boundary.** No maintained drop-in W-RST service exists here; it is not claimed as an active runtime capability.

### [StrucSum graph-structured summarization ideas](https://aclanthology.org/2026.findings-eacl.192/)

**Mechanism examined.** Uses structural relationships to condition summary planning and selection.

**What carried forward.** Graph selection ideas were evaluated against the local backward-walk/forward-collapse machinery.

**Status and boundary.** Its prompt-based implementation was rejected as production authority; no StrucSum runtime is installed.

### [SimpleNLG surface-realization architecture](https://github.com/simplenlg/simplenlg)

**Mechanism examined.** Deterministic lexicalization, morphology, agreement, and syntactic realization from structured specifications.

**What carried forward.** An isolated spike informed the local bounded contract grammar and morphology checks.

**Status and boundary.** SimpleNLG itself is not the production runtime; isolated testing exposed stiffness and incomplete project-specific realization.

### [Grammatical Framework (GF)](https://www.grammaticalframework.org/)

**Mechanism examined.** Separates abstract syntax from language-specific concrete grammars.

**What carried forward.** Its faithfulness-by-grammar principle informs typed product contracts and constrained realization.

**Status and boundary.** GF is not installed; project grammars and multilingual coverage remain separate engineering work.

### [OpenCCG](https://github.com/OpenCCG/openccg)

**Mechanism examined.** Grammar-driven surface realization from logical forms.

**What carried forward.** Evaluated as a model for separating content authority from linguistic realization.

**Status and boundary.** Not installed; cited as an architectural precedent, not an executing cog.

### [AMR-to-text and back-parsing consistency lineage](https://aclanthology.org/2020.acl-main.397/)

**Mechanism examined.** Graph-to-text realization plus semantic back-checking of generated text.

**What carried forward.** Tested as a realization candidate and as support for generate/reparse/verify gates.

**Status and boundary.** Not authoritative in production: isolated candidates could silently alter number or tense, and AMR is not the native representation.

### [Self-Determination Theory](https://selfdeterminationtheory.org/the-theory/)

**Mechanism examined.** Autonomy, competence, and relatedness as established motivational coordinates.

**What carried forward.** Provides conservative labels for explicit, source-bound driver candidates.

**Status and boundary.** Coordinates are not diagnoses, stable traits, accepted motives, or an inference of an unknown why.

### [Martela & Steger: three meanings of meaning in life (2016)](https://doi.org/10.1080/17439760.2015.1137623)

**Mechanism examined.** Separates coherence, purpose, and significance as distinct dimensions.

**What carried forward.** Contributed those dimensions as conservative candidate coordinates for explicit source language.

**Status and boundary.** A conceptual framework cannot establish personal meaning from text; candidates remain source-bound and uncertain.

### [Schwartz theory of basic human values](<https://doi.org/10.1016/S0065-2601(08)60281-6>)

**Mechanism examined.** A circular geometry of value compatibilities and tensions.

**What carried forward.** Supplies an inspectable geometry among explicitly nominated candidate coordinates.

**Status and boundary.** Schwartz geometry does not profile a person or accept a value or motive; local code records framework geometry only.

### [LaserTagger](https://github.com/google-research/lasertagger)

**Mechanism examined.** Edits text with a bounded insertion vocabulary and explicit edit tags.

**What carried forward.** Contributed the bounded-edit principle used by deslop/editorial cleanup.

**Status and boundary.** Not installed as production authority; a closed vocabulary can still make contextually wrong edits.

### [GECToR](https://github.com/grammarly/gector)

**Mechanism examined.** Iterative sequence tagging proposes bounded grammatical transformations.

**What carried forward.** Contributed the edit-tag and re-check pattern for morphology/typography cleanup.

**Status and boundary.** Not installed; grammaticality is not preservation, grounding, or product fitness.

### [EdiT5](https://aclanthology.org/2022.findings-acl.260/)

**Mechanism examined.** Separates edit operations and realization for controllable text editing.

**What carried forward.** Informed the separation of local edits from content-authoritative reconstruction.

**Status and boundary.** Not installed; neural editing may silently alter supported meaning.

### [textdescriptives](https://github.com/HLasse/TextDescriptives)

**Mechanism examined.** Computes transparent descriptive, readability, dependency, quality, and coherence features.

**What carried forward.** Used as an evaluated feature source for delivery diagnostics and regression comparisons.

**Status and boundary.** Feature availability and language coverage vary; scores do not determine product quality alone.

### [LFTK](https://github.com/brucewlee/lftk)

**Mechanism examined.** Provides a broad inventory of linguistic features over spaCy documents.

**What carried forward.** Evaluated as a feature inventory during linguistic/delivery calibration.

**Status and boundary.** Not a literary model or editorial authority; version/language constraints apply.

## Audit boundary

The maintained catalog records principal sources without claiming exhaustive scholarly credit.
The private corpus contains additional candidates and historical references. They must
be reviewed for identity, rights, actual influence, and adoption status before entering
a public bibliography. An unreviewed name match is not attribution evidence.
