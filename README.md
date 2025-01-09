Algorithme Insertion
    Entrée : un tableau T de taille n
    Sortie : le tableau T trié

    Début
        pour i de 1 à longueur(T) - 1 faire
            clé := T[i]
            j := i - 1
            tant que j >= 0 et T[j] > clé faire
                T[j + 1] := T[j]
                j := j - 1
            fin tant que
            T[j + 1] := clé
        fin pour
        retourner T
    Fin
