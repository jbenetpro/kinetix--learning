# Module e-learning — OMS (Order Management System)
**Formation :** Responsable de Production Transport et Logistique (RPTL) — Bac+3
**Sous-titre du module :** Rôle, enjeux, limites, marché et omnicanalité de l'OMS
**Durée cible :** 20–30 min
**Public :** Apprenants RPTL ou métiers proches (responsable entrepôt, affréteur, approvisionneur, coordinateur transport/logistique) — non-IT
**Statut :** 🔴 À créer — v1 storyboard (sans support existant — à enrichir/corriger avec le support réel du formateur)

**Positionnement dans le curriculum :** Premier module "système" après le module socle *Comprendre les projets IT*. Il pose le rôle de l'OMS dans la chaîne logistique, sans entrer dans le paramétrage technique d'un outil précis ni citer d'éditeur. Les exemples sont contextualisés métier transport/logistique (profil RPTL).

---

## Objectifs pédagogiques
À l'issue du module, l'apprenant sera capable de :
1. Définir ce qu'est un OMS et expliquer son rôle dans la gestion des commandes.
2. Situer l'OMS par rapport aux autres systèmes (WMS, TMS, ERP) et ne pas confondre leurs périmètres.
3. Expliquer l'enjeu de l'omnicanalité et le rôle de l'OMS dans l'orchestration des commandes multi-canal.
4. Identifier les limites d'un OMS (ce qu'il ne fait pas) et les risques d'un mauvais paramétrage côté métier.
5. Avoir une vue générale du marché des solutions OMS, sans jugement de valeur ni citation d'éditeur.
6. Réappliquer le réflexe "vérifier avant d'agir" au contexte de la gestion de commandes.

---

## Plan du module (10 écrans + quiz)

| # | Écran | Durée estimée |
|---|-------|----------------|
| 1 | Accroche / mise en situation | 1-2 min |
| 2 | Objectifs du module | 1 min |
| 3 | Qu'est-ce qu'un OMS ? | 3 min |
| 4 | L'OMS dans le système d'information : ne pas confondre avec WMS/TMS/ERP | 3 min |
| 5 | Les enjeux métier de l'OMS | 3 min |
| 6 | Zoom sur l'omnicanalité | 4 min |
| 7 | Les limites de l'OMS | 3 min |
| 8 | Panorama du marché des OMS | 2 min |
| 9 | Vérifier avant d'agir — appliqué à la gestion de commandes | 2 min |
| 10 | Quiz de validation (10 questions, 80% requis) | 5 min |
| 11 | Synthèse et points clés à retenir | 1-2 min |

---

### Écran 1 — Accroche / mise en situation
**Contenu clé :**
- Mise en situation narrative : "Un client a commandé en ligne un article indiqué 'en stock'. Il se présente en magasin pour le récupérer : l'article n'est plus là. Le site web, le magasin et l'entrepôt ne 'parlaient' pas le même langage au même moment. Qui aurait dû faire le lien entre ces canaux ?"
- Teaser : ce module explique le rôle du système qui orchestre les commandes entre les canaux de vente et les lieux de stock — l'OMS.

**Visuel suggéré :** Schéma simple avec 3 canaux (site web, magasin, entrepôt) reliés par un point d'interrogation, qui se transforme en "OMS" à la fin de l'écran.

**Note formateur :** Ancrer l'intérêt — montrer que ce sujet touche directement la fiabilité du stock que le RPTL gère au quotidien.

**[Exemple réel à intégrer]** — un cas vécu de rupture ou d'incohérence de stock entre canaux (anonymisé).

---

### Écran 2 — Objectifs du module
**Contenu clé :** Reprendre les objectifs pédagogiques ci-dessus sous forme de bullet points visuels (icônes).

**Visuel suggéré :** 6 pictos (définition / positionnement / enjeux / omnicanalité / limites / vérifier avant d'agir) avec texte court sous chacun.

---

### Écran 3 — Qu'est-ce qu'un OMS ?
**Contenu clé :**
- Définition simple : un OMS (Order Management System) est le système qui **centralise et orchestre les commandes**, de leur création (quel que soit le canal de vente) jusqu'à leur affectation à une source de préparation/expédition.
- Il répond à 3 questions pour chaque commande : *Quoi ?* (quels articles), *Où la prendre ?* (quel entrepôt, quel magasin, quel fournisseur), *Comment la satisfaire ?* (quel mode de livraison ou de retrait).
- Il ne prépare pas physiquement la commande (ce rôle revient au WMS) et ne pilote pas le transport (rôle du TMS) : il **décide et orchestre**, d'autres systèmes **exécutent**.

**Visuel suggéré :** Schéma "commande entrante → OMS (orchestration) → sources d'exécution (entrepôt, magasin, fournisseur)".

**Note formateur :** Insister sur le mot "orchestration" : c'est la notion clé qui différencie l'OMS des systèmes d'exécution.

---

### Écran 4 — L'OMS dans le système d'information : ne pas confondre avec WMS/TMS/ERP
**Contenu clé :**
- Rappel rapide (sans détailler, ces systèmes ont leurs propres modules) :
  - **ERP** : gère les référentiels de gestion (articles, clients, comptabilité, stock théorique global).
  - **OMS** : orchestre les commandes entre canaux de vente et sources d'exécution.
  - **WMS** : exécute la préparation physique en entrepôt (réception, stockage, préparation, expédition).
  - **TMS** : organise et pilote le transport (choix transporteur, tournées, suivi).
- Message clé : l'OMS est un système de **décision et de coordination**, pas un système d'**exécution physique**. Un RPTL doit savoir reconnaître, face à un incident, si le problème vient de la décision (OMS) ou de l'exécution (WMS/TMS).

**Visuel suggéré :** Frise ou schéma en 4 blocs alignés sur le flux d'une commande (ERP référentiel → OMS décision → WMS/TMS exécution), avec une question illustrative à chaque transition.

**[Exemple réel à intégrer]** — un cas où une anomalie a été, à tort, imputée au WMS alors qu'elle venait d'une mauvaise orchestration OMS (ou l'inverse).

---

### Écran 5 — Les enjeux métier de l'OMS
**Contenu clé :**
- **Visibilité du stock disponible** : l'OMS doit connaître, en temps réel ou quasi réel, le stock disponible à la vente (ATS) sur chaque source, pour ne pas promettre une commande qu'on ne pourra pas honorer.
- **Règles d'allocation** : l'OMS applique des règles de choix de la source de préparation (proximité, niveau de stock, coût, délai) — ces règles sont souvent paramétrées avec les équipes métier.
- **Expérience client et fiabilité de la promesse** : une mauvaise orchestration se traduit directement par des ruptures annoncées à tort, des délais non tenus, des commandes annulées.
- Rôle du RPTL : remonter les contraintes réelles de production (capacité de préparation, horaires de coupure, contraintes de transport) qui doivent nourrir les règles d'allocation de l'OMS.

**Visuel suggéré :** Schéma "promesse client" avec les 3 piliers (visibilité stock / règles d'allocation / fiabilité) qui la soutiennent.

---

### Écran 6 — Zoom sur l'omnicanalité
**Contenu clé :**
- Définition : l'omnicanalité consiste à permettre au client d'acheter et de se faire livrer/retirer sa commande indifféremment de plusieurs canaux (site web, application, magasin), avec une expérience cohérente.
- Illustrer quelques scénarios logistiques concrets que l'OMS doit orchestrer, sans citer de dispositif commercial précis par nom d'éditeur :
  - Commande passée en ligne, retirée en point de vente.
  - Commande passée en ligne, préparée et expédiée depuis un point de vente plutôt que l'entrepôt central (pour réduire le délai).
  - Commande passée en magasin mais article non disponible sur place : expédiée depuis un autre site.
- Message clé pour le RPTL : chacun de ces scénarios change la source de préparation de la commande — et donc la charge et l'organisation du site qu'il pilote.

**Visuel suggéré :** Schéma avec 1 client au centre et plusieurs flèches vers différentes sources de préparation possibles, l'OMS représenté comme l'aiguilleur central.

**[Exemple réel à intégrer]** — un cas vécu où un site a dû absorber une charge de préparation inattendue liée à un scénario omnicanal (ex : retrait magasin, expédition depuis magasin).

---

### Écran 7 — Les limites de l'OMS
**Contenu clé :**
- L'OMS **décide** où et comment honorer une commande, mais il ne garantit pas que cette décision soit réalisable si les données qu'il utilise sont fausses ou en retard (ex : stock remonté avec latence, capacité de préparation non mise à jour).
- L'OMS ne gère pas : la préparation physique (WMS), le transport (TMS), les référentiels globaux de gestion (ERP).
- Risques fréquents à connaître côté métier : stock "disponible" dans l'OMS mais en réalité bloqué, réservé ou endommagé sur le terrain ; règles d'allocation non ajustées à une contrainte terrain réelle (ex : capacité de préparation saturée un jour donné).
- Message clé : un OMS n'est fiable que si les données et contraintes terrain qu'il utilise sont fiables et à jour — c'est une responsabilité partagée avec le métier.

**Visuel suggéré :** Schéma "OMS = cerveau, pas les yeux ni les mains" — illustrer la dépendance à des données fiables remontées du terrain.

---

### Écran 8 — Panorama du marché des OMS
**Contenu clé :**
- Expliquer le principe d'un « quadrant d'analystes » (Gartner Magic Quadrant, Forrester Wave...) : une représentation qui positionne les éditeurs d'un marché selon deux axes — généralement la solidité de l'offre actuelle et la vision stratégique — pour donner une photographie du marché à un instant donné. Ce n'est pas un classement de qualité absolu et il évolue chaque année.
- ⚠️ Point vérifié : Gartner ne publie pas de Magic Quadrant pour l'OMS à ce jour — ce marché (« Distributed Order Management ») y est couvert par un *Market Guide* (liste d'éditeurs reconnus, sans positionnement en quadrant) et par les avis clients Gartner Peer Insights.
- Référence retenue pour la représentation en quadrant : **Forrester Wave™: Order Management Systems, Q1 2025** (8 éditeurs évalués). Éditeurs reconnus **Leaders** sur cette édition : **Manhattan Associates**, **Kibo**, **Fluent Commerce**.
  - ⚠️ **À confirmer avant publication** : le détail complet (les 5 autres éditeurs évalués et leur positionnement Strong Performer/Contender) n'est accessible que dans le rapport Forrester payant — à vérifier/compléter avant mise en ligne du module.
- Autres éditeurs reconnus sur ce marché par Gartner (liste de référencement Peer Insights, sans positionnement qualité) : OneStock, IBM Sterling Order Management, Adobe Commerce, SAP Order Management Services, Salesforce Order Management, Blue Yonder, Microsoft Dynamics 365 Commerce, parmi une liste plus large.
- Message clé pour le RPTL : peu importe l'éditeur utilisé sur son site, le rôle et les enjeux de l'OMS restent les mêmes — c'est cette logique qu'il faut maîtriser, pas un outil en particulier. Ce panorama sert à donner un repère sur la diversité et la maturité du marché, pas à recommander un choix.

**Visuel suggéré :** Schéma quadrant 2x2 (axes « Offre actuelle » / « Vision stratégique »), les 3 Leaders Forrester positionnés dans le cadran supérieur droit, et un encart listant les autres éditeurs reconnus du marché sans positionnement.

**Sources à citer à l'écran (note formateur) :**
- Gartner Peer Insights — Distributed Order Management Systems : https://www.gartner.com/reviews/market/distributed-order-management-systems
- Forrester Wave™: Order Management Systems, Q1 2025 (rapport Forrester, accès payant pour le détail complet)

**Note formateur :** Ce panorama doit être mis à jour à chaque nouvelle édition du rapport (cadence annuelle environ) — prévoir une relecture de cet écran avant chaque republication du module.

---

### Écran 9 — Vérifier avant d'agir — appliqué à la gestion de commandes
**Contenu clé :**
- Rappel du réflexe transversal introduit au module 1.
- Application à l'OMS : avant de signaler une anomalie comme "bug système", vérifier d'abord si les données terrain remontées (stock réel, capacité de préparation, horaires de coupure) sont correctes et à jour.
- Court exercice/mise en situation : présenter une commande bloquée ou mal orientée par l'OMS, et demander à l'apprenant d'identifier la ou les causes probables côté données terrain avant d'escalader vers l'IT.

**Visuel suggéré :** Mini-cas interactif (QCM court ou glisser-déposer), distinct du quiz final.

**[Exemple réel à intégrer]** — un cas vécu où une vérification terrain simple a permis d'éviter une escalade inutile vers l'IT.

---

### Écran 10 — Quiz de validation (10 questions — 80% requis pour valider)
**Exemples de questions (à compléter jusqu'à 10) :**
1. (QCM) Quel est le rôle principal d'un OMS ?
2. (Vrai/Faux) L'OMS prépare physiquement les commandes en entrepôt.
3. (QCM) Associer chaque système (ERP/OMS/WMS/TMS) à son rôle principal.
4. (Mise en situation) Un client retire en magasin une commande passée en ligne : quel système a orchestré cette décision ?
5. (QCM) Qu'est-ce que l'omnicanalité ?
6. (Vrai/Faux) Un OMS est fiable même si le stock remonté par le terrain est obsolète.
7. (QCM) Citer un risque fréquent lié à une mauvaise donnée de stock disponible.
8. (Mise en situation) Une commande est bloquée par l'OMS de façon inattendue → quelle est la première chose à vérifier côté métier avant d'escalader ?
9. (QCM) Que gère un TMS, à la différence d'un OMS ?
10. (Vrai/Faux) Le rôle de l'OMS reste le même quel que soit l'éditeur de la solution utilisée.

**Note formateur :** Feedback explicatif après chaque réponse. Seuil de réussite : 8/10 bonnes réponses minimum.

---

### Écran 11 — Synthèse et points clés
**Contenu clé (rappel en 4 puces) :**
- L'OMS centralise et orchestre les commandes entre canaux de vente et sources d'exécution — il décide, il n'exécute pas.
- Il se distingue de l'ERP (référentiels), du WMS (exécution entrepôt) et du TMS (transport) : ne pas confondre leurs périmètres.
- L'omnicanalité multiplie les scénarios possibles de préparation d'une commande — un RPTL doit en comprendre l'impact sur son activité.
- L'OMS n'est fiable que si les données terrain qu'il utilise le sont — "vérifier avant d'agir" s'applique pleinement ici.

**Call-to-action :** Transition vers le prochain module système. "Après l'orchestration des commandes, découvrons comment elles sont exécutées en entrepôt avec le WMS."

**Visuel suggéré :** Carte mentale récapitulative, bouton "Module suivant", lien de téléchargement du glossaire global.

---

## Glossaire
Les termes de ce module ont été ajoutés au [glossaire global](00_Glossaire_global.md) de la formation.

## Points ouverts / à valider avec toi
1. **Support existant** : validé comme base du module. Les résumés des 7 présentations (cycle de vie, allocation, promesse, fulfilment, ATS/ATP, OMS vs ERP vs WMS, gestion des exceptions) restent à intégrer dans les écrans (ATP, promesse/fallback, fulfilment, exceptions, modèle à 3 couches).
2. Les **[Exemple réel à intégrer]** (écrans 1, 4, 6, 9) — cas concrets anonymisés à fournir, sans nom de client ni de projet.
3. Les 10 questions du quiz sont à finaliser (réponses/options complètes + feedbacks).
4. ~~ATS~~ : résolu — ATS = stock disponible à la vente (traduction anglaise), déjà défini au glossaire.
5. **Écran 8 (panorama marché)** : les 8 éditeurs évalués dans le Forrester Wave OMS Q1 2025 et leur positionnement sont à confirmer avant publication — voir note dans l'écran.
