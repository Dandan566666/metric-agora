# Proposition de gouvernance

[Accueil](README.fr.md) · [Conception](DESIGN.fr.md) · [Participation](CONTRIBUTING.fr.md)

Version 0.1 · 16 octobre 2026. Cette proposition s’adresse aux communautés créées à partir de forks. Aucun service de vote, organe élu, mécanisme d’application des règles ni dispositif de fusion automatique ne fonctionne dans cette première publication.

## Mettre l’avenir entre les mains des participants

Un projet qui demande aux institutions puissantes de rendre leurs éléments de preuve vérifiables devrait aussi rendre ses propres décisions vérifiables. Les personnes qui apportent leur temps, leur savoir et leur attention méritent de savoir comment les priorités sont choisies, comment l’autorité est exercée et comment elle peut être contestée.

L’invitation est de bâtir une communauté dont l’orientation appartient à ses participants. Publiez les règles. Montrez qui détient les clés. Préservez les désaccords. Donnez à la génération suivante un moyen de poursuivre le travail sans attendre l’autorisation d’un fondateur. La proposition ci-dessous offre un point de départ pour cette responsabilité partagée.

## Publication et départ

L’initiateur publie la vision et la conception initiale, puis cesse de participer à la gestion. Le dépôt d’origine reste volontairement sans maintenance : aucun examen, aucune modération, aucun transfert, aucun choix de successeur, aucune exploitation de service ni aucun soutien financier n’est promis. L’initiateur peut conserver la propriété du compte requise par GitHub ; cette réalité technique ne crée aucune promesse de donner suite aux demandes de la communauté. Le silence ne doit jamais être interprété comme une approbation.

Chacun peut réutiliser les documents d’origine conformément à leur licence et organiser un fork sans demander d’autorisation. Un fork devrait identifier ses propres responsables et indiquer clairement qu’il s’agit d’une communauté indépendante, sans succession exclusive automatique ni approbation sous-entendue. Plusieurs communautés peuvent coexister, collaborer, être en désaccord ou développer des conceptions différentes. Aucune ne peut engager une autre sans son accord explicite.

## Établir une communauté opérationnelle

Publiez dans le fork un avis de fondation précisant son périmètre, ses participants fondateurs, ses responsables provisoires, le lieu de décision et la procédure d’adoption d’une charte. Tant qu’un système de vote opérationnel et un électorat suffisamment large n’existent pas, rendez publics le processus provisoire et l’identité des personnes qui exercent le contrôle. Ne présentez pas quelques comptes techniques comme une institution déjà décentralisée.

Pour un fork appartenant à une organisation, au moins deux personnes consentantes devraient détenir le rôle GitHub Owner afin d’assurer la continuité. GitHub ne propose pas d’organisations sans propriétaire et n’impose pas de règle constitutionnelle de signatures multiples aux Owners : ils conservent leurs pouvoirs administratifs. Réduisez la dépendance à leur égard par des décisions publiques, des permissions courantes minimales, des mandats limités, des revues des accès, des miroirs et la possibilité de créer à nouveau un fork.

## Rôles et autorité

Chacun peut proposer des idées, questionner les éléments de preuve, signaler des erreurs et soumettre des modifications à un fork maintenu. Le droit de vote n’a pas besoin de conférer un accès en écriture au dépôt. Les responsables élus exécutent les décisions consignées, gèrent les accès et la sécurité et publient les opérations administratives. Les relecteurs méthodologiques évaluent les éléments selon des normes publiques et déclarent leurs conflits d’intérêts. Ils doivent motiver tout rejet de façon à permettre sa contestation.

Les votes déterminent les priorités, la gouvernance, les ressources et les modifications proposées. Les votes ne rendent pas vraie une affirmation empirique. Un contre-exemple étayé reste pertinent même si son auteur perd un vote. Préservez les opinions minoritaires, les demandes de correction, les réponses des sources et l’historique des conclusions révisées.

## Règles de vote suggérées, à adopter ou à réviser

Utilisez un registre explicite des électeurs, les identifiants numériques stables des comptes GitHub et une voix par participant admissible. Comme proposition initiale, exigez des comptes créés depuis au moins 90 jours, une participation au projet s’étendant sur au moins 30 jours et un examen public de l’admissibilité. Ces mesures rendent les abus plus coûteux ; elles ne prouvent pas qu’un compte correspond à une seule personne et n’empêchent pas une prise de contrôle coordonnée. Publiez les éléments justifiant l’admission sans exiger que les identités civiles soient publiques, permettez les recours et expliquez le traitement des comptes liés entre eux ou compromis.

Figez l’électorat admissible au début de chaque scrutin, en excluant les robots et l’auteur de la modification pour le scrutin concerné. Publiez la version de la proposition et, pour une modification de code, les commits exacts de la branche proposée et de la branche cible ; liez également le vote aux versions de la charte et de l’électorat. Des modifications substantielles invalident le scrutin et imposent d’en ouvrir un nouveau. Les changements du registre ne prennent effet qu’au cours d’une période de vote ultérieure. Les mentions « J’aime », les étoiles, les abonnés et les totaux d’émojis ne sont pas des bulletins de vote.

| Décision | Durée du vote | Participation | Nombre minimal de votes pour ou contre | Approbation parmi les votes pour ou contre | Délai de réflexion |
| --- | --- | --- | --- | --- | --- |
| Proposition ou modification ordinaire | 7 jours | Au moins 60 % des électeurs admissibles et au moins 5 participants | 5 | Au moins deux tiers | 24 heures |
| Charte, contrôle, accès sensibles pour la sécurité ou engagement majeur de ressources | 14 jours | Au moins 70 % des électeurs admissibles et au moins 10 participants | 10 | Au moins 80 % | 48 heures |

Arrondissez les nombres de participants requis à l’entier supérieur. Les abstentions comptent dans la participation, mais pas dans le taux d’approbation ni dans le nombre minimal de votes pour ou contre. Sans quorum, il n’y a pas d’approbation ; n’abaissez pas discrètement le seuil. Si la communauté est trop petite, restez dans une phase explicitement provisoire ou adoptez publiquement une autre charte avant de l’appliquer. Consignez les échéances en UTC, un décompte dont la responsabilité est clairement établie, les changements de vote, les conflits d’intérêts et le résultat. Une communauté doit préciser les procédures d’authentification des bulletins, de modification, de suppression, de clôture, de contestation et de recours avant de se fonder sur ce tableau.

## Examens, sécurité et automatisation future

Une modification approuvée reste soumise aux vérifications et à l’examen indépendant prévus par la charte adoptée. Les relecteurs chargés de la sécurité peuvent suspendre une modification pour un motif technique documenté, avec possibilité de recours ; il ne s’agit pas d’un droit personnel de veto sur les orientations. Les mesures de confinement d’urgence devraient être limitées, consignées et bornées dans le temps, avec examen par d’autres responsables et compte rendu public ultérieur protégeant les détails sensibles.

Si les participants construisent ultérieurement une automatisation, séparez les tests des contributions publiques du décompte des votes et de la fusion effectués avec des privilèges. Vérifiez la réussite effective, les versions exactes, la provenance fiable des vérifications et tous les examens requis immédiatement avant la fusion. Tenez compte des changements de la branche cible et exécutez en série les opérations susceptibles d’entrer en conflit. Gardez les identifiants à l’écart des modifications non fiables. Un travail d’intégration continue portant le même nom ou un commentaire affichant un décompte de votes ne constitue pas une autorisation fiable. L’activation d’une telle automatisation serait un projet futur nécessitant son propre examen, et non une fonction de cette publication.

## Langues et ressources

L’anglais constitue le texte de référence de cette première publication. Une communauté maintenue devrait publier sa propre politique linguistique et de traduction, préserver les opinions dissidentes significatives dans toutes les langues et rendre les modifications de la charte accessibles avant un vote. Aucun participant n’a l’obligation de donner de l’argent, des identifiants, des ressources de calcul ou du travail. Les financements et les affiliations doivent être déclarés et ne doivent pas acheter de voix supplémentaires. Les nouvelles obligations financières nécessitent l’acceptation explicite des personnes ou de l’entité qui les assument.

## Une charte prend vie grâce aux personnes

Ces mots acquièrent un sens concret lorsque des personnes les adoptent, assument la responsabilité de leurs pouvoirs et continuent de se rendre des comptes mutuellement. Créez un fork de cette première proposition, discutez de ce que votre communauté peut honnêtement soutenir et façonnez une charte que vous êtes prêts à respecter. Ce travail trouve sa place auprès de ceux qui veulent le faire avancer.

## Références GitHub

- [Assurer la continuité de la propriété](https://docs.github.com/en/organizations/managing-peoples-access-to-your-organization-with-roles/maintaining-ownership-continuity-for-your-organization)
- [Contribuer au moyen de forks](https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project)
- [Règles disponibles pour les ensembles de règles](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-rulesets/available-rules-for-rulesets)
