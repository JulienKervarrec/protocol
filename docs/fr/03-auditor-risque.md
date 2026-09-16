# 3. Auditor et risque de solvabilité

Auditor centralise le risque inter-marchés. Il enregistre les marchés activés, les paramètres de prix, les facteurs de collatéral et les dettes d’un compte.

Le bitmap accountMarkets suit les marchés qu’un compte a rejoints. Les calculs de liquidité comparent la valeur ajustée du collatéral et la valeur ajustée de la dette. Les facteurs réduisent la valeur reconnue comme garantie et bornent le pouvoir d’emprunt.

Auditor valide aussi les liquidations et calcule l’incitation correspondante. Le risque réel dépend donc de l’oracle, des facteurs, de l’ordre des mises à jour et de la capacité à vendre le collatéral.

Suite : [taux variables et fixes](04-taux-et-maturites.md).
