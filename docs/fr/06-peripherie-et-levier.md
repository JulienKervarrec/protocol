# 6. Périphérie, levier et lecture

DebtManager facilite le levier et le deleveraging en combinant une position Exactly avec un prêt flash Balancer. Il doit vérifier le résultat économique, les actifs attendus et le remboursement du prêt dans la même transaction.

Previewer et RatePreviewer servent à agréger ou prévisualiser des données sans modifier directement la position. MarketETHRouter adapte les flux ETH aux marchés qui comptabilisent un token ERC-20.

Ces contrats de périphérie sont pratiques mais élargissent la surface d’intégration. Le contrat principal reste la source de vérité pour les parts, la dette, les plafonds et les autorisations.

Suite : [proxies et variantes vérifiées](07-proxies-et-variantes.md).
