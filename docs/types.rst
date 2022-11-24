.. index:: type

.. _types:

*****
Types
*****

Solidity est un langage à typage statique, ce qui signifie que le type de chaque variable (état et locale) doit être spécifié.
Solidity propose plusieurs types élémentaires qui peuvent être combinés pour former des types complexes.

De plus, les types peuvent interagir entre eux dans des expressions contenant des opérateurs. Pour une liste synthétique des différents opérateurs, voir :ref:`order`.

Le concept de valeurs "indéfinies" ou "nulles" n'existe pas dans Solidity, mais les variables nouvellement déclarées ont toujours une :ref:`valeur par défaut<default-value>` qui dépend de son type. Pour gérer les valeurs inattendues, vous devriez utiliser la :ref:`fonction revert<assert-and-require>`pour annuler la transaction dans son ensemble, ou renvoyer un tuple avec une seconde valeur ``bool`` indiquant le succès de la transaction.

.. include:: types/value-types.rst

.. include:: types/reference-types.rst

.. include:: types/mapping-types.rst

.. include:: types/operators.rst

.. include:: types/conversion.rst
