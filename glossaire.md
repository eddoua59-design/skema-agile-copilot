---
titre: Glossaire FR/EN — Scrum, AgilePM/DSDM, PRINCE2 7, PMI/CAPM, performance
type: synthèse (rédigée à partir des documents du dépôt)
langue: fr
fiabilite: synthese
---

# Glossaire FR/EN — Scrum, AgilePM/DSDM, PRINCE2 7, PMI/CAPM, performance

> **Synthèse rédigée à partir des documents de ce dépôt** : chaque entrée renvoie à sa source. En cas de doute, la source (surtout si `fiabilite: officiel`) fait foi. Les termes sont groupés par cadre ; le même mot peut avoir un sens différent d'un cadre à l'autre (voir [comparatif-methodes.md](comparatif-methodes.md)).

## 1. Scrum (Guide Scrum 2020)

Source : [guide-scrum-2020-fr.md](docs/scrum/guide-scrum-2020-fr.md) (EN : [scrum-guide-2020-en.md](docs/scrum/scrum-guide-2020-en.md)). Les termes Scrum, Developers, Product Owner, Scrum Master, Sprint, Sprint Planning, Daily Scrum, Sprint Review, Sprint Retrospective, Increment, Definition of Done ne sont pas traduits.

| Terme | Définition (d'après le guide) |
|---|---|
| **Scrum** | Cadre de travail léger qui aide personnes, équipes et organisations à générer de la valeur grâce à des solutions adaptatives pour des problèmes complexes ; fondé sur l'**empirisme** et la **pensée Lean** ; volontairement incomplet. |
| **Piliers empiriques** | **Transparence, inspection, adaptation.** |
| **Valeurs Scrum** | Engagement, focus, ouverture, respect, courage. |
| **Scrum Team** | Unité fondamentale : un Scrum Master, un Product Owner et des Developers ; une seule équipe (pas d'équipe dans l'équipe), pluridisciplinaire, autogérée, **dix personnes au plus** en général. |
| **Developers** | Membres de la Scrum Team qui s'engagent à créer tout ou partie utile d'un Increment à chaque Sprint (Sprint Backlog, Definition of Done, adaptation quotidienne du plan, responsabilité mutuelle). |
| **Product Owner** | Redevable de maximiser la valeur du produit et de la gestion du Product Backlog ; **une personne, pas un comité**. |
| **Scrum Master** | Redevable de la mise en place de Scrum et de l'efficacité de la Scrum Team ; « véritable leader au service » de l'équipe et de l'organisation. |
| **Sprint** | Événement-conteneur de **durée fixe d'un mois ou moins** ; un nouveau Sprint commence dès la fin du précédent ; peut être annulé uniquement par le Product Owner. |
| **Sprint Planning** | Lance le Sprint ; ≤ 8 h pour un Sprint d'un mois ; trois thèmes : **pourquoi** (Objectif de Sprint), **quoi** (éléments sélectionnés), **comment** (plan). |
| **Daily Scrum** | 15 minutes, chaque jour ouvré, pour les Developers : inspecter la progression vers l'Objectif de Sprint. |
| **Sprint Review** | ≤ 4 h (Sprint d'un mois) : inspecter le résultat du Sprint avec les parties prenantes ; avant-dernier événement. |
| **Sprint Retrospective** | ≤ 3 h (Sprint d'un mois) : améliorer qualité et efficacité ; conclut le Sprint. |
| **Product Backlog** | Liste ordonnée et émergente de ce qui est nécessaire pour améliorer le produit ; engagement : **Objectif de Produit**. |
| **Sprint Backlog** | Objectif de Sprint (pourquoi) + éléments du Product Backlog choisis (quoi) + plan d'action (comment) ; engagement : **Objectif de Sprint**. |
| **Increment** | Étape concrète vers l'Objectif de Produit, utilisable ; engagement : **Definition of Done**. |
| **Definition of Done** | Description formelle de l'état de l'Increment lorsqu'il satisfait les mesures de qualité requises. |
| **Affinement du Product Backlog** | Activité continue de décomposition et de précision des éléments (description, ordre, taille). |

## 2. AgilePM / DSDM

Sources : [cours SKEMA AgilePM](docs/agilepm/cours-skema/), [exercices](docs/agilepm/exercices-agilepm.md), [examen blanc](docs/agilepm/examen-blanc-agilepm/).

| Terme (EN) | Définition (d'après le cours) |
|---|---|
| **DSDM** (Dynamic Systems Development Method) | Première approche agile de management de projet (1995) ; propriété de l'**Agile Business Consortium (ABC)**. **AgilePM** = nom commercial de la certification DSDM organisée par **APMG International**. |
| **Philosophie** | « Une plus grande valeur ajoutée apparaît lorsque les projets suivent des objectifs précis, sont jalonnés de livraisons fréquentes et impliquent la collaboration de personnes motivées et autonomes. » « Maison » DSDM : **bon sens et pragmatisme**, 4 piliers : **Processus, Personnes, Produits, Pratiques**. |
| **8 principes** | Se focaliser sur les besoins de l'entreprise · Livrer dans les délais · Collaborer · Ne jamais compromettre la qualité · Construire par incréments sur des fondations solides · Développer itérativement · Communiquer de façon claire et continue · Démontrer la maîtrise. |
| **Variables projet** | Approche traditionnelle : périmètre fixé, durée/coût variables. **DSDM : durée, coût et qualité fixés, périmètre variable.** |
| **Facteurs clés de succès** (*Instrumental Success Factors*, ISF) | Adoption de l'approche DSDM ; équipe efficace de développement de la solution (autonomie, stabilité, compétences, taille) ; engagement actif et continu du métier ; développement itératif, tests intégrés et livraison incrémentale ; transparence. |
| **PAQ** (*Project Approach Questionnaire*) | Questionnaire utilisé dès la Faisabilité, revu à la fin de Fondations : niveau d'atteinte des facteurs clés de succès, niveau de risque, actions à mener. |
| **Phases** | Pré-projet → Faisabilité → Fondations → Développement évolutif → Déploiement → Post-projet. |
| **Solution en évolution** | Produit clé : ensemble des livrables intermédiaires ; **incrément de solution** (version intermédiaire) et **solution déployée** (livrable final). |
| **MoSCoW** | **M**ust (doit avoir : constitue le MUST = sous-ensemble minimum utilisable) · **S**hould · **C**ould · **W**on't have this time. |
| **Timebox** | Durée généralement 2 à 4 semaines ; **format DSDM** : Lancement → Investigation (≈10-20 %) → Perfectionnement (≈60-80 %) → Consolidation (≈10-20 %) → Clôture ; **format libre** : Lancement → Développement itératif → Clôture. |
| **Daily stand-up** | Réunion quotidienne debout de la Timebox : 3 questions (fait / à faire / blocages) ; conseil : 2 minutes par personne + 2 minutes. |
| **Rôles niveau projet** | Sponsor, Visionnaire métier, Chef de projet, Coordinateur technique. |
| **SDT** (*Solution Development Team*) | Ambassadeur métier, Business analyst, Chef d'équipe, Développeur de solution, Testeur de solution. |
| **Rôles de soutien** | Conseiller métier, Conseiller technique, Animateur d'atelier, Coach DSDM. |
| **Produits** | Cadre de référence · Business Case · Liste priorisée des exigences (LPE / PRL) · Définition de l'architecture de la solution (DAS) · Approche de développement · Plan de livraison · Approche de management (MAD) · Évaluation de faisabilité · Résumé de Fondations · Solution en évolution · Plan de Timebox · Enregistrement de Timebox · Rapport de performance du projet · Évaluation des bénéfices. |
| **Produits « G »** | Produits de **gouvernance** (marqués d'un « G ») : appuient les décisions aux passages clés — cadre de référence, évaluation de faisabilité, résumé de Fondations, enregistrement de Timebox, rapport de performance du projet, évaluation des bénéfices. |
| **Plan de livraison / Plan de Timebox** | Horizons de planification : plan de livraison ≈ 6 semaines à 6 mois ; plan de Timebox 2-4 semaines (mis à jour au stand-up). |
| **6 concepts de tests** | Intégrés, collaboratifs, répétables, priorisés, indépendants, pilotés par les tests (TDD). 3 catégories : **positifs**, **négatifs**, **de sollicitation**. |
| **Pratiques clés** | Priorisation MoSCoW, Timeboxing, ateliers animés (*facilitated workshops*), modélisation, développement itératif (réflexion, action, conversation). |

## 3. PRINCE2 7

Sources : [guide rapide Foundation](docs/prince2/guide-rapide-foundation/), [notes de cours](docs/prince2/notes-cours-prince2.md), [échantillon d'examen](docs/prince2/examen-blanc-prince2-7/).

| Terme | Définition (d'après le guide) |
|---|---|
| **Projet** | Organisation temporaire créée pour livrer un ou plusieurs produits d'entreprise conformément à un cas d'affaire convenu. Caractéristiques : changement, temporaire, transversal, unique, incertitude. |
| **5 éléments intégrés** | **Personnes** (au centre), **contexte du projet**, **principes**, **pratiques**, **processus**. |
| **7 principes** | Justification continue pour l'entreprise · Tirer les leçons de l'expérience · Rôles, responsabilités et relations définis · Management par séquences · Management par exception · Focalisation produit · Adapter en fonction du projet. |
| **7 pratiques** | Cas d'affaire · Organisation · Plans · Qualité · Risque · Incidences · Progression. |
| **7 processus** | Élaborer le projet · Diriger le projet · Initialiser le projet · Contrôler une séquence · Gérer la livraison des produits · Gérer une limite de séquence · Clore le projet. |
| **7 aspects de performance / cibles** | Bénéfices, coûts, temps, qualité, périmètre, durabilité, risque ; des **tolérances** sont fixées sur chacun. |
| **Cas d'affaire** (*business case*) | Documente la justification pour l'entreprise (bénéfices escomptés vs coûts, risques) ; le projet doit rester souhaitable, viable et réalisable. |
| **Livrable / aptitude / résultat / bénéfice / contre-bénéfice / objectif business** | Livrables → (intégrés en) aptitudes → résultats → bénéfices (ou contre-bénéfices) → objectifs business. |
| **Séquence** (*stage*) | Période de management : séquence d'initialisation, séquences ultérieures, séquence finale ; il y a au moins deux séquences. |
| **Exécutif** | Point d'imputabilité unique du projet, responsable du cas d'affaire ; un seul exécutif, rôle non combinable avec celui de chef de projet. |
| **Comité de pilotage de projet** | Exécutif + utilisateur(s) principal(aux) + fournisseur(s) principal(aux) ; imputable de la réussite du projet dans les tolérances fixées par la couche business. |
| **Chef de projet / chef d'équipe** | Management quotidien dans les tolérances du comité de pilotage / livraison des lots de travaux dans les tolérances du chef de projet. |
| **Assurance projet / support projet** | Assurance indépendante (responsabilité des membres du comité de pilotage) ; support administratif (à séparer de l'assurance). |
| **Couche business (commanditaire)** | Fournit le mandat de projet, désigne l'exécutif, fixe les tolérances du projet. |
| **Plans** | Plan de projet, plan de séquence, plan d'équipe (optionnel), plan d'exception ; planification basée sur le produit (description de produit de projet, structure de décomposition du produit, descriptions de produit, diagramme de flux des produits). |
| **Qualité** | Planification, contrôle et assurance qualité ; exigences qualité de l'utilisateur, critères d'acceptation, spécifications qualité. |
| **Risque** | Événement(s) incertain(s) affectant les objectifs (menace ou opportunité) ; technique : identifier, évaluer, planifier, implémenter, communiquer ; propriétaire du risque / propriétaire des mesures liées au risque. |
| **Incidence** | Événement pertinent nécessitant l'attention du management : problème, préoccupation, événement extérieur, opportunité commerciale, requête de changement, hors-spécification ; technique : saisir, évaluer, recommander, décider, implémenter. |
| **Tolérance / exception** | Tolérance = limite de l'autorité déléguée ; **exception** = prévision d'un écart dépassant les tolérances convenues → rapport d'exception, éventuellement plan d'exception. |
| **Management par exception** | Les niveaux supérieurs ne sont sollicités qu'en cas de dépassement prévu des tolérances. |
| **Base de référence / budget de changement** | Versions approuvées des produits soumis au contrôle des changements / budget prévu pour couvrir les changements. |
| **Documents clés** | Mandat de projet · exposé du projet · documentation d'initialisation de projet (DIP) · journal de projet · journal des leçons · rapport de synthèse · rapport d'exception · rapport de fin de séquence. |

## 4. PMI / CAPM (PMBOK 7, Agile Practice Guide, Business Analysis)

Sources : [ECO CAPM](docs/capm/eco-examen-capm.md), [modules 1 à 10](docs/capm/modules/).

| Terme | Définition (d'après les modules) |
|---|---|
| **CAPM** | Certified Associate in Project Management (PMI) : examen de 150 questions dont 135 notées, 3 h ; domaines : fondamentaux 36 %, prédictif 17 %, agile 20 %, analyse d'affaires 27 %. |
| **Projet / programme / portefeuille** | Initiative temporaire pour un produit/service/résultat unique ; groupe de projets connexes gérés de manière coordonnée ; ensemble de projets, programmes et opérations gérés pour des objectifs stratégiques. |
| **8 domaines de performance** | Parties prenantes, équipe, approche de développement et cycle de vie, planification, travail du projet, livraison, mesure, incertitude. |
| **Talent Triangle** | Ways of Working, Power Skills, Business Acumen. |
| **WBS** (*Work Breakdown Structure*) | Décomposition hiérarchique du périmètre ; **lot de travaux** = niveau le plus bas ; **règle des 100 %**. |
| **Chemin critique** | Séquence d'activités la plus longue ; détermine la durée minimale du projet ; pas de marge. |
| **PERT / estimation à 3 points** | dE = (O + 4·PP + P)/6 (bêta/PERT) ou (O + PP + P)/3 (triangulaire). |
| **Valeur acquise (EVM)** | PV (valeur planifiée), EV (valeur acquise), AC (coût réel) ; **CV = EV − AC**, **SV = EV − PV**, **CPI = EV/AC**, **SPI = EV/PV** ; **EAC = AC + ETC** ou BAC/CPI ; **VAC = BAC − EAC**. |
| **Réponses aux risques** | Menaces : escalader, éviter, transférer, atténuer, accepter. Opportunités : escalader, exploiter, partager, améliorer, accepter. |
| **Types de contrat** | Prix forfaitaire (risque sur le vendeur), frais remboursables (risque sur l'acheteur), régie ; RFI, RFQ, RFP. |
| **Structures organisationnelles** | Organique, fonctionnelle, multidivisionnelle, matricielle (faible / équilibrée / solide), orientée projet, virtuelle, hybride ; **PMO** (soutenant, conformité, directif). |
| **Approches de développement** | Prédictive (« waterfall »), itérative, incrémentale, agile, hybride. |
| **Manifeste Agile** | 4 valeurs et 12 principes (2001). |
| **Backlog / user story / epic** | Liste priorisée par valeur ; récit « En tant que… je souhaite… afin de… » (critères **INVEST**) ; epic = grande fonctionnalité à décomposer. |
| **DoR / DoD** | Definition of Ready (critères d'entrée en itération) / Definition of Done (critères de livraison de l'incrément). |
| **MVP / MBI** | Minimum Viable Product (investissement pour apprendre) / Minimum Business Increment (investissement pour réaliser de la valeur). |
| **Story points / vélocité** | Estimation relative de complexité (planning poker) ; vélocité = points terminés par itération (moyenne sur ~3 itérations ; ne sert pas à comparer des équipes). |
| **Burndown / burnup** | Travail restant dans le temps / travail accompli vers la livraison. |
| **Lean / Kanban** | Réduction des gaspillages et amélioration continue / tableau de flux avec limites d'encours (WIP) et système de traction. |
| **BA** (*Business Analysis*) | Ensemble d'activités soutenant des solutions alignées sur les objectifs de l'entreprise ; élicitation, analyse, traçabilité des exigences ; **business case**. |
| **Matrice de traçabilité des exigences** | Suit les exigences de leur origine jusqu'aux livrables (approche prédictive). |
| **Incertitude (ACV)** | Ambiguïté, complexité, volatilité ; stratégies : élaboration progressive, expérimentation, prototypes, approche itérative, impliquer les parties prenantes, analyse d'alternatives, réserves. |

## 5. Performance, indicateurs et tableaux de bord (cours SKEMA)

Sources : [performance et tableaux de bord](docs/skema-cours/performance-tableaux-de-bord/), [lectures 1 à 4](docs/skema-cours/).

| Terme | Définition (d'après les cours) |
|---|---|
| **Performance** | « Est performance tout ce qui, et seulement ce qui, contribue à atteindre les objectifs stratégiques » (Lorino) ; combinaison d'**efficience, efficacité et compétence** (« triangle d'or »). |
| **Efficacité / efficience** | Atteinte de l'objectif / obtention d'un extrant avec un minimum d'intrants ; pertinence, cohérence, réalité, utilité complètent l'analyse. |
| **KPI** (*Key Performance Indicator*) | Mesure d'un aspect critique de la performance globale ; **doit induire l'action** ; types : alerte, équilibre, anticipation. |
| **Indicateur SMART** | Spécifique, Mesurable, Accepté, Réaliste, Temporel (cours Vaesken) ; en anglais *Specific, Measurable, Assignable, Realistic, Time-related* (Doran, lecture 4). |
| **Tableau de bord vs reporting** | Tableau de bord = pendant l'action (pilotage) ; reporting = après l'action, pour la hiérarchie. |
| **Courbe en S / EVM** | Courbes VP (valeur prévue), CR (coût réel), VA (valeur acquise) ; écarts en production, en coût, en délai. |
| **MLP** (*Multi-Level Perspective*) | Performance à quatre niveaux : **project, asset, network, system**. |
| **Projectification / programmification** | Organisation de l'activité en projets temporaires / en programmes et portefeuilles de projets. |
| **Function / outcome / objective / goal** | Fonction du système → outcomes ; objectif = outcome préféré atteignable dans une période donnée ; but (*goal*) = outcome préféré atteignable sur une période plus longue (Ackoff). |
