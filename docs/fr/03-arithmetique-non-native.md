# Arithmetique non native

halo2-ecc represente de grands entiers et des corps etrangers par plusieurs limbs natifs.
FpChip implemente les operations de corps premier avec reductions et bornes intermediaires.
Les extensions Fp2 et Fp12 supportent notamment les calculs de pairing BN254.
Les courbes de Weierstrass utilisent addition, doublement et multiplication scalaire optimises.
MSM combine plusieurs points avec des scalaires mais exige des tailles de vecteurs coherentes.
Les points a l infini et decompressions cyclotomiques sont des cas limites de securite importants.
Une egalite modulaire doit etre contrainte sans confondre representation reduite et valeur brute.

Suite : [04 — ECDSA, pairings et EVM](04-ecdsa-pairings-et-evm.md).
