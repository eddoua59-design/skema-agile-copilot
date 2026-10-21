# SKEMA Agile — base de connaissances pour GitHub Copilot

Les supports de cours des dossiers **SKEMA / AGILE**, **SKEMA / COURS** et **PMI-SKEMA** (Scrum, AgilePM/DSDM, PRINCE2 7, CAPM/PMI, performance et tableaux de bord, analyse financière, géopolitique, leadership et changement, mégaprojets), **convertis en Markdown** pour que GitHub Copilot (et toi) puissiez les lire, les chercher et s'en servir : réviser les certifications, poser des questions de méthode, préparer des livrables.

> ⚠️ **Usage personnel d'étude.** Il contient des documents protégés (PeopleCert, APMG/Agile Business Consortium, PMI, SKEMA) : voir « Droits et provenance ». Vérifie la politique de ton entreprise avant de copier ces contenus sur un poste ou un dépôt professionnel.

## Ce que contient le dépôt

| Thème | Dossier | Contenu |
|---|---|---|
| **Scrum** | [`docs/scrum/`](docs/scrum/) | Guide Scrum 2020 en français et en anglais (CC BY-SA 4.0) |
| **AgilePM / DSDM** | [`docs/agilepm/`](docs/agilepm/) | Cours SKEMA (84 diapos), cahier d'exercices, examen blanc de 50 questions avec réponses |
| **PRINCE2 7** | [`docs/prince2/`](docs/prince2/) | Guide de référence rapide Foundation, échantillon d'examen (60 questions, réponses et justifications), notes de cours et notes personnelles |
| **CAPM / PMI** | [`docs/capm/`](docs/capm/) | Exam Content Outline (PMI), 10 modules de préparation, quiz SKEMA (39 QCM) |
| **Cours SKEMA** | [`docs/skema-cours/`](docs/skema-cours/) | Performance de projet et tableaux de bord (130 diapos), lectures 1 à 4 (performance multi-niveaux, opérations, projets), cas d'analyse financière (Minerve, Politics), géopolitique (2 cours), consigne et modèles d'outils PMO, leadership et changement, notes de séances |
| **PMI-SKEMA** | [`docs/pmi-skema/`](docs/pmi-skema/) | Mémoire de mastère « L'agilité dans les mégaprojets » (88 pages, 8 entretiens) et article de Bass sur le leadership transformationnel |
| **Ressources** | [`docs/ressources/`](docs/ressources/) | Lien vers les templates de l'enseignant |
| **Synthèses** | [`INDEX.md`](INDEX.md), [`glossaire.md`](glossaire.md), [`comparatif-methodes.md`](comparatif-methodes.md) | Carte du dépôt, glossaire FR/EN, comparatif des méthodes (rédigés à partir des sources) |

Les 22 documents du dossier `AGILE` (14 PDF, 4 PowerPoint, 3 Word, 1 Pages) sont tous couverts, ainsi que les documents utiles des dossiers `COURS` et `PMI-SKEMA` (les doublons avec `AGILE` ne sont pas repris) — voir les tables de correspondance dans [`INDEX.md`](INDEX.md).

## Utiliser le dépôt avec GitHub Copilot

Le dépôt contient [`.github/copilot-instructions.md`](.github/copilot-instructions.md) (consignes toujours actives : répondre en français, chercher d'abord dans `docs/`, citer les sources, hiérarchie de fiabilité) et [`AGENTS.md`](AGENTS.md) (mêmes règles pour les agents).

**1. Dans ton éditeur (VS Code, Visual Studio, JetBrains)** — le plus simple
1. Récupère le dépôt : `git clone https://github.com/eddoua59-design/skema-agile-copilot.git` ou *Code → Download ZIP* sur la page GitHub, puis ouvre le dossier dans ton éditeur.
2. Ouvre **Copilot Chat** : les consignes de `.github/copilot-instructions.md` sont chargées automatiquement.
3. Pose tes questions en laissant Copilot chercher dans le dossier (`@workspace` / `#codebase` dans VS Code) ou en joignant un fichier (`#file:docs/prince2/guide-rapide-foundation/06-processus.md`).

**2. Avec un Space Copilot (github.com)** — pour avoir la base de connaissances dans le chat web
- Crée un *Space* (github.com/copilot/spaces) et ajoute comme sources **le dépôt** (si ton compte de travail y a accès) **ou les fichiers** `docs/**`, `glossaire.md`, `comparatif-methodes.md` (téléversement). Si le Space propose un champ d'instructions, colle-y le contenu de `.github/copilot-instructions.md`.

**3. Copilot CLI / agent** — lit `AGENTS.md` et `.github/copilot-instructions.md` à la racine du dépôt.

**Exemples de demandes**
- « Quelles sont les différences entre un Sprint Planning, un plan de Timebox et un plan de séquence PRINCE2 ? » (s'appuie sur le comparatif)
- « Interroge-moi sur les 7 principes de PRINCE2 : une question à la fois, corrige avec la justification. »
- « Rédige 5 user stories INVEST pour … et propose une Definition of Done. »
- « Prépare un tableau de bord de 6 KPI SMART pour un projet de … en suivant le cours de performance. »
- « Résume le domaine III de l'ECO CAPM et les modules correspondants. »

## Structure

```
.
├── README.md · INDEX.md · glossaire.md · comparatif-methodes.md
├── AGENTS.md
├── .github/copilot-instructions.md
└── docs/
    ├── scrum/                      guide Scrum 2020 (FR, EN)
    ├── agilepm/                    cours-skema/ (6 fichiers) · exercices-agilepm.md · examen-blanc-agilepm/
    ├── prince2/                    guide-rapide-foundation/ (6) · examen-blanc-prince2-7/ (6) · notes-cours-prince2.md · notes-personnelles-prince2.md
    ├── capm/                       eco-examen-capm.md · modules/ (11 fichiers) · quiz-skema-capm.md
    ├── skema-cours/                lectures 1-4 · performance-tableaux-de-bord/ (4) · analyse-financiere/ (4) · geopolitique/ (4) · pmo-tdb-perf/ (2) · leadership-changement/ (1) · notes-personnelles-seances.md
    ├── pmi-skema/                  these-agilite-megaprojets/ (14) · bass-transactional-to-transformational-leadership.md
    └── ressources/                 templates-liens.md
```

**Conventions**
- Chaque fichier commence par un front matter : `titre`, `source_fichier` (document d'origine), `type`, `langue`, `fiabilite`, `sujets`.
- `fiabilite` : **`officiel`** (documents des éditeurs) › **`support-de-cours`** (diapos et cas SKEMA) › **`publication`** (article scientifique) › **`travail-etudiant`** (mémoire, devoirs rendus : non officiel) › **`notes`** › **`notes-non-verifiees`** / **`quiz-non-verifie`** ; `synthese` pour les fichiers rédigés ici.
- Les marqueurs HTML `<!-- p.N -->` (page du PDF) et `<!-- diapo N -->` permettent de citer l'origine.
- Fichiers de taille raisonnable (quelques Ko à ~35 Ko) pour une bonne recherche sémantique.

## Droits et provenance

| Document(s) | Titulaire / licence | Remarque |
|---|---|---|
| Guide Scrum 2020 (FR, EN) | © 2020 Ken Schwaber & Jeff Sutherland — **CC BY-SA 4.0** | Redistribuable avec attribution et même licence |
| PRINCE2 7 Foundation : guide de référence rapide, échantillon d'examen 1, réponses et justifications | © PeopleCert International Ltd — « Official Training Materials » | **Non redistribuable** — usage personnel |
| AgilePM Foundation : sample paper et clé de réponses | © The APM Group Ltd 2018 ; AgilePM® : Agile Business Consortium | **Non redistribuable** — usage personnel |
| AgilePM : cours (v2019 S1.1) et cahier d'exercices | © Dynamic Systems Development Method Ltd ; traduction Learning Street ; SKEMA | Support de cours |
| CAPM : Exam Content Outline | © 2023 Project Management Institute, Inc. | **Non redistribuable** |
| CAPM : modules de préparation 1 à 10 | Support « Préparation à l'examen CAPM » (Doppelfeld – Mehring), contenus alignés sur le PMI | Support de cours |
| CAPM : quiz SKEMA | Quiz SKEMA (clé non vérifiée) | Support de cours |
| Performance et tableaux de bord | Philippe Vaesken (SKEMA) | Support de cours |
| Lectures 1 à 4 | Cours SKEMA (auteur non indiqué) ; références académiques citées conservées | Support de cours |
| Notes de cours PRINCE2 | Notes d'un participant (non officielles) | — |
| Notes personnelles PRINCE2 | Notes personnelles + comptes rendus générés automatiquement | Fiabilité limitée |
| Templates | Lien Dropbox de l'enseignant (lien retiré du dépôt) | — |
| Cours de géopolitique | Frédéric Munier (SKEMA) | Support de cours — non redistribuable |
| Cas d'analyse financière (Minerve, Politics) | Enseignant de SKEMA (auteur non indiqué) | Support de cours ; le tableur Politics est un travail d'étudiant |
| Mémoire « L'agilité dans les mégaprojets » | Julien Roussaud et Jérôme Paquereau (MS MPP, SKEMA) | Travail d'étudiants, droits réservés aux auteurs ; remerciements nominatifs non reproduits, un nom d'interviewé pseudonymisé |
| Article de Bass « From Transactional to Transformational Leadership » | Bernard M. Bass, *Organizational Dynamics* | **Article protégé** — scan reconnu par OCR, usage personnel |
| Présentation « Synergie projet / changement » | Travail d'étudiants (SKEMA) | Chiffres non sourcés |

PRINCE2® et AgilePM® sont des marques déposées de leurs propriétaires ; PMI, CAPM et PMBOK sont des marques du Project Management Institute.

## Limites connues

- Les **schémas et captures** des PDF/PowerPoint ne sont pas inclus : ils sont **décrits en texte** (blocs « Figure … », « Schéma … »). Certains détails graphiques peuvent manquer.
- Le **quiz CAPM** d'origine est un PDF d'images : texte obtenu par reconnaissance optique puis relu ; **deux réponses de la clé sont signalées** (⚠️ questions 10 et 25).
- Le cours **Lectures 1-4** (PowerPoint très visuel et animé) est **condensé** : les diapos d'animation répétées sont fusionnées.
- Quelques coquilles du texte d'origine (espaces manquants, tronquages de tableaux dans les PDF) subsistent.
- Les **notes personnelles PRINCE2** mêlent notes et comptes rendus automatiques : à utiliser avec prudence.
- Les dossiers `AGILE`, `COURS` et `PMI-SKEMA` sont convertis ; le dossier `MANAGEMENT COMPLEXITÉ` est vide et le fichier Keynote `.key` de la présentation « Synergie » n'est pas converti (son PDF l'est).
- Les **diapos de géopolitique** sont des textes de cours : cartes, photos et graphiques ne sont pas transcrits. L'**article de Bass** vient d'un scan (OCR, deux colonnes) et le **mémoire** garde les figures non transcrites.
- Les **feuilles de travail Excel** (Minerve 2 et 3) ne sont pas des corrigés : elles contiennent des écarts ou sont incomplètes (signalés ⚠️ dans les fichiers).
