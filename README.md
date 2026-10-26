# Second Brain

Système de gestion des connaissances personnelles, organisé selon la méthode **PARA**
(Projets, Domaines, Ressources, Archives) popularisée par Tiago Forte dans *Building a Second Brain*,
complétée par une boîte de réception, un journal et des notes permanentes.

Compatible avec [Obsidian](https://obsidian.md) (il suffit d'ouvrir ce dossier comme « vault »),
mais utilisable avec n'importe quel éditeur Markdown.

## Structure

| Dossier | Rôle | Exemples |
|---|---|---|
| `00_Inbox/` | Capture rapide, sans trier. À vider régulièrement. | Idée, lien, note de réunion brute |
| `01_Projets/` | Objectif précis **avec une échéance**. | Mémoire de fin d'études, dossier de candidature |
| `02_Domaines/` | Responsabilités continues, **sans échéance**. | Cours HEC, carrière, santé, finances |
| `03_Ressources/` | Sujets d'intérêt, documentation de référence. | Finance d'entreprise, lectures, outils |
| `04_Archives/` | Tout ce qui est terminé ou inactif. | Projets finis, cours passés |
| `05_Journal/` | Notes quotidiennes / hebdomadaires. | `2026-10-26.md` |
| `06_Templates/` | Modèles de notes réutilisables. | Projet, cours, lecture, journal |
| `07_Notes_permanentes/` | Idées reformulées avec vos propres mots, reliées entre elles. | Une idée = une note |

## Flux de travail (CODE)

1. **Capturer** : tout va d'abord dans `00_Inbox/`.
2. **Organiser** : chaque semaine, déplacer chaque note vers Projets / Domaines / Ressources, ou la supprimer.
3. **Distiller** : surligner l'essentiel, résumer, extraire les idées clés dans `07_Notes_permanentes/`.
4. **Exprimer** : réutiliser ces notes pour produire (travaux, présentations, décisions).

## Conventions

- Noms de fichiers : `AAAA-MM-JJ` pour le journal, sinon titres clairs (`Finance - Valorisation DCF.md`).
- Liens entre notes : `[[Nom de la note]]` (syntaxe Obsidian).
- Tags : `#statut/actif`, `#statut/termine`, `#type/cours`, `#type/lecture`…
- Un projet terminé → déplacé dans `04_Archives/`.

## Revue hebdomadaire

Voir `06_Templates/Revue hebdomadaire.md`.
