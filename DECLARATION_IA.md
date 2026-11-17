# Déclaration des ressources et outils d'IA

| Outil ou ressource | Version ou date | Usage précis | Parties concernées | Vérification effectuée |
| :--- | :--- | :--- | :--- | :--- |
| Assistant d'IA (Gemini) | Novembre 2026 | Aide à la structuration du pipeline temporel et de la méthodologie (première version du notebook) | Sections 4, 5, 6 | Code testé, sorties comparées aux exigences du sujet |
| Assistant d'IA (Claude, Anthropic) | 17 novembre 2026 | Correction de la première version : mois manquant d'octobre 2025 mal traité, références complémentaires, courbe de validation, analyse des erreurs, incertitude (bootstrap), rédaction des interprétations | Sections 2 à 10 | Notebook exécuté de bout en bout ; chiffres du texte générés à partir des sorties ; contrôles d'alignement (`assert`). À relire et à pouvoir expliquer en soutenance |
| Documentation officielle | scikit-learn, pandas | Paramètres de `Ridge`, `TimeSeriesSplit`, `GridSearchCV` | Sections 5 et 6 | Test du code |
| Source de données | FRED, extraction du 17 nov. 2026 | Série CPIAUCSL | Section 2 | Dimensions, dates et manquants vérifiés |
