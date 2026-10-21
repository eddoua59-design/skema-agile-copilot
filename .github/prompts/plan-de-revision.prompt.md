---
description: Plan de révision jour par jour pour une certification
agent: ask
argument-hint: certification, date d'examen, heures par semaine
---

# Plan de révision

Certification : ${input:certification:PRINCE2 Foundation / AgilePM Foundation / CAPM}
Date de l'examen : ${input:date:ex. 15 décembre 2026}
Temps disponible : ${input:temps:ex. 5 heures par semaine}

Construis un plan réaliste à partir des fichiers du dépôt :
1. Calcule le nombre de semaines restantes à partir de la date du jour (demande-la-moi si tu ne la connais pas).
2. Découpe le programme en blocs (cours → fiches → quiz thématiques → examens blancs → simulation), avec les **fichiers exacts** à lire pour chaque bloc.
3. Prévois deux **simulations d'examen** (prompt `simulation-examen`) et une semaine de rappel final.
4. Rappelle le format de l'examen (durée, nombre de questions, seuil) tel qu'il figure dans le dépôt.
5. Présente le plan en tableau (semaine, objectif, fichiers, temps). Propose d'adapter le plan après chaque simulation.
