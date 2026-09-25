# ECDSA, pairings et EVM

Le module secp256k1 permet de vérifier dans le circuit des signatures compatibles Ethereum.
La clé publique, le message et les composantes de signature doivent être liés aux entrées publiques attendues.
Le module BN254 construit les opérations nécessaires au pairing optimal Ate.
Ces primitives rendent possibles aggregation, vérification récursive et preuves de données EVM.
Le coût en contraintes dépend fortement des décompositions, fenêtres et tables pré-calculées.
Une optimisation ne doit jamais supprimer le traitement des identités ou des scalaires limites.
La vérification onchain exige en plus un encodage canonique des sorties publiques.

Suite : [05 — Limites et vérification](05-limites-et-verification.md).
