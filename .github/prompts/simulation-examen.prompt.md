---
description: Simulation d'examen sans correction immédiate, avec bilan chiffré
agent: ask
argument-hint: certification (PRINCE2, AgilePM ou CAPM) et nombre de questions
---

# Simulation d'examen

Certification : ${input:certification:PRINCE2 / AgilePM / CAPM}
Nombre de questions : ${input:nombre:10}

Règles :
1. Tire au hasard le nombre de questions demandé dans les examens blancs du dépôt (`docs/prince2/examen-blanc-prince2-7/`, `docs/agilepm/examen-blanc-agilepm/`, `docs/capm/quiz-skema-capm.md`).
2. Pose-les **toutes d'un coup**, numérotées, avec leurs options, **sans réponse** ni justification. Rappelle le format réel de l'examen (durée, nombre de questions, seuil de réussite : voir les fichiers).
3. J'y réponds en une seule fois (ex. « 1B 2D 3A… »). Ensuite seulement, corrige tout : score, comparaison avec le seuil de réussite, puis justification des erreurs.
4. Termine par un **plan de révision ciblé** : thèmes manqués, fichiers du dépôt à relire, ordre conseillé.
