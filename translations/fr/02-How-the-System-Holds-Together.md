> Français: Traduction assistée par machine de la source anglaise faisant autorité. Native-language corrections are welcome. [Anglais](../../README.md) | [Toutes les langues](../README.md)

# Comment le système tient la route

![Le archive préservé prenant en charge les spécialistes remplaçables et un plan de contrôle inspectable](../../assets/core-architecture-layers.png)

## Séparation des responsabilités

La plateforme sépare quatre préoccupations qui coopèrent sans se devenir :

1. **Préservation** conserve les preuves originales et la provenance observée.
2. **Comprendre** ajoute des objets sémantiques versionnés, des relations, des états temporels,
  et des interprétations appuyées.
3. **Récupération et interaction** rassemble des preuves spécifiques à la demande pour les questions,
  exploration et conversation.
4. La **reconstruction d'artefacts** convertit un monde de preuves limité en un monde déclaré
  produit pour un destinataire déclaré.

Les instructions du produit ne remontent pas dans la vérité du corpus. Un chapitre, un public, un genre, un mouvement rhétorique ou un budget de mots appartiennent à un seul retrait. Il ne s'agit pas d'une étiquette intrinsèque sur un artefact source.

## Topologie en couches

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

## L'adhésion ne prétend pas savoir

L'enregistrement d'arrivée peut indiquer que des octets particuliers ont atteint le système via un canal particulier. Il ne décide pas silencieusement qui a créé l'artefact, qui y apparaît, quand son sujet est apparu, si un nom de fichier est exact, pourquoi il est important ou à qui appartient son contenu. Ce sont des observations distinctes avec des preuves et une autorité distinctes.

L'architecture distingue l'artefact original des représentations qui en dérivent. Le texte extrait, les descriptions, les intégrations, les classifications, les résumés et les relations peuvent être régénérés ou remplacés. Ils ne remplacent pas la source.

## Parcours interactifs et documentaires

Les réponses interactives et la génération d'artefacts partagent des preuves, une provenance, des relations typées, des incertitudes et des mécanismes de validation. Ils restent distincts du même workflow.

Une demande interactive peut nécessiter une conversation complète, un cycle de vie de tâche, une traversée de relation étroite ou une clarification. Il n’est pas nécessaire de construire un conteneur de livres et de réduire globalement un arbre historique.

La génération d’artefacts nécessite un produit déclaré, un récepteur, un budget et un plan global pour l’artefact. Il doit voir la structure provisoire pertinente avant l'élagage et doit rendre compte de ce qui a été laissé de côté.

## Architecture dynamique plutôt qu’une chaîne fixe

La chaîne de montage est compilée pour le produit. Différentes sorties peuvent utiliser différents spécialistes, commander différemment les mêmes spécialistes ou nécessiter plusieurs instances d'une même capacité. Le manager utilise des contrats de capacité et des preuves préalables plutôt que les seuls noms de scène codés en dur.

Les invariants universels restent stables à tous les niveaux : identité de la source, propriété, état épistémique, incertitude, comptabilisation des pertes, transferts typés, observation des coûts, vérification indépendante et restauration.

Un modèle général externe peut occuper une station typée lorsque sa contribution mesurée justifie le transfert. Il reçoit uniquement la charge utile adaptée à la demande requise par cette station, et non le corpus maintenu ou l'autorité codée par le plan de contrôle plus large. Le remplacement ou la suppression de cette station laisse intacts le archive durable et la capacité de reconstruction future. La station délimitée peut contribuer sans recevoir les connaissances humaines qu’un système centralisé aurait autrement aplati en valeur institutionnelle.
