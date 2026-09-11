# Circuits Halo2 avec halo2-lib

halo2-lib fournit des primitives pour construire des circuits sur la pile Halo2.
halo2-base organise les temoins en cellules affectees puis impose des relations par des gates.
Une valeur calculee hors circuit ne devient sure que si chaque relation attendue est contrainte.
GateInstructions couvre les operations arithmetiques communes dans le corps natif.
RangeInstructions ajoute des bornes via une table de lookup configuree.
Le MockProver detecte certaines contraintes violees mais ne reproduit pas un prouveur de production.
L audit doit donc suivre chaque donnee depuis son temoin jusqu aux contraintes qui la lient.

Suite : [02 — Range checks et SafeType](02-range-checks-et-safetype.md).
