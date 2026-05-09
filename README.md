# Calibration bayésienne de codes de calcul par méthodes MCMC

Projet de fin de Master 1 Mathématiques appliquées,
Université Claude Bernard Lyon 1 (2025–2026).
Encadrante : Frédérique Bienvenüe-Duheille.

---

## Contexte

Dans de nombreux domaines (sûreté nucléaire, mécanique des sols, ...),
certaines expérimentations physiques sont impossibles ou trop coûteuses
à réaliser. On leur substitue des codes de calcul dont la fiabilité
dépend de la précision de leurs paramètres d'entrée, souvent mal connus.

Ce projet traite le problème du calage de ces paramètres dans un cadre
bayésien : en combinant des croyances a priori sur les paramètres et les
rares données expérimentales disponibles, on estime une distribution a
posteriori complète sur les paramètres et on en déduit estimations et
intervalles de crédibilité.

L'inférence sur cette distribution a posteriori est réalisée par des
méthodes MCMC, les approches classiques (rejet, importance sampling)
étant inopérantes en grande dimension.

---

## Contenu

**`main.pdf`** *(en cours de rédaction)* — Fondements théoriques et
résultats. Contient à ce stade :

- Formalisation du problème de calage et cadre bayésien
- Théorie des chaînes de Markov (ergodicité, réversibilité, TCL)
- Algorithmes MCMC : Metropolis-Hastings, Rejet retardé (DR),
  Metropolis adaptatif (AM), DRAM
- Diagnostics de convergence : Geweke, Gelman-Rubin, Raftery-Lewis, ESS
- Benchmark sur distributions de référence (Rosenbrock, Rastrigin,
  entonnoir de Neal, gaussienne corrélée en haute dimension)

*En cours : résultats numériques comparatifs des algorithmes sur le
benchmark et applications aux cas d'étude industriels.*

---

## Auteur

Komlan Katakou — M1 Mathématiques appliquées, Université Lyon 1 (2025–2026)
