# `.github` — défauts de l'organisation PRAGMA-e-TIC

Ce repo héberge les **défauts communautaires** appliqués à toute l'organisation [`pragma-e-tic`](https://github.com/pragma-e-tic) sur GitHub, ainsi que des **workflows réutilisables** par les autres repos.

## Contenu

```
profile/README.md                    # Profil public de l'organisation
.github/
├── SECURITY.md                      # Politique de sécurité par défaut
├── CODE_OF_CONDUCT.md               # Code de conduite
├── CONTRIBUTING.md                  # Guide de contribution
├── PULL_REQUEST_TEMPLATE.md         # Template PR
├── ISSUE_TEMPLATE/
│   ├── bug_report.yml
│   ├── feature_request.yml
│   └── config.yml
└── workflows/
    ├── reusable-ci-python.yml       # CI Python (lint + tests)
    ├── reusable-ci-node.yml         # CI Node/Next.js
    └── reusable-deploy-ovh.yml      # Déploiement SSH sur VPS OVH
```

## Comment ça marche

Pour les fichiers communautaires (SECURITY, CODE_OF_CONDUCT, etc.) : si un repo de l'organisation ne définit pas son propre fichier, GitHub utilise automatiquement celui présent ici.

Pour les workflows réutilisables : tout repo de l'org peut les invoquer via `uses: pragma-e-tic/.github/.github/workflows/<nom>.yml@main`. Voir les commentaires en tête de chaque fichier pour les exemples d'utilisation.

## Mise à jour

Toute modification passe par une PR sur `main`. Comme ces fichiers s'appliquent à toute l'organisation, la review est attendue plus stricte qu'ailleurs.

## Licence

Documentation et templates sous [licence MIT](LICENSE). Les workflows sont sous la même licence et peuvent être réutilisés en référence à ce repo.
