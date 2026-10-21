# CLAUDE.md — Règles de travail du projet kinetix

## Le projet

Contenus d'une application de formation e-learning supply chain, destinée au parcours **Responsable de Production Transport et Logistique (RPTL)**, Bac+3.

- `00_Glossaire_global.md` : glossaire unique et cumulatif. Chaque module y ajoute ses termes, dans une section dédiée, par ordre alphabétique.
- `NN_<Titre_du_module>.md` : un storyboard par module, numéroté dans l'ordre du parcours.

Conventions de contenu :
- Rédaction en français.
- Exemples contextualisés métier transport/logistique, sans citer de logiciel, d'éditeur ni de nom de client.
- Quand un module introduit un nouveau terme, l'ajouter aussi au glossaire global.

## Travail multi-appareils

Le dépôt GitHub est la seule source de vérité. Le projet est travaillé depuis plusieurs appareils (Mac perso, PC, téléphone), avec ou sans Claude.

## Règle Git : `main` = version fiable, branche = version de travail

**On ne pousse jamais directement sur `main`.** Toute modification passe par une branche et une pull request, que Jerome valide et fusionne lui-même.

Déroulé à chaque session de travail :

1. **Partir de la dernière version** : `git fetch origin` puis créer la branche à partir de `origin/main` à jour.
2. **Créer une branche de travail** nommée `type/description-courte`, par exemple :
   - `module/02-gestion-des-stocks` (nouveau module)
   - `update/01-projets-it-quiz` (modification d'un module existant)
   - `glossaire/ajout-termes-transport`
   - `chore/...` (organisation du dépôt, outillage)
3. **Commits** : messages courts en français, qui disent ce qui change (« Ajoute l'écran 4 du module 02 »).
4. **Pousser la branche et ouvrir une pull request** vers `main`, avec un résumé des changements en français.
5. **Ne pas fusionner la PR soi-même** : c'est Jerome qui relit et fusionne.

Si une branche de travail est déjà en cours pour le même sujet (PR ouverte non fusionnée), continuer sur cette branche plutôt que d'en créer une nouvelle.

En travaillant sans Claude (copie locale sur un ordinateur) : `git pull` avant de commencer, et suivre la même règle de branche + PR.
