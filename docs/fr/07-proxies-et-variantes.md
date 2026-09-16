# 7. Proxies et variantes vérifiées

Les déploiements utilisent des proxies ERC-1967 et séparent adresse de proxy et adresse d’implémentation. Une mise à niveau doit préserver le stockage, les rôles et les invariants de comptabilité.

Le dossier contracts/verified contient des variantes comme VerifiedMarket, VerifiedAuditor et Firewall pour des déploiements soumis à des contrôles supplémentaires. Elles ajoutent une frontière de conformité ; elles ne remplacent pas l’analyse du risque financier.

Les fichiers deployments documentent plusieurs réseaux, notamment Optimism et Base. Une adresse présente dans le dépôt n’est pas une preuve qu’un marché est actif ou correctement configuré aujourd’hui.

Suite : [limites et périmètre](08-limites-et-perimetre.md).
