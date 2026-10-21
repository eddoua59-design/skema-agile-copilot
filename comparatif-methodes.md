---
titre: Comparatif Scrum / AgilePM-DSDM / PRINCE2 7 / PMI (CAPM)
type: synthèse (rédigée à partir des documents du dépôt)
langue: fr
fiabilite: synthese
---

# Comparatif Scrum / AgilePM (DSDM) / PRINCE2 7 / PMI (CAPM)

> **Synthèse rédigée à partir des documents de ce dépôt** (sources indiquées). Les rapprochements entre cadres sont des **correspondances approximatives, à titre indicatif** : chaque cadre a son propre vocabulaire et ses propres règles. Pour une réponse précise, retourner aux sources.

## 1. Vue d'ensemble

| | **Scrum** | **AgilePM (DSDM)** | **PRINCE2 7** | **PMI (CAPM / PMBOK 7)** |
|---|---|---|---|---|
| **Nature** | Cadre de travail léger, volontairement incomplet | Approche agile de management de **projet complet** (cycle de vie début → fin) | Méthode de management de projet : principes, pratiques, processus, personnes, contexte | Référentiel de connaissances et certification (CAPM) couvrant prédictif, agile, hybride, analyse d'affaires |
| **Qui en est propriétaire** | K. Schwaber et J. Sutherland (guide en CC BY-SA 4.0) | Agile Business Consortium ; certification APMG International | PeopleCert | Project Management Institute |
| **Cycle de vie** | Sprints successifs d'un mois ou moins | Pré-projet → Faisabilité → Fondations → Développement évolutif (Timeboxes) → Déploiement → Post-projet | Pré-projet puis séquences (initialisation, ultérieures, finale), au moins deux séquences | Selon l'approche choisie : prédictive (groupes de processus), itérative/incrémentale/agile, hybride |
| **Philosophie** | Empirisme (transparence, inspection, adaptation) et pensée Lean | Durée, coût, qualité **fixés** ; périmètre **variable** (MoSCoW) ; 8 principes | **Management par exception**, par séquences, focalisation produit ; tolérances | Choisir l'approche selon le contexte ; 8 domaines de performance |
| **Planification** | Product Backlog + Sprint Planning (objectif, quoi, comment) | Plan de livraison (≈ 6 sem.–6 mois) + Plan de Timebox (2-4 sem.) | Plan de projet, de séquence, d'équipe, d'exception ; planification basée sur le produit | Plan de management du projet (prédictif) ; vision / roadmap / release / itération (adaptatif) |
| **Périmètre et priorités** | Product Backlog ordonné par le Product Owner | Liste priorisée des exigences, **MoSCoW** ; Must = sous-ensemble minimum utilisable | Description de produit de projet, critères d'acceptation ; changements via la pratique **incidences** | WBS et référence de base (prédictif) ; backlog priorisé par valeur (MoSCoW, Kano, 100 points…) |
| **Réunion quotidienne** | **Daily Scrum** : 15 min | **Daily stand-up** : 3 questions, 2 min par personne + 2 min | — (rapports de contrôle et de synthèse) | Daily stand-up de 10-15 min (agile) |
| **Contrôle / gouvernance** | Événements d'inspection et d'adaptation ; Sprint Review | Rôles « niveau projet » ; management par exception ; produits « G » | Comité de pilotage, couche business, **tolérances** sur 7 cibles, rapports d'exception | Revues de performance ; EVM ; indicateurs agiles (vélocité, burndown) |
| **Qualité** | Definition of Done ; qualité jamais revue à la baisse pendant le Sprint | « Ne jamais compromettre la qualité » ; tests précoces et continus | Pratique **qualité** : planification, contrôle, assurance ; critères d'acceptation | Plan de gestion de la qualité ; outils (Ishikawa, Pareto, diagrammes de contrôle…) |
| **Certification** (voir les docs) | — | Fondation : 50 QCM, 40 min, 25 pts (50 %) ; Practitioner : cas d'étude, 80 questions | Foundation : 60 QCM, 1 h, 36 bonnes réponses (60 %) | CAPM : 150 questions (135 notées), 3 h |

Sources : [Guide Scrum](docs/scrum/guide-scrum-2020-fr.md) · [cours AgilePM](docs/agilepm/cours-skema/) · [guide PRINCE2 7](docs/prince2/guide-rapide-foundation/) · [modules CAPM](docs/capm/modules/) · [ECO](docs/capm/eco-examen-capm.md).

## 2. Rôles — rapprochements indicatifs

| Fonction | Scrum | AgilePM | PRINCE2 7 | PMI (CAPM) |
|---|---|---|---|---|
| Décideur / sponsor | (parties prenantes) | **Sponsor** (rôle le plus élevé, responsable du Business Case et du budget) | **Exécutif** (imputable en dernier ressort ; cas d'affaire) | **Sponsor** (relie l'équipe à la stratégie ; escalade) |
| Voix du métier / du produit | **Product Owner** (valeur du produit, Product Backlog) | **Visionnaire métier** (vision) ; **Ambassadeur métier** (détails au quotidien) | **Utilisateur principal** | **Product owner** (adaptatif) ; **Business Analyst** |
| Management de l'équipe | **Scrum Master** (leader au service ; pas un chef de projet) | **Chef de projet** (leadership agile de haut niveau) ; **Chef d'équipe** (SDT) | **Chef de projet** (management quotidien dans les tolérances) ; chefs d'équipe | **Chef de projet** / facilitateur d'équipe (Scrum Master, coach…) |
| Réalisation | **Developers** | Équipe de développement de la solution : développeur, testeur, BA, ambassadeur… | Chefs d'équipe et membres de l'équipe | Équipe pluridisciplinaire |
| Technique | — | Coordinateur technique ; conseiller technique | **Fournisseur principal** (intégrité technique, qualité des produits livrés) | — |
| Instance collégiale | — | Rôles de niveau projet | **Comité de pilotage de projet** (exécutif + utilisateur(s) + fournisseur(s)) | Comité de pilotage |
| Assurance / support | — | Coach DSDM ; animateur d'atelier | **Assurance projet** ; **support projet** | **PMO** (soutenant, conformité, directif) |

## 3. Artefacts / produits — rapprochements indicatifs

| Besoin | Scrum | AgilePM | PRINCE2 7 | PMI (CAPM) |
|---|---|---|---|---|
| Justification | — (l'Objectif de Produit est l'état futur visé, pas un business case) | **Business Case** | **Cas d'affaire** | **Business case** ; charte du projet |
| Liste de ce qu'il faut faire | **Product Backlog** | **Liste priorisée des exigences** | Description de produit de projet ; plans | Backlog (adaptatif) ; matrice de traçabilité des exigences (prédictif) |
| Plan court terme | **Sprint Backlog** | **Plan de Timebox** | **Plan de séquence** | Plan d'itération / de release |
| Plan global | (roadmap hors guide) | **Plan de livraison** | **Plan de projet** | Plan de management du projet |
| Résultat livré | **Increment** | **Solution en évolution** → incrément de solution → solution déployée | Produits du projet | Livrables ; incrément |
| Critère de fin | **Definition of Done** | Critères d'acceptation (Timebox) | Critères d'acceptation | Critères d'acceptation ; DoD |
| Bilan | Sprint Retrospective / Review | **Enregistrement de Timebox**, **rapport de performance du projet** | Rapport de fin de séquence, **rapport de leçons** | Leçons apprises ; clôture |
| Évaluation des bénéfices | (hors guide) | **Évaluation des bénéfices** | **Approche de gestion des bénéfices** | Plan de mesure des bénéfices (business case) |

## 4. Points d'attention de vocabulaire

- **« Séquence »** (PRINCE2 7, anglais *stage*) ≠ **Sprint** (Scrum) ≠ **Timebox** (DSDM) : ce sont des blocs de temps de nature différente (séquence = période de management avec décision de passage ; Sprint/Timebox = bloc de développement à durée fixe).
- **« Incidence »** (PRINCE2, *issue*) recouvre problème, préoccupation, requête de changement, hors-spécification… alors que le **« problème »** PMI (*issue*) est une condition actuelle pouvant affecter les objectifs.
- **« Business Case »** (AgilePM) = **« Cas d'affaire »** (traduction PRINCE2) = *business case* (PMI) ([cours AgilePM](docs/agilepm/cours-skema/05-produits.md)).
- **« Chef de projet »** : en Scrum il n'existe pas ; en AgilePM il délègue la planification détaillée à l'équipe ; en PRINCE2 il manage dans les tolérances du comité de pilotage.
- **Priorisation** : MoSCoW (AgilePM, PMI) ; en Scrum l'**ordre** du Product Backlog décidé par le Product Owner.
- **Gestion du changement de périmètre** : DSDM varie le périmètre (le Must est garanti) ; PRINCE2 passe par la pratique incidences et les tolérances ; PMI prédictif : demandes de changement approuvées sur les références de base.

## 5. Quel cadre choisir ? (d'après les cours)

- **AgilePM** : environnements **complexes** (projets et programmes, cycle de vie complet, dépendances inter-projets, culture projet « corporate ») ; Scrum, Kanban, Lean, XP sont des approches agiles plus légères, orientées développement ([cours AgilePM, diapos 9-11](docs/agilepm/cours-skema/01-introduction-agile-et-dsdm.md)).
- **PMI / CAPM** : choisir l'approche (prédictive, adaptative, hybride) selon le produit, le projet et l'organisation : degré d'innovation, certitude et stabilité des exigences, facilité de changement, possibilités de livraison, risque, sécurité, réglementation, parties prenantes, contraintes d'échéancier, financement, structure, culture… ([module 4](docs/capm/modules/module-04-approche-de-developpement-et-cycle-de-vie.md), [module 7](docs/capm/modules/module-07-approches-projet-adaptatives.md)).
- **PRINCE2 7** : s'adapte au contexte (organisation, contrat commercial, méthode de livraison — cycle en V, agile, hybride —, durabilité, échelle) et ne couvre **pas** les aspects spécialistes ni les techniques détaillées de gestion de projet ([notes de cours](docs/prince2/notes-cours-prince2.md), [guide](docs/prince2/guide-rapide-foundation/01-concepts-cles-et-benefices.md)).
- **Scrum** : décrit dans le [Guide Scrum](docs/scrum/guide-scrum-2020-fr.md) ; à utiliser « tel quel » (le cadre est immuable : n'en mettre en œuvre qu'une partie, « le résultat ne sera pas du Scrum »).
