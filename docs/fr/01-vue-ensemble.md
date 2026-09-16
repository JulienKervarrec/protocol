# 1. Vue d’ensemble d’Exactly

Exactly est un protocole de crédit non custodial qui organise des dépôts et des emprunts à taux variable ou fixe. Le dépôt source contient les contrats Solidity, les scripts de déploiement et la configuration des marchés.

Chaque actif possède un contrat Market. Les marchés flottants fournissent une liquidité continue ; les marchés fixes utilisent des maturités et une comptabilité séparée. Le protocole relie ces pools sans créer un AMM de tokens de maturité.

Le parcours suit Market, Auditor, InterestRateModel, FixedLib et les contrats de périphérie. Il décrit les invariants lisibles dans le code, pas une promesse de rendement ni un audit.

Suite : [architecture d’un marché](02-market-et-erc4626.md).
