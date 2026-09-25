# Circuits Halo2 avec halo2-lib

halo2-lib fournit des primitives pour construire des circuits sur la pile Halo2.
halo2-base organise les témoins en cellules affectées puis impose des relations par des gates.
Une valeur calculée hors circuit ne devient sûre que si chaque relation attendue est contrainte.
GateInstructions couvre les opérations arithmétiques communes dans le corps natif.
RangeInstructions ajoute des bornes via une table de lookup configurée.
Le MockProver détecte certaines contraintes violées mais ne reproduit pas un prouveur de production.
L’audit doit donc suivre chaque donnée depuis son témoin jusqu’aux contraintes qui la lient.

Suite : [02 — Range checks et SafeType](02-range-checks-et-safetype.md).
