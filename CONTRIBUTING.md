# Contribuer à Trouspy

## Flux Git

1. Créer ou sélectionner une issue dans le dépôt concerné et la relier au Project commun,
   avec un résultat et un critère d'acceptation.
2. Créer une branche courte : `feat/123-description`, `fix/123-description` ou
   `docs/123-description`.
3. Faire des commits petits et compréhensibles.
4. Ouvrir une pull request liée à l'issue et compléter la checklist.
5. Obtenir au moins une revue avant fusion, sauf incident urgent documenté.
6. Utiliser une fusion squash et supprimer la branche après fusion.

Après l'initialisation, passer par une pull request pour modifier `main`. Sur GitHub Free,
les protections de branches et revues obligatoires ne sont pas disponibles pour les dépôts
privés de l'organisation : cette pratique repose sur l'accord de l'équipe.

## Avant une pull request

- Les tests et vérifications pertinentes passent localement.
- Aucun secret ni donnée personnelle réelle n'est présent.
- Le changement est documenté au niveau utile.
- Les critères d'acceptation sont vérifiables par une autre personne.

## Commits

Utiliser une intention claire, par exemple :

```text
feat(mobile): ajouter l'écran d'accueil
fix(web): corriger le menu sur petit écran
docs(project): préciser la règle de décision
```

## Changements structurants

Toute décision difficile à inverser — architecture, fournisseur, modèle de données, collecte
de données personnelles — nécessite une fiche dans `docs/decisions/`.
