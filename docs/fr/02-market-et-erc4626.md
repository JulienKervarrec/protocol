# 2. Market et comptabilité ERC-4626

Market hérite de MarketBase et utilise une comptabilité de coffre : les parts représentent une fraction des actifs et de la dette du marché. Les fonctions de dépôt, retrait, emprunt et remboursement modifient les soldes et les parts selon l’état courant.

MarketExtension regroupe certaines opérations appelées via delegatecall. Cette modularité réduit la taille logique du contrat principal, mais impose de suivre soigneusement le contexte de stockage et les autorisations.

La conversion parts-actifs doit rester cohérente lorsque les intérêts et les revenus non réalisés évoluent. Une interface ne doit donc jamais traiter le nombre de parts comme un montant fixe.

Suite : [le registre de risque Auditor](03-auditor-risque.md).
