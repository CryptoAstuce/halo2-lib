# Range checks et SafeType

Les range checks empechent une valeur de corps de representer un entier hors de la borne attendue.
La decomposition en limbs exige assez de marge pour eviter un wrap dans le corps natif.
La table de lookup doit etre chargee avant toute cellule qui reclame une verification de plage.
SafeType associe une valeur a des garanties supplementaires etablies par le circuit.
Ces garanties sont perdues si une conversion contourne les constructeurs ou oublie une contrainte.
Les longueurs fixes et le packing de bytes doivent exclure representations multiples du meme message.
Les correctifs recents renforcent precisement ces validations de parametres et d identite.

Suite : [03 — Arithmetique non native](03-arithmetique-non-native.md).
