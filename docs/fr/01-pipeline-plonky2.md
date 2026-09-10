# 01 — Carte du pipeline Plonky2

Plonky2 transforme un circuit en polynomes sur le champ Goldilocks, puis engage leurs evaluations avant les controles FRI.
Le module `plonk` orchestre la preuve, tandis que `fri` porte le test de proximite de bas degre.
Les donnees publiques appartiennent a la relation prouvee ; elles ne rendent pas le temoin public.
Le transcript Fiat–Shamir derive les defis a partir des engagements deja observes.
La recursion permet a un circuit de verifier une autre preuve et de compresser une chaine de calculs.
Ce parcours relie chaque notion aux modules sources au lieu de presenter Plonky2 comme une boite noire.
Source : [`plonky2/src`](https://github.com/0xPolygonZero/plonky2/tree/main/plonky2/src).

[Suite : le champ Goldilocks](02-champ-goldilocks.md)
