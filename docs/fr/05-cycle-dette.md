# 5. Emprunt, remboursement et liquidation

Un emprunteur dépose du collatéral reconnu par Auditor, puis tire une dette sur un Market compatible. Le remboursement réduit la dette et rétablit progressivement la liquidité du marché.

Si la position passe sous les seuils de solvabilité, Auditor accepte une liquidation conforme aux règles du protocole. Le liquidateur reçoit une incitation, mais l’opération est bornée par la valeur du collatéral et les paramètres de marché.

La séquence doit être analysée avec les arrondis, les intérêts accumulés, les prix et les frais. Une position saine au dernier bloc peut devenir liquidable après variation d’oracle ou accumulation de dette.

Suite : [périphérie et levier](06-peripherie-et-levier.md).
