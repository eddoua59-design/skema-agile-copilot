---
description: Génère des flashcards (question / réponse) prêtes à importer
agent: ask
argument-hint: sujet ou fichier
---

# Flashcards

Sujet ou fichier : ${input:sujet:ex. docs/prince2/guide-rapide-foundation/06-processus.md, ou les 8 principes DSDM}
Nombre de cartes : ${input:nombre:15}

- Une carte = **une seule notion**, question courte au recto, réponse courte et exacte au verso (termes officiels).
- Mélange définitions, listes à retenir, « quel rôle / quel processus pour… », et différences entre cadres.
- Présente le résultat en **tableau Markdown** (`Question | Réponse | Source`), puis en **CSV à deux colonnes** (`question;réponse`) dans un bloc de code, pour import dans Anki ou Quizlet.
- Ne crée une carte que si l'information est dans le dépôt.
