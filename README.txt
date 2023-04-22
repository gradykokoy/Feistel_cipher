Voici le fichier README pour l'algorithme de Freisnel Cipher :

# Algorithme de Freisnel Cipher

L'algorithme de Freisnel Cipher est un algorithme de chiffrement symétrique à blocs de taille 8 bits. Il utilise une clé de longueur 8 bits et une fonction de permutation pour générer deux sous-clés qui sont utilisées pour chiffrer ou déchiffrer la donnée.

## Comment utiliser l'algorithme

1. Entrez une clé K de longueur 8 bits.
2. Entrez une fonction H de permutation de longueur 8 bits.
3. Entrez l'ordre de décalage à gauche et à droite pour la génération des sous-clés.
4. Entrez la valeur N ou C à traiter, de longueur 8 bits.
5. Choisissez entre chiffrer ou déchiffrer la valeur N ou C.
6. Entrez une permutation P de 4 bits pour l'opération de chiffrement ou déchiffrement.
7. Entrez la clé de permutation pour l'opération de chiffrement ou déchiffrement, de longueur 8 bits.

## Fonctions disponibles

L'algorithme de Freisnel Cipher utilise les fonctions suivantes :

- `OuExclusif(val1, val2)`: Effectue une opération XOR entre deux valeurs binaires de même longueur.
- `OuLogique(val1, val2)`: Effectue une opération OR logique entre deux valeurs binaires de même longueur.
- `ETlogique(va11, val2)`: Effectue une opération AND logique entre deux valeurs binaires de même longueur.
- `permut(val, k)`: Effectue une permutation des bits de la valeur `val` selon la clé `k`.
- `inverse_permut(k)`: Inverse la permutation des bits effectuée par la clé `k`.
- `decalage(val, ordre, gauche)`: Effectue un décalage à gauche ou à droite de la valeur `val` selon l'ordre spécifié.

L'algorithme utilise également les fonctions `generateKey`, `roundDChiffre`, `roundGChiffre`, `roundGDechiffre` et `roundDDechiffre` pour le chiffrement et le déchiffrement des données.
