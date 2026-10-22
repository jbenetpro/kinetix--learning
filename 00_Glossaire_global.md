# Glossaire global — Formation Responsable de Production Transport et Logistique (RPTL)

> Glossaire unique et cumulatif, téléchargeable par l'apprenant. Chaque module alimente cette liste avec ses propres termes. Classement alphabétique.

---

## Module : Comprendre les projets IT

| Terme | Définition |
|---|---|
| **Agile** | Approche de gestion de projet itérative et incrémentale : le projet avance par cycles courts ("sprints"), avec livraison régulière de valeur et ajustement continu selon les retours. |
| **Backlog** | Liste priorisée des besoins/fonctionnalités à réaliser dans un projet mené en Agile. |
| **Cadrage** | Phase initiale d'un projet IT où l'on définit le périmètre, les objectifs, les contraintes et les grandes lignes de la solution. |
| **Hypercare** | Période de support renforcé juste après la mise en production d'une solution, pour accompagner les utilisateurs et corriger rapidement les anomalies critiques. |
| **Key user / référent métier** | Collaborateur terrain qui représente les utilisateurs finaux, teste la solution et valide qu'elle correspond au besoin réel. |
| **MOA (Maîtrise d'Ouvrage)** | Entité qui porte le besoin métier dans un projet IT : définit le "quoi" et le "pourquoi" de la solution attendue. |
| **MOE (Maîtrise d'Œuvre)** | Entité qui conçoit et réalise la solution technique répondant au besoin exprimé par la MOA : définit le "comment". |
| **Recette / UAT (User Acceptance Testing)** | Phase de test où les utilisateurs métier vérifient que la solution livrée répond effectivement à leurs besoins, avant la mise en production. |
| **Sponsor** | Porteur du projet au niveau direction ; débloque le budget et tranche les arbitrages majeurs. |
| **Sprint** | Cycle de travail court et borné dans le temps (souvent 1 à 4 semaines) en Agile, à l'issue duquel un incrément de solution utilisable est livré. |
| **Waterfall (cascade)** | Approche de gestion de projet séquentielle : chaque grande phase du projet (recueil des besoins, conception, réalisation, tests, déploiement) est terminée avant de démarrer la suivante. |

---

## Module : OMS

| Terme | Définition |
|---|---|
| **Allocation (règle d'allocation)** | Règle appliquée par l'OMS pour choisir la source (entrepôt, magasin, fournisseur) qui va honorer une commande, selon des critères comme la proximité, le niveau de stock, le coût ou le délai. |
| **ATP (Available to Promise / stock promis pour une date)** | Stock sur lequel l'entreprise peut s'engager auprès du client pour une date de livraison donnée : on part de l'ATS, on ajoute le stock futur (en transit, en approvisionnement) et on tient compte des délais d'approvisionnement, de préparation, d'expédition et de livraison. Permet de promettre une livraison même si l'ATS est à zéro. |
| **ATS (Available to Sell / stock disponible à la vente)** | Quantité de stock réellement disponible à la vente (« disponibilité de stock »), obtenue en partant du stock physique compté, moins les réservations en cours, moins les protections de stock (blocages, pièces de présentoir, stock tampon). C'est la traduction anglaise de « stock disponible à la vente ». |
| **Buffer (stock tampon)** | Quantité de stock volontairement retirée de la vente (ex. dernières pièces, réserve par canal) pour se protéger des écarts d'inventaire ou préserver certains canaux. Vient en déduction de l'ATS. |
| **Commande** | Reflet de ce que le client a payé et souhaite recevoir : articles, quantités, mode de livraison ou de retrait. Une commande peut donner naissance à un ou plusieurs fulfilments. |
| **Démarque inconnue** | Écart entre le stock théorique et le stock réellement compté, dont la cause n'est pas identifiée (erreurs d'inventaire, casse, vol, erreurs de réception). |
| **ERP (Enterprise Resource Planning)** | Système de gestion qui centralise les référentiels de l'entreprise (articles, clients, comptabilité, stock théorique global). |
| **Exception (gestion des exceptions)** | Événement ou situation qui sort du déroulé normal d'une commande (« happy path ») : erreur de stock, anomalie en préparation ou en sourcing, source indisponible sans repli. La gestion des exceptions définit les règles à suivre pour débloquer la commande (traitement automatique si la promesse client n'est pas impactée, sinon contact client et décision manuelle tracée). |
| **Fallback (repli)** | Gestion des priorités de sourcing : règle définie en amont qui indique quelle autre source utiliser, et selon quels critères, lorsque la source prioritaire n'est pas disponible. |
| **Fulfilment** | Reflet de la préparation et de la façon dont une commande sera traitée : 1 à N articles, un point d'origine, un point de destination (expédition depuis un entrepôt, retrait en magasin, expédition depuis un magasin...). Créé dans l'OMS après la commande. |
| **Happy path** | Déroulé normal d'un processus, sans incident ni écart. Tout ce qui en sort relève de la gestion des exceptions. |
| **Omnicanalité** | Capacité à permettre au client d'acheter et de se faire livrer ou retirer sa commande indifféremment via plusieurs canaux (site web, application, magasin), avec une expérience cohérente. |
| **OMS (Order Management System)** | Système qui centralise et orchestre les commandes, de leur création jusqu'à leur affectation à une source de préparation ou d'expédition. |
| **Orchestration (des commandes)** | Action de décider, pour chaque commande, quelle source va la préparer et comment elle sera livrée ou retirée, en coordonnant les différents canaux et sources d'exécution. |
| **Promesse client** | Engagement pris auprès du client sur la mise à disposition de la marchandise avec un délai de livraison. Elle combine la faisabilité stock, la route logistique, le délai et le coût. |
| **Quadrant d'analystes (Magic Quadrant / Wave)** | Représentation publiée par un cabinet d'analystes (Gartner, Forrester...) qui positionne les éditeurs d'un marché selon deux axes (ex. solidité de l'offre actuelle / vision stratégique), pour donner une photographie du marché à un instant donné. Évolue à chaque nouvelle édition. |
| **Sourcing** | Choix, pour une commande, du ou des lieux (entrepôt, magasin, fournisseur) qui vont la préparer, selon des critères comme le stock, le délai, le coût et la route logistique. |
| **Split de commande** | Répartition d'une commande sur plusieurs sources (ex. 2 articles + 2 articles) lorsqu'aucun lieu seul ne peut la servir en totalité. Génère plusieurs fulfilments. |

---

*(Les modules suivants ajouteront leurs propres sections ici : WMS, TMS, APS/ERP/WCS, IA, etc.)*
