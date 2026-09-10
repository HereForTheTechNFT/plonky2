# 05 — Recursion, securite et limites

La recursion encode la verification d une preuve precedente dans un nouveau circuit.
Elle sert a agreger des calculs, construire des preuves incrementales ou reduire l interface remise au verificateur final.
Le circuit recursif doit lier explicitement la preuve, les donnees publiques et les donnees communes attendues.
Une configuration incompatible ou des donnees communes substituees changent la relation verifiee.
Plonky2 est un projet de recherche archive : ce parcours explique le code, il ne constitue ni audit ni recommandation de production.
Aucune installation, compilation ou execution de tests n a ete effectuee ; la suite amont reste la reference pour verifier une modification.
Sources : [`recursion`](https://github.com/0xPolygonZero/plonky2/tree/main/plonky2/src/recursion) et [`tests`](https://github.com/0xPolygonZero/plonky2/tree/main/plonky2/src).

[Retour au sommaire](README.md)
