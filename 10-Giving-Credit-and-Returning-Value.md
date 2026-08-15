# Giving Credit and Returning Value

![Attributed knowledge paths returning useful public maps without erasing their sources](assets/publish-reciprocity-open-paths.png)

The system was assembled independently from largely second-hand hardware,
personal resources, and substantial effort outside employment. Its intellectual
foundation came from people and institutions willing to publish work that others
could inspect, test, adapt within its terms, criticize, and build upon. Attribution
therefore records both technical lineage and a reciprocal obligation: public work
made the work possible, and the public edition returns its bounded findings
without claiming ownership of the contexts that produced them.

## Why this ledger exists

The work could not exist without people who chose to publish research,
write and maintain software, preserve cultural works, translate texts, curate
corpora, operate archives, and make their work available for reuse or study. Their
decision to share is an exercise of sovereignty. Public availability does not make
their contribution anonymous or ownerless.

The ledger records the principal contributions used in the public architecture. It
states what each source supplied, how it was used, and the relationship between the
source and this project. The categories are important:

- **active dependency** means the software or model executes in a current path;
- **adapted method** means an implementation uses a published mechanism without
  claiming the original code as project-authored;
- **calibration source** means material was measured, not reproduced in the public
  release;
- **design influence** means the work changed an architectural decision;
- **evaluated or rejected** preserves credit and the result of an experiment without
  implying adoption.

No entry implies that its authors, maintainers, communities, publishers, archives,
or institutions endorse this project. This documentation ZIP redistributes none of
their code, model weights, dataset text, or article text.

## Literary, linguistic, and communication foundations

| Contribution | Public source or identifying work | What it contributes here | Relationship |
|---|---|---|---|
| Carlota S. Smith | *Modes of Discourse: The Local Structure of Texts* | Grammatical distinctions among discourse modes; supports typed delivery analysis. | Design influence |
| M. A. K. Halliday and Ruqaiya Hasan | *Cohesion in English* | Separates surface cohesion from actual coherence. | Design influence and measurement basis |
| M. A. K. Halliday | Register as field, tenor, and mode | Treats audience and communicative situation as measured dimensions rather than prompt decoration. | Design influence |
| Douglas Biber | *Variation across Speech and Writing* | Multidimensional register analysis using co-occurring observable features. | Weave measurement lineage |
| William Mann and Sandra Thompson | Rhetorical Structure Theory | Discourse relations, nuclearity, and the distinction between central and supporting material. | Active specialist lineage |
| John Swales | *Genre Analysis* | Rhetorical moves and steps used to describe product structure. | Product-contract lineage |
| Gérard Genette and the Russian Formalist tradition | *Narrative Discourse*; fabula and sjuzhet | Separates event material from the order and viewpoint of its telling. | Narrative and reconstruction influence |
| H. P. Grice | “Logic and Conversation” | Cooperative maxims and the difference between deliberate flouting and accidental violation. | Human Protocol and detector design |
| Douglas Walton | Argumentation schemes and critical questions | Provides inspectable challenge patterns rather than one opaque argument score. | Argument-analysis influence |
| Alexandra Aikhenvald | *Evidentiality* | Treats source and evidence marking as a linguistic responsibility. | Epistemic-role influence |
| Claude Shannon | “A Mathematical Theory of Communication” | Supplies the formal communication vocabulary for information, channel limits, redundancy, and loss. | Communication architecture influence |
| Herbert Clark and Susan Haviland | Given-new contract | Supports measurement of what a receiver is assumed to know and what must be introduced. | Weave measurement lineage |
| Morton Ann Gernsbacher | Structure-building framework | Supports receiver-oriented establishment, mapping, and coherence analysis. | Human Protocol influence |
| Benjamin Bloom; Lorin Anderson and David Krathwohl | Educational objective taxonomies | Supplies an explicitly bounded vocabulary for expected receiver depth. | Audience-contract influence |

These works supplied methods and questions, not universal answers about a person.
The architectural contribution is to connect their bounded mechanisms to a
provenance-preserving assembly line and to keep every inference reversible and
inspectable.

## Selection, editing, and realization

| Contribution | Public source | What it contributes here | Relationship |
|---|---|---|---|
| Jaime Carbonell and Jade Goldstein | “The Use of MMR, Diversity-Based Reranking for Reordering Documents and Producing Summaries” | Balances relevance and novelty during bounded selection. | Adapted method |
| Hui Lin and Jeff Bilmes | Submodular summarization under budget | Diminishing-return selection under an explicit budget. | Adapted method |
| Eric Malmi, Sebastian Krause, Sascha Rothe, Daniil Mirylenka, and Aliaksei Severyn | LaserTagger | Demonstrates constrained editing with a closed insertion vocabulary. | Evaluated design influence |
| Kostiantyn Omelianchuk, Vitaliy Atrasevych, Artem Chernodub, and Oleksandr Skurzhanskyi | GECToR | Demonstrates tagged transformations and iterative correction. | Evaluated design influence |
| Jonathan Mallinson, Jakub Adamek, Eric Malmi, and Aliaksei Severyn | EdiT5 | Demonstrates pointer-based reordering that limits invention. | Evaluated design influence |
| Eric Malmi and collaborators; the broader surface-realization community | Grammar-based, graph-to-text, and constrained realization work | Reinforces separation of content determination, planning, realization, and verification. | Architecture influence; no blanket runtime adoption |

## Reasoning, discourse, and verification specialists

| Contribution | Public source | What it contributes here | Relationship |
|---|---|---|---|
| Elena Chistova and IsaNLP contributors | [IsaNLP RST Parser v3 model card](https://huggingface.co/tchewik/isanlp_rst_v3) and its cited ACL work; model card records CC BY-NC 4.0 | Produces bounded discourse structures and relation candidates. It does not determine personal meaning. | Active specialist; model is used within its non-commercial license boundary and not redistributed here |
| Shon Otmazgin, Arie Cattan, Yoav Goldberg, and FastCoref contributors | [F-COREF paper and official implementation](https://github.com/shon-otmazgin/fastcoref), MIT | Produces candidate coreference chains for later source-bound validation. | Active specialist |
| Chris Reed, the ARG-tech group, AIF/xAIF contributors, and AMF/ARI contributors | [oAMF module registry](https://github.com/arg-tech/oAMF), [AIF dataset and model registry](https://github.com/arg-tech/aif-arg-datasets), and linked specifications | Classifies bounded proposition relationships and supplies interoperable argument-graph vocabulary. | AMF/ARI is an active specialist lineage; oAMF was evaluated as orchestration prior art rather than adopted wholesale |
| Liyan Tang, Philippe Laban, and Greg Durrett | [MiniCheck](https://aclanthology.org/2024.emnlp-main.499/); [official code](https://github.com/Liyan06/MiniCheck) | Efficient factuality observations over claims and grounding documents. | Evaluated specialist; not release authority |
| Deren Lei, Yaxi Li, Siyao Li, Mengya Hu, Rui Xu, Ken Archer, Mingyu Wang, Emily Ching, and Alex Deng | [FactCG](https://aclanthology.org/2025.naacl-long.258/); [official code](https://github.com/derenlei/FactCG) | Graph-informed multi-hop factuality observations. | Evaluated specialist; not release authority |
| Philippe Laban, Tobias Schnabel, Paul N. Bennett, and Marti A. Hearst | [SummaC](https://aclanthology.org/2022.tacl-1.10/) | Exposes sentence/document granularity problems in consistency checking. | Design influence |
| Lorena Scirè, Simone Conia, and Roberto Navigli | [FENICE](https://arxiv.org/abs/2403.02270) | Claim extraction and evidence alignment for summarization evaluation. | Design influence |
| Xiangkun Hu and collaborators | [RefChecker](https://github.com/amazon-science/RefChecker) | Fine-grained support, refutation, and unknown records. | Evaluated design influence |
| Trieu H. Trinh and collaborators | [AlphaGeometry](https://github.com/google-deepmind/alphageometry) | Monotonic deduction closure and explicit proof-dependency traces. Geometry rules are not used. | Design influence |

MiniCheck and FactCG were evaluated with pinned public revisions and their published
licenses. Their scores were not separable on important project-shaped mutations, so
they were removed from release authority. Preserving that negative result is part of
reciprocity: the tools are credited for what they can observe without misrepresenting
what their authors claimed they could prove.

## Software contributors

The following public software projects provide bounded machinery. Their respective
copyright notices and licenses govern any redistribution of their code; this public
documentation does not redistribute it.

| Software | Contributors or steward | Recorded license | Bounded role |
|---|---|---|---|
| spaCy and its language models | Explosion AI, Matthew Honnibal, Ines Montani, and contributors | MIT | Part-of-speech, morphology, dependency parsing, and structural measurements |
| BlingFire | Microsoft and contributors | MIT | Sentence segmentation |
| LemmInflect | Brad Jascob and contributors | MIT | English inflection |
| submodlib | Vishal Kaushal, Rishabh Iyer, Ganesh Ramakrishnan, and DECILE contributors | MIT | Submodular selection |
| NLTK | Steven Bird, Edward Loper, Ewan Klein, and contributors | Apache-2.0 | Corpus access and linguistic utilities |
| NumPy | NumPy contributors | BSD-3-Clause | Numerical arrays and similarity matrices |
| SciPy | SciPy contributors | BSD-3-Clause | Clustering and statistical operations |
| NetworkX | NetworkX contributors | BSD-3-Clause | Directed graph operations and measurements |
| kneed | Kevin Arvai and contributors | BSD-3-Clause | Knee-point detection for measured calibration curves |
| PyYAML | Kirill Simonov and contributors | MIT | Structured configuration interchange |
| httpx | Tom Christie and contributors | BSD-3-Clause | Service-boundary HTTP transport |
| psycopg | Daniele Varrazzo and contributors | LGPL-3.0 | PostgreSQL access |
| Pydantic | Pydantic contributors | MIT | Typed validation and serialization |
| OpenVINO | Intel and contributors | Apache-2.0 | Bounded model inference where configured |
| textdescriptives | Lasse Hansen, Kenneth Enevoldsen, and contributors | Apache-2.0 | Readability, coherence, and information-theoretic measurements |
| LFTK | Bruce W. Lee and Jason Hyung-Jong Lee | Public project license; verify with any redistributed release | Linguistic feature extraction evaluated for calibration |

The table is a principal inventory, not a substitute for machine-generated
dependency notices in a future code distribution. Exact versions, hashes, transitive
licenses, and complete license texts must accompany any release that redistributes
software or model files.

## Cultural works, corpora, archives, and communities

The analysis measures delivery patterns and structural properties. Unless a separate
license permits reproduction, the public output contains aggregate measurements and
source identities, not source text.

| Source | People or institution being credited | Permission and use boundary | Contribution |
|---|---|---|---|
| Project Gutenberg | Michael S. Hart, Distributed Proofreaders, participating authors, editors, translators, and volunteers | Verified public-domain texts are measured; Project Gutenberg edition terms and trademark remain respected. | Long-period literary and product-form calibration |
| LibriVox | Volunteer readers, maintainers, and the authors of public-domain source texts | LibriVox records public-domain texts and dedicates its recordings to the public domain under its stated policy. | Candidate spoken-delivery calibration; not silently pooled with print |
| Brown Corpus | W. Nelson Francis, Henry Kučera, Brown University, and curators | Used through its distributed corpus terms for aggregate measurement. | Genre-labelled register contrasts |
| Reuters-21578 | Reuters, David Lewis, and curators | Aggregate measurements only under the dataset’s distribution terms. | Dense wire-copy comparison |
| NPS Chat Corpus | Eric Forsyth, Jane Lin, Craig Martell, and the Naval Postgraduate School | Aggregate measurement; personal text is not reproduced publicly. | Human-to-human chat comparison |
| Universal Declaration of Human Rights translations | United Nations OHCHR and translators | Parallel translations measured as a control; attribution retained. | Separates cross-language protocol patterns from English habits |
| arXiv | Cornell University, arXiv, submitting authors, and maintainers | Metadata is treated according to its published terms; abstracts remain authors’ work and are not reproduced. | Longitudinal scientific-register measurement |
| PubMed/MEDLINE | U.S. National Library of Medicine, participating journals, and authors | Aggregate measurement only; abstracts are not redistributed and no NLM endorsement is implied. | Scientific prose comparison |
| Delpher | Koninklijke Bibliotheek, digitization contributors, publishers, and authors | Aggregate measurement only because item-level rights vary. | Long-period newspaper comparison |
| Wikipedia | Wikimedia Foundation and contributing editors | CC BY-SA source; no article text is reproduced in this publication. | Encyclopedia register comparison |
| Stack Overflow | Stack Exchange and the answering community | CC BY-SA source; no post text is reproduced here. | Forum-answer comparison |
| Hacker News and Mastodon samples | Platform operators and individual community authors | No blanket content license is assumed; only non-identifying aggregate observations are publishable. | Exploratory modern-format comparison |

The public project’s reciprocal return is not possession of these works. It is an
auditable account of the methods they enabled, the boundaries found, the failed
hypotheses they helped falsify, and reusable measurements that preserve a path back
to their contributors.

Reciprocity also governs external model use. Supplying an authorized working payload
for a bounded contribution does not make the external service the owner of the
maintained corpus, just as using published research does not erase its authorship.
The contribution should be credited and measured, while the source, authority, and
continuing value of the underlying record remain distinct. Reciprocity prevents useful
derivation from becoming an excuse to destroy human context and concentrate its value
inside the receiving institution.

## Rights and completeness boundary

Public-domain status, open access, open source, and permission for computational
analysis are different rights states. The ledger records the applicable basis rather
than treating “available online” as permission. Sources requiring circumvention,
uncertain authorization, or an unreviewed fair-use theory are excluded from new
publication datasets.

The ledger covers the principal foundations visible in the public documentation. The
private project maintains a larger evolving inventory, including evaluated and
rejected candidates. A future scholarly or software release must produce an exact
artifact-specific software bill of materials, model and dataset ledger, bibliography,
license bundle, and transformation record. Omission from this summary does not erase
credit or grant permission.
