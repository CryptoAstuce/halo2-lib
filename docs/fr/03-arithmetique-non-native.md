# Arithmétique non native

halo2-ecc représente de grands entiers et des corps étrangers par plusieurs limbs natifs.
FpChip implémente les opérations de corps premier avec réductions et bornes intermédiaires.
Les extensions Fp2 et Fp12 supportent notamment les calculs de pairing BN254.
Les courbes de Weierstrass utilisent addition, doublement et multiplication scalaire optimisés.
MSM combine plusieurs points avec des scalaires mais exige des tailles de vecteurs cohérentes.
Les points à l’infini et décompressions cyclotomiques sont des cas limites de sécurité importants.
Une égalité modulaire doit être contrainte sans confondre représentation réduite et valeur brute.

Suite : [04 — ECDSA, pairings et EVM](04-ecdsa-pairings-et-evm.md).
