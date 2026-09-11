# ECDSA, pairings et EVM

Le module secp256k1 permet de verifier dans le circuit des signatures compatibles Ethereum.
La cle publique, le message et les composantes de signature doivent etre lies aux entrees publiques attendues.
Le module BN254 construit les operations necessaires au pairing optimal Ate.
Ces primitives rendent possibles aggregation, verification recursive et preuves de donnees EVM.
Le cout en contraintes depend fortement des decompositions, fenetres et tables pre-calculees.
Une optimisation ne doit jamais supprimer le traitement des identites ou des scalaires limites.
La verification onchain exige en plus un encodage canonique des sorties publiques.

Suite : [05 — Limites et verification](05-limites-et-verification.md).
