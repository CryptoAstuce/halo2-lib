# Range checks et SafeType

Les range checks empêchent une valeur de corps de représenter un entier hors de la borne attendue.
La décomposition en limbs exige assez de marge pour éviter un wrap dans le corps natif.
La table de lookup doit être chargée avant toute cellule qui réclame une vérification de plage.
SafeType associe une valeur à des garanties supplémentaires établies par le circuit.
Ces garanties sont perdues si une conversion contourne les constructeurs ou oublie une contrainte.
Les longueurs fixes et le packing de bytes doivent exclure représentations multiples du même message.
Les correctifs récents renforcent précisément ces validations de paramètres et d’identité.

Suite : [03 — Arithmétique non native](03-arithmetique-non-native.md).
