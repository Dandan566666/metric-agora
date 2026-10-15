# Premier plan de conception

[Accueil](README.fr.md) · [Carte de recherche](DATA_DOMAINS.fr.md) · [Gouvernance](GOVERNANCE.fr.md) · [Participation](CONTRIBUTING.fr.md)

Version 0.1 · 16 octobre 2026 · Proposition destinée à de futures communautés indépendantes. Cette publication contient uniquement de la documentation. Toutes les capacités décrites ci-dessous sont proposées, et non mises en œuvre.

## Faire d’une question un objet que chacun peut examiner

Quelque part, une personne regarde un chiffre qui vient d’être publié et se demande s’il décrit le monde dans lequel elle vit. Elle devrait pouvoir poursuivre cette question au-delà d’un titre. Elle devrait pouvoir accéder au tableau d’origine, voir les définitions, comparer d’autres observations et comprendre ce que les éléments permettent d’affirmer.

Ce plan invite une communauté à rendre ce parcours possible. Commencez par une question assez limitée pour être étudiée et assez importante pour compter. Construisez un chemin de preuves qu’une autre personne pourra suivre. Exposez les erreurs de nos propres méthodes aussi volontiers que celles que nous découvrons ailleurs. Chaque enquête reproductible peut devenir le socle de la suivante.

## Objectif et premier périmètre

Développer un outil ouvert qui aide à comparer des éléments publics complexes, à expliquer les écarts, à repérer des erreurs démontrables ou des présentations sélectives et à construire des estimations mieux étayées. Le résultat central devrait être une enquête consultable et vérifiable, accompagnée d’un historique montrant comment ses conclusions ont été établies.

Le périmètre à long terme couvre les 84 pistes de la carte de recherche. Une communauté naissante devrait choisir une question, une zone géographique et une courte période pour lesquelles la documentation est adaptée. Elle devrait démontrer l’utilité de ses méthodes avant d’élargir la couverture ou d’automatiser la collecte. Ce plan n’engage l’initiateur à rien construire, maintenir, financer ou exploiter.

## L’unité de travail

Chaque enquête devrait préciser sa question, ses limites géographiques, sa période d’observation, sa population cible, son indicateur, son unité, son dénominateur et la décision qu’elle vise à éclairer. Elle devrait distinguer une comparaison descriptive d’une affirmation causale ou d’une estimation fondée sur un modèle. Ces approches nécessitent des éléments de preuve différents.

Une fonction centrale d’un futur outil devrait être de **vérifier un chiffre qui vient d’être publié** : recevoir un lien vers une source, une affirmation citée, un rapport ou un graphique ; retrouver et authentifier la publication d’origine ; extraire l’affirmation exacte et ses définitions ; rechercher des éléments comparables et indépendants ; puis présenter le dossier obtenu. L’authenticité de la publication, la qualité de la mesure et les éléments qui étayent une interprétation sont des questions distinctes. Une publication officielle authentique peut présenter des limites ; une estimation privée peut être solidement étayée. L’interface devrait rendre ces distinctions visibles plutôt que les réduire à une seule étiquette vrai/faux. Cette première publication ne contient aucune fonction de réception ou de vérification de ce type.

Un dossier de preuves devrait contenir les fiches suivantes :

| Fiche | Contenu minimal |
| --- | --- |
| Question et affirmation | Énoncé exact, périmètre, alternatives et éléments susceptibles de le contredire |
| Source | Éditeur, URL d’origine, document/tableau/page, dates de publication et de consultation, conditions de réutilisation |
| Observation | Valeur, unité, zone géographique, période de référence, définition, population, informations sur l’échantillonnage ou la couverture, incertitude lorsqu’elle est disponible |
| Version | Publication initiale, date de révision, trace de la récupération et référence archivée légalement ou empreinte du contenu |
| Filiation | Producteur d’origine, jeux de données en amont, citations, transformations et dépendances |
| Comparaison | Vérifications de compatibilité, exclusions, formules de conversion, hypothèses et différences restantes |
| Résultat | Constats, explications alternatives, limites, sensibilité aux hypothèses, commentaires des relecteurs et historique des révisions |

Une empreinte peut montrer qu’un fichier conservé a été modifié. Elle ne peut pas prouver l’exactitude de son contenu. Si la redistribution d’une source n’est pas autorisée, conservez une citation légale et les métadonnées autorisées plutôt que de la republier.

## Proposition de déroulement d’une enquête

1. **Définir la question avant de rassembler les éléments.** Consigner le périmètre, les indicateurs envisagés, les critères d’inclusion, les règles de comparaison et les cas d’échec attendus afin de réduire la sélection opportuniste des résultats.
2. **Rechercher des sources potentielles.** Inclure les notes méthodologiques et les historiques de révision. Consigner la couverture de la recherche et les lacunes connues ; l’absence dans les résultats de recherche ne prouve pas l’inexistence.
3. **Extraire en vérifiant.** L’IA peut proposer des champs et des citations. Vérifier les chiffres importants dans le tableau ou la page d’origine. Consigner les valeurs manquantes au lieu d’inventer des remplacements. Conserver la langue d’origine à côté des traductions lorsque l’interprétation importe.
4. **Vérifier la comparabilité.** Harmoniser les zones géographiques, populations, tranches d’âge, périodes, unités, bases de prix, traitements saisonniers, méthodes d’échantillonnage et définitions. Signaler les séries incompatibles et expliquer pourquoi elles ne peuvent pas être combinées.
5. **Cartographier les dépendances.** Regrouper les sources qui partagent des observations en amont. Un agrégateur mondial et un rapport national peuvent contenir la même série d’origine. Des fournisseurs de modèles différents peuvent aussi partager des sources d’entraînement ou des résultats de recherche documentaire.
6. **Appliquer des vérifications adaptées.** Utiliser les identités comptables lorsque les définitions le permettent ; examiner les révisions et la cohérence interne des séries ; comparer des méthodes de mesure réellement indépendantes. Traiter les mesures issues de satellites, de transactions, de recherches en ligne et de plateformes comme des indicateurs indirects ayant leurs propres problèmes de sélection et de couverture.
7. **Mettre les explications à l’épreuve.** Examiner les changements de dénominateur, les délais de publication, l’activité informelle, les refontes d’enquête, les changements structurels et les autres causes plausibles. Mener des analyses de sensibilité et, si possible, tester les méthodes sur des périodes réservées à l’évaluation ou des révisions historiques connues.
8. **Publier et inviter à la contestation.** Fournir le dossier, les documents d’appui dont la diffusion est autorisée, les calculs reproductibles, les éléments contradictoires et les conditions qui modifieraient la conclusion. Permettre les corrections et conserver un historique versionné.

## Comment décrire un écart

Formuler des constats précis et vérifiables : une divergence de définition ; un décalage temporel ou géographique ; une limite de couverture ou d’échantillonnage ; une révision ; une erreur de calcul ou d’extraction ; une présentation sélective étayée par des omissions identifiées ; une incohérence inexpliquée ; ou des éléments insuffisants.

Distinguer le défaut observé d’une source du motif supposé de son auteur. Décrire une manipulation intentionnelle nécessite des preuves qui dépassent le caractère statistiquement surprenant d’un résultat. Appliquer les mêmes critères aux institutions officielles, entreprises privées, chercheurs, médias, groupes de plaidoyer et au projet lui-même. Un écart peut faire émerger une question sans permettre de déterminer quelle source est erronée.

Ne pas calculer automatiquement la moyenne de chiffres divergents. La combinaison d’estimations nécessite un modèle explicite, une prise en compte des dépendances et de l’incertitude, ainsi qu’une analyse de sensibilité aux hypothèses. Ne pas déduire une valeur cachée uniquement parce que plusieurs indicateurs indirects vont dans le même sens. Lorsque les éléments ne permettent pas d’identifier la quantité, signaler cette limite.

## Rôle de l’IA et limites du système

L’IA peut aider à la recherche, à l’extraction, à la traduction, à la classification, à la formulation d’hypothèses et à l’explication. Elle ne doit pas ajouter silencieusement des faits manquants, transformer une citation générée en preuve ni déclarer une source malhonnête sur la seule base d’un motif détecté. Consigner le modèle, son fournisseur et sa version lorsque ces informations sont disponibles, la date, les requêtes ou consignes de travail, les appels d’outils et les corrections humaines. Respecter les conditions des sources et éviter d’envoyer des données confidentielles ou personnelles à un fournisseur de modèles sans fondement approprié.

Une conception future pourrait séparer la recherche des sources, l’extraction, un stockage de la provenance, les calculs déterministes, l’examen et la présentation. Traiter les documents récupérés comme des données non fiables ; le texte d’une source ne doit jamais autoriser des actions d’outils ni modifier les règles de l’enquête. Isoler le traitement des documents et le code non fiable des identifiants et des opérations privilégiées. Cette première proposition ne sélectionne aucun fournisseur de modèles ou d’infrastructure. Les futures communautés devront décider elles-mêmes de leurs coûts, de leurs accès, de leur hébergement et de leurs dispositifs de sécurité.

## Étapes proposées

| Étape | Livrable | Critère d’acceptation |
| --- | --- | --- |
| 0 : former une communauté | Fork maintenu, responsables nommés, règles publiques, déclaration des conflits d’intérêts et des ressources | Chacun sait où les décisions sont prises et qui peut les exécuter |
| 1 : démontrer la méthode manuellement | Un dossier de preuves, la filiation des sources, un tableau de comparabilité, des calculs et un registre des désaccords | Chaque chiffre essentiel est traçable ; une autre personne peut reproduire les calculs ; les limites et les éléments contraires sont visibles |
| 2 : spécifier l’outil | Modèle de données, spécification des adaptateurs de sources, modèle de menace, cas d’évaluation et proposition d’interface | Le périmètre et le comportement en cas d’échec sont explicites ; l’exactitude de l’extraction et les vérifications des citations ont des critères mesurables |
| 3 : envisager un prototype | Un plan de mise en œuvre et une licence logicielle faisant l’objet d’un accord distinct | Les participants approuvent la propriété, les ressources, la sécurité, l’évaluation et les modalités de maintenance avant le développement |
| 4 : élargir de façon réfléchie | Domaines supplémentaires et enquêtes reliant plusieurs domaines | Chaque ajout respecte les mêmes normes de comparabilité, de filiation, de respect de la vie privée et de reproductibilité |

Il s’agit d’étapes suggérées, et non de délais ou de promesses de financement. Cette première publication s’arrête avant la mise en œuvre.

## Évaluer avant de changer d’échelle

Une future communauté devrait tester ses méthodes sur des erreurs documentées, des différences légitimes de définition, des publications révisées, des indicateurs indirects incompatibles, des répétitions d’une même source et des cas sans réponse identifiable. Mesurer séparément les erreurs d’extraction et de citation et la justesse des interprétations. Inclure des graphiques trompeurs, des dénominateurs omis, des erreurs de reconnaissance optique de caractères, des termes traduits et des versions obsolètes. Comparer le travail assisté par l’IA à une référence manuelle soigneusement examinée. Publier les échecs aussi bien que les réussites.

Pour l’étude pilote sur l’emploi proposée ici, comparer le chômage, la participation au marché du travail, les mesures de l’emploi rapporté à la population, les heures travaillées et les salaires pour un même lieu et une même période, selon la disponibilité des données et la compatibilité des définitions. Les données administratives ou les enquêtes indépendantes peuvent apporter un éclairage supplémentaire, mais il faut d’abord en examiner la couverture et les dépendances. Une baisse du taux de chômage ne tranche pas, à elle seule, la question plus large.

## Faire avancer ce travail

Le futur outil commence avec des personnes prêtes à examiner soigneusement une affirmation. Une citation vérifiée, une comparaison rigoureuse, une limite clairement expliquée : voilà les matériaux à partir desquels se construit la compréhension publique. Choisissez une question, associez d’autres personnes à l’enquête et laissez une trace assez solide pour que des inconnus puissent la mettre à l’épreuve. Que ce soit la première réussite de votre communauté.

## Références méthodologiques

Ces références éclairent la proposition ; elles ne certifient ni ne soutiennent ce projet.

- [Principes fondamentaux de la statistique officielle des Nations unies](https://unstats.un.org/fpos) : méthodes professionnelles, transparence, confidentialité et interprétation responsable.
- [Présentation du cadre d’évaluation de la qualité des données du FMI](https://www.imf.org/external/np/sta/dsbb/2003/eng/dqaf.htm) : un cadre pour examiner les pratiques statistiques et la qualité des données.
- [Présentation de W3C PROV](https://www.w3.org/TR/prov-overview/) : représentation de la provenance des entités, des activités et des agents.
- [Présentation de la population active par l’OIT](https://www.ilo.org/resource/labour-force) : distinctions entre emploi, chômage et situation hors de la population active.
