# Contribuer aux projets PRAGMA-e-TIC

Merci de l'intérêt porté à nos projets. Voici les règles communes à tous les repos de l'organisation. Chaque repo peut compléter ces règles par un `CONTRIBUTING.md` qui lui est propre.

## Avant d'ouvrir une PR

1. **Issue d'abord, code ensuite.** Sauf typo ou correctif trivial, ouvrez une issue ou commentez une issue existante avant de coder, pour qu'on s'aligne sur l'approche.
2. **Branche depuis `main`.** Nommage : `feature/<topic>` ou `fix/<topic>`.
3. **Conventional Commits** sur tous les commits :
   - `feat:` nouvelle fonctionnalité
   - `fix:` correction de bug
   - `docs:` documentation
   - `chore:` maintenance, dépendances
   - `refactor:` refactoring sans changement fonctionnel
   - `test:` tests uniquement
4. **Tests.** Toute nouvelle fonctionnalité ou tout correctif doit s'accompagner d'au moins un test.
5. **CI verte.** Lint + tests doivent passer avant la review.

## Process de revue

- Une review par un *owner* est requise pour merger sur `main`.
- Les commentaires de review s'adressent au code, pas à la personne (cf. code de conduite).
- Une PR « WIP » se met en *draft* — elle ne sera pas reviewée tant qu'elle reste en draft.

## Définition of done

- [ ] Code écrit, testé.
- [ ] Tests CI verts.
- [ ] Documentation à jour (README, docstrings, exemples).
- [ ] PR rebasée sur `main`.
- [ ] Reviewée et approuvée par un owner.
- [ ] Mergée puis branche supprimée.

## Stack et conventions

Voir [Dev Hub PRAGMA-e-TIC](https://github.com/pragma-e-tic/.github/blob/main/profile/README.md) pour la stack cible et les conventions globales (Python : Ruff + uv + pytest ; TypeScript : ESLint + Vitest + Playwright).

## Licence des contributions

En contribuant, vous acceptez que votre contribution soit publiée sous la licence du repo concerné.
