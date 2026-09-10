# 03 — Engagements, oracles et FRI

FRI teste qu une fonction engagee est proche d un polynome de faible degre sans publier tout le polynome.
Le prouveur engage des couches successives dans des arbres de Merkle ; le verificateur n ouvre que des positions echantillonnees.
Les defis du transcript fixent les combinaisons et les indices apres les engagements correspondants.
Chaque pli reduit le domaine et reporte la coherence vers une couche plus petite.
Une preuve contient donc des ouvertures Merkle, des valeurs de couches et les donnees finales attendues par le verificateur.
La configuration FRI est un compromis explicite entre taille, temps et marge de securite.
Source : [`fri`](https://github.com/0xPolygonZero/plonky2/tree/main/plonky2/src/fri).

[Suite : contraintes PLONK](04-contraintes-et-portes.md)
