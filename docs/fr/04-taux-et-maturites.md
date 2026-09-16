# 4. Taux, utilisation et maturités

InterestRateModel calcule le taux variable à partir de l’utilisation du marché. Le code expose notamment une utilisation naturelle, une vitesse de croissance et une composante sigmoïde : le taux ne suit pas simplement une pente unique.

FixedLib représente les périodes de quatre semaines, les montants fournis et empruntés, les gains non affectés et le recours de la liquidité flottante comme réserve de secours.

Les pools fixes n’achètent pas nécessairement un token de maturité sur un marché secondaire. Leur taux provient de l’utilisation et de la maturité visée, tandis que la liquidité flottante absorbe une partie des déséquilibres.

Suite : [emprunt, remboursement et liquidation](05-cycle-dette.md).
