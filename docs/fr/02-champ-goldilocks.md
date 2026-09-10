# 02 — Le champ Goldilocks

Le type central travaille modulo `2^64 - 2^32 + 1`, un nombre premier adapte aux operations sur mots de 64 bits.
Cette forme rend les reductions arithmetiques particulierement efficaces, mais elle ne dispense pas de respecter les invariants du champ.
Les conversions canoniques et non canoniques n ont pas le meme contrat : le lecteur doit verifier laquelle est employee.
Les extensions de champ servent lorsque le protocole demande davantage de structure algebrique.
La securite ne se deduit pas seulement de la taille du champ : nombre de requetes FRI, taux et extension comptent aussi.
Source : [`goldilocks_field.rs`](https://github.com/0xPolygonZero/plonky2/blob/main/field/src/goldilocks_field.rs).

[Suite : engagements et FRI](03-fri-engagements.md)
