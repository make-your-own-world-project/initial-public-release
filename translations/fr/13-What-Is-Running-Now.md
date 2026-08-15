> Français: Traduction assistée par machine de la source anglaise faisant autorité. Native-language corrections are welcome. [Anglais](../../README.md) | [Toutes les langues](../README.md)

# Qu'est-ce qui fonctionne actuellement

![L’appareil local organisé par responsabilité autour d’une épine dorsale partagée et maîtrisée](../../assets/public-machinery-catalog.png)

## Comment lire ce catalogue

Le catalogue est le pendant public de la vue Datacenter dans Mission Control. Il décrit ce que chaque rouage apporte et ce qui serait perdu s'il disparaissait, sans publier les adresses privées, la configuration de la machine, les informations d'identification, les chemins de fichiers ou la cadence de fonctionnement. Le live graph reste la source opérationnelle de vérité.

L’état des composants est important. Un outil peut être actif, conservé en tant que système source, évalué mais non adopté, ou être un prédécesseur retiré. La présence dans ce catalogue n'accorde pas d'autorité à un composant au-delà de son rôle déclaré.

Cette règle inclut la capacité aux frontières extérieures. Lorsqu'il est utilisé, il occupe une station délimitée et reçoit une charge utile spécialement conçue plutôt qu'un accès illimité au corpus maintenu. La charge utile prend en charge l’opération déclarée mais omet l’état durable nécessaire pour reconstruire le système plus large ou produire indépendamment de futurs retraits. La station reçoit du travail, et non la garde du archive humain dont une institution centralisée pourrait extraire une valeur durable.

## Accès et contournement du système

### Cerveau de robot (LibreChat)


**Responsabilité.** Fournir la fenêtre de conversation remplaçable avec un visage humain. Il transporte les requêtes et les réponses tandis que la mémoire durable, la récupération, le raisonnement et la vérification restent dans les services situés en dessous.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

**Principaux outils publics.**[LibreChat](https://github.com/danny-avila/LibreChat),[Noeud.js](https://github.com/nodejs/node)

### Séparateur de conversation


**Responsabilité.** Remarque lorsqu'une conversation s'est transformée en deux sujets et propose de classer celui terminé séparément.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

**Principaux outils publics.**[API rapide](https://github.com/fastapi/fastapi)

### Contrôle de mission


**Responsabilité.** La fenêtre sur la machine : ce qui est en cours d'exécution, ce qui nécessite une attention particulière et ce qu'elle fait en ce moment. À cette limite de publication, sa page d'état signale tous les systèmes surveillés opérationnels sur l'installation locale.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

** Limite. ** L'état opérationnel signale l'état du service ; les artefacts et les reçus acceptés établissent les limites distinctes de l'exécution et des preuves sémantiques.

**Principaux outils publics.**[API rapide](https://github.com/fastapi/fastapi),[Visualisation graphique](https://gitlab.com/graphviz/graphviz),[Psycopg](https://github.com/psycopg/psycopg)

### Routeur sémantique


**Responsabilité.** Acheminez les requêtes limitées vers le moteur local approprié et exigez une autorisation explicite avant d'utiliser l'inférence externe. Une capacité coûteuse n'est sélectionnée que lorsque la demande justifie son coût mesuré.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

**Principaux outils publics.**[API rapide](https://github.com/fastapi/fastapi). Envoy et vLLM Semantic Router restent crédités dans l'index source en tant que prédécesseurs inspectés ou retirés, et non en tant que dépendances d'exécution actuelles.

### Historiques complets des agents


**Responsabilité.** Conservez des flux d'événements d'agent complets et ordonnés comme preuve d'interaction, y compris les tours humains, les tours d'assistant, les outils, les erreurs et les corrections. Les histoires enregistrent ce qui s'est passé ; ils ne transforment pas les déclarations des agents en faits vérifiés.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

** Limite. ** Fournit uniquement ce que sa source et sa provenance établissent ; l’interprétation en aval reste distincte.

### Documents du projet


**Responsabilité.** Préservez les enregistrements privés de conception, de preuves et de projets qui expliquent pourquoi la plateforme existe et comment son architecture a changé. Les produits publics consomment des dérivés examinés plutôt que d'exposer l'emplacement du document privé.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

** Limite. ** Fournit uniquement ce que sa source et sa provenance établissent ; l’interprétation en aval reste distincte.

### Vikunja


**Responsabilité.** Préserver le système de tâches externes en tant que source indépendante antérieure à la plateforme. L'intégration peut lire les preuves de tâches autorisées sans absorber le système de tâches dans le corpus ni modifier son cycle de vie.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

** Limite. ** Fournit uniquement ce que sa source et sa provenance établissent ; l’interprétation en aval reste distincte.

**Principaux outils publics.**[Vikunja](https://github.com/go-vikunja/vikunja)

## Conservation et récupération

### Apport de connaissances


**Responsabilité.** La façon dont les choses entrent. Déposez un document, une exportation, une pile de notes, et le tout atterrit dans un endroit trouvable au lieu de nulle part.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

### MongoDB


**Responsabilité.** Tient lui-même les conversations, comme on l'a dit.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

** Limite. ** La disponibilité et l'intégrité sont nécessaires ; les données stockées ne s’interprètent ni ne se vérifient d’elles-mêmes.

**Principaux outils publics.**[MongoDB](https://github.com/mongodb/mongo)

### PostgreSQL


**Responsabilité.** Conserver des enregistrements de projet structurés durables, des états dérivés et des index de recherche destinés à survivre aux services d'application remplaçables. Les documents stockés conservent une autorité et une provenance distinctes plutôt que de devenir une mémoire indifférenciée.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

** Limite. ** La disponibilité et l'intégrité sont nécessaires ; les données stockées ne s’interprètent ni ne se vérifient d’elles-mêmes.

**Principaux outils publics.**[PostgreSQL](https://github.com/postgres/postgres),[pgvecteur](https://github.com/pgvector/pgvector)

## Raisonnement et reconstruction

### Classificateur de relations d'arguments

classification CPU AMF_ARI OpenVINO épinglée d'inférence, de conflit, de reformulation ou d'absence de relation

**Responsabilité.** Classer la relation entre deux propositions fournies ; cela ne crée ni proposition ni déduction de motif personnel. Exemple : distinguer une instruction qui en soutient une autre de celle qui la contredit, ou ne renvoyer aucune relation prise en charge.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

**Principaux outils publics.**[Modèle AMF ARI RoBERTa OpenVINO](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8)

### Artefacts humains


**Responsabilité.** Définir les produits à contact humain que la chaîne d'assemblage peut construire. Chaque produit comporte son propre destinataire, son objectif, sa structure, sa politique de preuve et son contrat de livraison plutôt que de partager un aperçu générique.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

### Mise à la terre + validation de livraison

porte de réception indépendante pour les contrôles de fidélité, de provenance, de perte, d'invention, de tissage et de compréhension

**Responsabilité.** Vérifier de manière indépendante que l'artefact conserve la signification prise en charge et satisfait à son contrat de livraison déclaré avant sa sortie. Exemple : rejeter un paragraphe lisible qui invente une conclusion, et rejeter séparément un document fondé dont la structure est inutilisable pour son lecteur cible.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

### Résolution du public

état du destinataire, prérequis, registre et pertinence

**Responsabilité.** Décrivez ce que le destinataire prévu est censé savoir, avoir besoin et tolérer tout en gardant les hypothèses explicites. Exemple : demandez à un guide du propriétaire d'expliquer le pH avant d'utiliser des abréviations familières à un technicien de piscine.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

### Effondrement de l'arbre entier + paquets

partition contrainte par conteneur, sélection, gains et pertes

**Responsabilité.** Sélectionnez et équilibrez ce qui peut correspondre à l'artefact demandé tout en enregistrant ce qui a été omis et en préservant la forme significative de l'arbre. Exemple : gardez chaque branche principale représentée dans un article de 1 000 mots au lieu de laisser la plus grande branche source consommer la totalité du budget.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

**Principaux outils publics.**[sous-modlib](https://github.com/decile-team/submodlib),[à genoux](https://github.com/arvkevi/kneed)

### Modèle de travail compact

support portable adapté à la demande pour les unités, relations, trajectoires, blocs sources, plans, poignées et registres de transfert sélectionnés

**Responsabilité.** Regroupez les faits, les relations, la chronologie, l'incertitude, les échecs et les sources sélectionnés dans un contexte portable spécifique à l'emploi. Exemple : donnez à l'éditeur la chaîne de maintenance du pool et pourquoi ses étapes se connectent sans charger l'intégralité du corpus ni supprimer les liens.

**Doit conserver.** source_spans ; relation_ids ; chronologie; incertitude; échecs; remplacement; inconnues

**Forme des ressources.** CPU et RAM proportionnels à la sélection limitée ; pas de GPU ni de location

** Limite. ** La qualité est limitée par la relation en amont et la couverture par l'État du dépôt

### Mécanismes de livraison

registres, modes, profils de tissage, commandes de stimulation, de densité et de deslop

**Responsabilité.** Fournir des contraintes de livraison mesurées, telles que le rythme, la densité, le registre et la trajectoire de tissage, pour ce produit et ce public. Exemple : donner à une explication pour enfants des paquets plus courts et un modèle de récurrence différent d'un rapport technique sans modifier les faits sous-jacents.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

### Prétraitement du discours

tranches délimitées exactes, candidats de référence FastCoref et liens d'opérandes isanlp RST loués

**Responsabilité.** Identifiez les référents candidats et les durées de discours avant de raisonner la classification tout en préservant les coordonnées exactes de la source. Exemple : liez « ce » au candidat pompe nommé et exposez les deux clauses reliées par une relation de discours causale.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

**Principaux outils publics.**[IsaNLP RST](https://github.com/tchewik/isanlp_rst),[FastCoref](https://github.com/shon-otmazgin/fastcoref)

### Reconstruction avancée d'artefacts entiers

prérequis, référents, lien causal, progression, introduction et conclusion

**Responsabilité.** Reconstruire le matériel sélectionné dans l'ordre du lecteur, en restaurant les prérequis, les référents, les liens de causalité, la progression et une fin honnête. Exemple : introduire l'objectif avant la procédure et clôturer sur une question non résolue lorsqu'aucune conclusion n'existe.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

### Graphique Pourquoi et projection des dépendances

vue déterministe des arêtes de graphes classifiées qui ne peut pas introduire de nouvelles affirmations de raisonnement

**Responsabilité.** Traduire les bords de relation acceptés en dépendances inspectables et expliquer pourquoi les vues sans ajouter d'interprétation. Exemple : montrez que la conclusion B dépend de la prémisse A parce que cette arête classifiée exacte existe.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

**Principaux outils publics.**[RéseauX](https://github.com/networkx/networkx)

### Réponse interactive fondée


**Responsabilité.** Renvoie une réponse conversationnelle avec le raisonnement, la provenance, l'incertitude et les chemins d'expansion pertinents. Le chemin de réponse peut parcourir des conversations complètes et des cycles de vie de preuves sans prétendre être une génération de documents.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

### Pont du protocole humain

codage orienté récepteur de la charge utile fixe prise en charge

**Responsabilité.** Convertir une charge utile fixe et prise en charge en une forme que la personne concernée peut suivre, en utilisant le contrat de produit et le modèle de livraison mesuré ; cela ne peut pas changer les preuves. Exemple : transformez la même chaîne de raisonnement fondée en un e-mail concis ou un guide par étapes en modifiant la structure de livraison, et non en conclusions.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

### Assemblage de contexte interactif


**Responsabilité.** Créez un graphique de preuves et de raisonnement limité pour la question actuelle, en préservant la chronologie, les corrections, les échecs, l'identité de la source et l'autorisation. Il fournit un contexte à la réponse sans aplatir le corpus en extraits de recherche.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

### Adhésion sans perte


**Responsabilité.** Admettre les octets originaux et les événements natifs avant l'interprétation, en enregistrant uniquement les faits d'arrivée observés. Les descriptions, les horodatages déduits du contenu, des identités et des relations restent des observations versionnées distinctes.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

### Preuve primaire


**Responsabilité.** Détenir les dépôts faisant autorité auxquels les représentations et produits ultérieurs doivent pouvoir remonter. Leur existence perdure même lorsque le système ne peut pas encore expliquer leur signification ou leur relation.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

### Arbre provisoire complet

structure complète de preuves, de dépendances, d'alternatives et d'échecs avant l'élagage

**Responsabilité.** Conservez l'arborescence complète des candidats, y compris les alternatives, les échecs, les inconnues et les vues remplacées, afin que l'effondrement puisse voir ce qu'il perdrait. Exemple : conserver à la fois un traitement ayant échoué et la correction ultérieure avant de sélectionner le matériel pour un guide.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

### Graphique de raisonnement

chronologie, relations typées, cycles de vie des réclamations, échecs et incertitudes

**Responsabilité.** Maintenir la carte des propositions, de la chronologie, des tentatives, des résultats, des conflits, des dépendances et de l'incertitude en fonction de la demande. Exemple : connecter un traitement ayant échoué à la correction qui l'a remplacé sans supprimer aucun des deux états.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

### Demande + Contrat d'artefact

objectif, destinataire, conteneur, canal, budget et véracité

**Responsabilité.** Gelez l'objectif, le récepteur, le produit, le canal, le budget et la norme de vérité afin que chaque rouage en aval résolve le même travail. Exemple : distinguer une explication générale de 500 mots d'un rapport d'incident technique avant de commencer la sélection des preuves.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

### Expansion inversée

rassembler en arrière sans tailler; mesurer la contribution marginale

**Responsabilité.** Passez de la demande ou des preuves ultérieures aux enregistrements associés antérieurs et rassemblez le parcours complet du candidat avant que quoi que ce soit ne soit rejeté. Exemple : suivez une question actuelle sur les algues en remontant aux enregistrements antérieurs du pH, de la taille de la piscine, de l'entretien et du contexte d'utilisation.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

### Mouvements rhétoriques dactylographiés

tâches et dépendances sémantiques, sans jamais en-tête de sous-chaînes

**Responsabilité.** Attribuez à chaque unité sélectionnée une tâche de communication et une dépendance basées sur le contrat de produit, et non sur un mot d'en-tête correspondant. Exemple : marquez les preuves comme étayant une réclamation et un échec comme établissant une récupération plutôt que de qualifier les deux de « contexte ».

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

### Reconstruction sémantique

entités, propositions, épisodes, tentatives, résultats et questions

**Responsabilité.** Convertissez les observations sources en objets sémantiques attribués sans décider de leur importance ou de leur présentation finale. Exemple : représentez un correctif proposé, la tentative, son échec et la question restante sous forme d'enregistrements liés distincts.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

### Représentations versionnées


**Responsabilité.** transcriptions, structure, texte, OCR, mise en page et vues dérivées

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

### Pourquoi c'était important

motivation attribuée, préoccupation, conséquence et pertinence actuelle

**Responsabilité.** Présentez des preuves directes et explicitement attribuées sur la raison pour laquelle l'attention a été investie, laissant les raisons non étayées inconnues. Exemple : présumer qu'une tâche de maintenance est importante parce qu'elle protège les personnes utilisant un équipement partagé lorsque le archive le confirme, plutôt que de deviner ce motif à partir d'une seule question technique.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

### Raisonnement + moteur d'artefacts

reconstruction, effondrement, protocole humain et rendu Markdown atomique

**Responsabilité.** Coordonner le chemin de reconstruction et de rendu délimité et exposer le reçu de chaque étape ; il ne remplace pas le jugement d'un spécialiste. Exemple : effectuer une requête de composition via la sélection, la planification, la réalisation, la validation et l'écriture atomique.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

### Assemblage + Gestionnaire de Capacités

parcourt les champs obligatoires en arrière, évalue les conditions préalables, sélectionne les spécialistes véridiques, ordonne les vagues de dépendance et ignore les travaux de valeur nulle

**Responsabilité.** Choisissez quels spécialistes sont nécessaires, dans quel ordre ils fonctionnent et quel travail n'ajoute aucune valeur ; il ne fait pas leur travail. Exemple : planifier la réalisation de la relation avant la réalisation de la phrase et ignorer une passe stylistique indisponible qui n'apporte rien de requis.

**Doit préserver.** must_preserve_fields ; field_lineage; explicit_indisponibilité

**Forme de ressource.** CPU ; mémoire faible ; pas de GPU ni de location

** Limite. ** Les observations sur les coûts et la valeur exposent les décisions mais ne définissent jamais l'importance humaine

### Réconciliateur de budget de transporteur atomique

mesure la source indivisible, la colle et les supports de relation avant la réalisation et redistribue le budget fixe du produit entier par une véritable marge de section

**Responsabilité.** Vérifiez si les faits indivisibles et les supports relationnels peuvent s'adapter à chaque section, puis déplacez uniquement la marge disponible tout en préservant le budget total du document. Exemple : agrandissez une section de procédure de 90 mots qui contient une instruction atomique requise de 120 mots en empruntant des mots inutilisés à une autre section.

**Doit préserver.** Whole_artifact_budget ; requis_rhetorical_jobs ; autorité_source ; graph_shape

**Forme de ressource.** CPU ; durée d'exécution proche de zéro ; évite le gaspillage de travail GPU/modèle/vérificateur Stage 8

**Boundary.** ne peut pas compresser une proposition indivisible ; échoue si tous les transporteurs requis dépassent le budget produit déclaré

### Gestionnaire de reliure lié à la source

déplace uniquement une branche isolée complète lorsque la tâche de produit qui lui est attribuée est incompatible et qu'une destination est prouvée compatible

**Responsabilité.** Déplacer une branche de preuve complète et isolée vers la seule section dont le métier peut légitimement l'utiliser, tout en refusant les déplacements ambigus ou porteurs de relation. Exemple : réaffectez une note de récupération autonome de la configuration au dépannage sans la dupliquer dans les deux sections.

**Doit préserver.** branch_identity ; source_spans ; relation_ids ; marginal_gain_ledger

**Forme de ressource.** CPU ; faible latence ; pas de GPU ni de location

**Boundary.** refuse les mouvements relationnels, ambigus, partiels ou en surcapacité

### Réalisateur de relations à l'échelle du document

transforme les bords de raisonnement acceptés de même section et de section transversale en un langage conjonctif compact et rejouable indépendamment sans répéter les deux opérandes

**Responsabilité.** Transformez les relations graphiques acceptées en un langage de connexion court tout en gardant la direction, les opérandes et les étendues sources rejouables indépendamment. Exemple : réalisez A-causes-B comme un pont causal limité au lieu d'imprimer A et B comme des faits adjacents non liés.

**Doit préserver.** relation_direction; identité_opérande ; exact_carrier_spans ; source_spans ; section_lignée

**Forme de ressource.** CPU ; durée d'exécution proche de zéro ; pas de GPU ni de location

**Boundary.** ne réalise que des types de relations explicitement acceptés ; les ponts compacts préservent l'identité des bords typés mais restent formulés mécaniquement ; les bords de même porteur, ambigus, implicites et inconnus restent visibles dans le graphique mais non affirmés en prose

### Moteur de connaissances


**Responsabilité.** Coordonnez l'adhésion, les représentations dérivées, la recherche, la provenance et les emplois durables sans fusionner ces responsabilités en un seul état de vérité. Il expose les interfaces prises en charge aux consommateurs tandis que les preuves principales restent adressables de manière indépendante.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

### Microplanificateur de clauses/phrases dactylographiées

attribue des supports liés à la source aux travaux rhétoriques dactylographiés et compile des plans de clauses, de phrases et de paragraphes

**Responsabilité.** Divisez le sens et les relations approuvés en tâches de clause, de phrase et de paragraphe tout en préservant leurs liaisons sources ; il n'invente pas de formulations ou de revendications. Exemple : prévoir une clause cause suivie de sa conséquence et de sa transition pour le réalisateur de surface.

**Doit conserver.** semantic_unit_ids ; relation_ids ; source_forms

**Forme de ressource.** CPU ; faible latence ; pas de GPU ni de location

**Boundary.** n'invente pas de proposition manquante ni ne répare une relation non classifiée

**Principaux outils publics.**[SpaCy](https://github.com/explosion/spaCy),[BlingFire](https://github.com/microsoft/BlingFire)

### Gestionnaire de contrats de produits

convertit le genre, le récepteur, le but, le canal, la véracité, l'attention et le budget en champs de produits requis et en travail rhétorique

**Responsabilité.** Transformez la demande en une liste de contrôle concrète pour le produit fini sans choisir de preuve ni l'écrire. Exemple : pour un manuel d'utilisation, exigez des prérequis, des actions ordonnées, des conseils de récupération et une fermeture avant le démarrage d'un éditeur.

**Doit conserver.** déclaré_usage ; récepteur; véracité; canal

**Forme de ressource.** CPU ; durée d'exécution proche de zéro ; pas de GPU ni de location

**Boundary.** ne déduit pas la signification de la source ni ne choisit les faits

### Réalisateur de surfaces contractuelles

applique la grammaire délimitée, la morphologie, la typographie, la perspective et les transformations typées aux unités de livraison

**Responsabilité.** Appliquer la grammaire, la morphologie, la typographie et la perspective autorisée à un plan déjà approuvé ; il ne peut pas décider d'un nouveau sens. Exemple : transformer un plan impératif dactylographié en instruction grammaticale sans ajouter une allégation de sécurité qui n'a jamais été fournie.

**Doit préserver.** Claim_authority ; source_and_relation_bindings ; rhétorique_job

**Forme de ressource.** CPU ; l'éditeur candidat facultatif peut utiliser un bail GPU existant mais n'a aucune autorité

**Boundary.** la grammaire fermée est fidèle mais peut rester stylistiquement rigide

**Principaux outils publics.**[SpaCy](https://github.com/explosion/spaCy)

## Gestion, vérification et opérations

### Amf Ari


**Responsabilité.** Exécutez le classificateur argument-relation épinglé sur les paires de propositions fournies et renvoyez les tentatives de support, de conflit, de reformulation ou d'absence de relation notées. Il ne crée pas de propositions, n'en déduit pas de motifs et ne certifie pas ses propres labels.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

**Principaux outils publics.**[OuvrirVINO](https://github.com/openvinotoolkit/openvino),[Modèle AMF ARI RoBERTa OpenVINO](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8)

### Indexeur de discussion


**Responsabilité.** Conserve les conversations dans un enregistrement long au lieu de les laisser dans la fenêtre de discussion.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

### Indexeur de fichiers


**Responsabilité.** Découvrez les fichiers éligibles et soumettez un travail d'indexation limité et préservant la provenance. Il ne doit pas traiter les dates du système de fichiers, les noms de fichiers ou le texte extrait comme une heure de création, une identité ou un motif faisant autorité.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

### Télémétrie matérielle


**Responsabilité.** Enregistrez un historique limité de l'état de la machine afin que les pannes puissent être comparées à la puissance, à la température, à la mémoire et à l'état de l'accélérateur. La description publique omet la cadence d'échantillonnage privée et la disposition de la machine.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

**Principaux outils publics.**[psutil](https://github.com/giampaolo/psutil)

### Image


**Responsabilité.** Produire des images localement afin qu'un concept visuel n'ait pas à traverser une frontière d'inférence externe. La génération d’images reste distincte de l’autorité de preuve et de l’autorisation de publication.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

**Principaux outils publics.**[stable-diffusion.cpp](https://github.com/leejet/stable-diffusion.cpp),[Z-Image-Turbo](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo),[Référence d'emballage Z-Image-Turbo-Windows](https://github.com/airesearch-official/Z-Image-Turbo-Windows)

### Ollama


**Responsabilité.** L'esprit lourd. Plus lent et plus vaste, réservé aux questions qui nécessitent véritablement plus de réflexion que de vitesse.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

**Principaux outils publics.**[Ollama](https://github.com/ollama/ollama),[Qwen3](https://github.com/QwenLM/Qwen3)

### Ollama Intégrer


**Responsabilité.** Rend l'écriture consultable par le sens plutôt que par les mots exacts.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

**Principaux outils publics.**[Ollama](https://github.com/ollama/ollama),[Texte intégré nomique](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5)

### Location d'électricité


**Responsabilité.** Permet à la machine de tourner au ralenti et de se réveiller complètement pour un vrai travail.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

### Retitreur de conversation


**Responsabilité.** Donne des noms de conversations qui signifient quelque chose, de sorte que la liste soit trouvable plutôt qu'un mur de premières phrases.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

### Observateur sémantique


**Responsabilité.** Vérifie si une réponse est étayée par le matériel dont elle prétend provenir.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

**Principaux outils publics.**[Transformateurs](https://github.com/huggingface/transformers),[MiniVérification](https://github.com/Liyan06/MiniCheck),[FactCG](https://github.com/derenlei/FactCG)

### Analyse de pente


**Responsabilité.** Garde une trace de la façon dont chaque esprit échoue et si cela s'améliore ou empire.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

**Principaux outils publics.**[SpaCy](https://github.com/explosion/spaCy),[BlingFire](https://github.com/microsoft/BlingFire),[NLTK](https://github.com/nltk/nltk)

### Discours


**Responsabilité.** Transforme la parole en texte, donc parler est une façon d'écrire les choses.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

**Principaux outils publics.**[Discours](https://github.com/speaches-ai/speaches),[murmurer plus vite](https://github.com/SYSTRAN/faster-whisper),[distillation-plus rapide-chuchotée-large-v3](https://huggingface.co/Systran/faster-distil-whisper-large-v3)

### Service de tâches


**Responsabilité.** Lisez les enregistrements de tâches autorisées comme preuve du travail planifié sans les convertir en rappels, en motifs déduits ou en vérité de corpus.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

### vLLM


**Responsabilité.** L'esprit de tous les jours. Rapide, toujours chargé, répond à presque tout.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

**Principaux outils publics.**[vLLM](https://github.com/vllm-project/vllm),[Qwen3](https://github.com/QwenLM/Qwen3)

### Travaux de scène durables

lots limités, points de contrôle, annulation, reprise et échec partiel

**Responsabilité.** Exécutez de longues étapes d'artefact en tant que tâches limitées pouvant être reprises avec des états de terminal véridiques au lieu de les lier à une seule requête du navigateur. Exemple : reprendre après un point de contrôle de promotion vérifié plutôt que de répéter un raisonnement coûteux après une interruption.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

### Exécution + Gestionnaire de manifeste

exécute l'adaptateur attribué et enregistre la méthode physique, le point de terminaison, la révision du modèle, les hachages, les bords d'appel, la synchronisation, les tentatives et la disposition

**Responsabilité.** Exécutez chaque spécialiste assigné et enregistrez ce qui est physiquement exécuté, avec ses entrées, son identité, son timing, ses tentatives et ses résultats. Exemple : montrez que le classificateur AMF épinglé a géré l'étape 2 au lieu de faire confiance à une étiquette de manifeste qui indique simplement qu'il l'a fait.

**Doit conserver.** input_hashes ; adaptateur_identité ; état_échec

**Forme des ressources.** Coordinateur du processeur ; délègue le travail du GPU uniquement par l'intermédiaire des propriétaires de bail déclarés

**Boundary.** enregistre l'exécution ; ne peut pas certifier son propre succès

### Arbitrage de location de GPU


**Responsabilité.** Coordonnez les transferts de conseils entre les charges de travail des accélérateurs gérés par la plateforme sans exposer l'identité physique de l'appareil ni anticiper le travail déjà en cours.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

### Coordinateur de résidence Power

**Responsabilité.** Maintenir un modèle d'état ACTIVE, WARM, IDLE et JAMAIS sur l'ensemble des mécanismes d'alimentation et de résidence de la plateforme distribuée.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

### Grand livre de charge utile attendu/observé

associe la responsabilité de chaque rouage à ses champs observés, à l'état de préparation, aux omissions, à la valeur, au coût, au timing, aux tentatives et à la demande de réparation

**Responsabilité.** Comparez ce que chaque rouage était censé apporter avec ce qu'il a réellement transmis, y compris le coût et les intrants manquants. Exemple : exposez que l'analyse des relations a duré 40 secondes mais n'a fourni aucun bord de connexion utilisable à l'éditeur.

**Doit préserver.** handoff_identity ; résumés; champs_manquants ; coût_base

**Forme de ressource.** CPU ; proche de zéro par rapport au raisonnement et à la vérification

**Boundary.** La synchronisation des sections portables ne remplace pas la synchronisation de l'étape physique/du modèle dans le manifeste d'exécution

### Responsable qualité conscient du produit

vérifie l'achèvement rhétorique, le raisonnement connectif, la lisibilité, la typographie, la duplication, l'attention, le budget, le tissage, le slop et les actions exécutables pour le produit demandé

**Responsabilité.** Évaluez si ce produit spécifique fonctionne pour son lecteur et son objectif déclarés sur des axes de qualité distincts, puis identifiez l'étape de réparation responsable. Exemple : un manuel peut échouer en manquant des conseils de récupération même lorsque chaque phrase est grammaticale et fondée.

**Doit conserver.** individual_axis_results ; rejeté_candidate_evidence

**Forme de ressource.** CPU plus vérificateur/deslop limité HTTP ; historiquement la plus grande part de Stage 8

**Boundary.** les axes de genre doivent être mesurés et versionnés ; un score de qualité opaque est interdit

### Gestionnaire de reçus + promotions

recalcule indépendamment les invariants et permet la promotion et l'écriture d'artefacts atomiques uniquement à partir d'un reçu PASS

**Responsabilité.** Vérifiez indépendamment le bundle et écrivez l'artefact uniquement après chaque passe invariante requise. Exemple : refuser la promotion lorsque le moteur de rendu signale un succès mais que sa réception ne peut pas reproduire une liaison source.

**Doit préserver.** Failure_results ; inconnues; release_identity ; rollback_boundary

**Forme des ressources.** CPU et E/S ; pas de GPU ni de location

**Boundary.** L'authenticité du manifeste dépend en fin de compte de la liaison de version/configuration immuable examinée

### Provenance + Contrôle des pertes

identité source, état épistémique, inférence, invention et branches rejetées

**Responsabilité.** Gardez chaque déclaration liée à qui ou quoi l'a fournie, quand elle s'est appliquée et si elle a été observée, déduite, remplacée, rejetée ou inconnue. Exemple : conserver une réinterprétation ultérieure sans écraser la croyance antérieure qui a réellement guidé une action.

**Doit préserver.** Identité exacte du graphique, provenance de la relation et limite déclarée des composants.

**Forme des ressources.** Le déploiement en direct enregistre l'utilisation réelle du processeur, de la mémoire, du stockage, de l'accélérateur et du bail ; ce catalogue public n'expose pas le placement des machines.

**Boundary.** Peut assumer uniquement sa responsabilité déclarée en matière de graphe et ne peut pas réparer les preuves en amont manquantes ou non étayées.

## Composants déclarés supplémentaires

### Passerelle Web sécurisée

Fournit un accès à distance authentifié à partir de clients approuvés sans exposer directement les services de plate-forme privée à l'Internet public.

### Superviseur de plateforme

Démarre les services dans l’ordre des dépendances, observe leur état de santé et effectue des actions de redémarrage limitées. Son échec supprime la supervision coordonnée sans redéfinir l’état des services qui continuent de fonctionner.

## Limite d'exhaustivité

Le catalogue couvre les composants logiques actifs dans le graphe d'architecture maintenu, et non tous les packages transitifs installés par chaque environnement d'exécution. Une future version logicielle nécessite une nomenclature logicielle exacte et un ensemble de licences générés à partir des octets spécifiques distribués.
