# 04 — Contraintes, portes et donnees publiques

Le constructeur de circuit alloue des cibles, ajoute des portes et relie les fils par des contraintes de copie.
Une porte exprime une identite polynomiale locale ; les contraintes de permutation garantissent la coherence globale des valeurs reliees.
Les constantes, temoins et entrees publiques ont des roles distincts dans la relation.
Les donnees publiques doivent etre enregistrees dans un ordre stable, car cet ordre entre dans l interface de verification.
Une contrainte oubliee ne provoque pas necessairement une erreur : elle peut laisser un degre de liberte au prouveur.
La revue utile suit donc chaque cible depuis son allocation jusqu a toutes ses contraintes.
Source : [`plonk/circuit_builder.rs`](https://github.com/0xPolygonZero/plonky2/blob/main/plonky2/src/plonk/circuit_builder.rs).

[Suite : recursion](05-recursion-et-limites.md)
