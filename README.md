# LAB5 - Sécurité mobile

## Résumé
Ce dossier contient un rapport personnalisé pour **Amira Ezbiri** sur l'analyse d'une application Android qui cache sa logique de vérification dans une bibliothèque native.

## Fichiers fournis
- `rapport_lab5_amira_ezbiri (1).pdf` : version PDF du rapport
- `README_LAB5_Amira_Ezbiri.md` : ce fichier
## Contenu du rapport
Le rapport suit le flux d'analyse suivant :
1. découverte de l'application
2. test d'une valeur incorrecte
3. analyse Java dans JADX
4. extraction de `libfoo.so`
5. analyse native dans Ghidra
6. décodage du secret
7. validation finale dans l'application

## Secret final
`Thanks for all the fish`

## Compilation PDF
Si besoin, recompilation locale :

```bash
pdflatex rapport_laboratoire_lab5_amira_ezbiri.tex
pdflatex rapport_laboratoire_lab5_amira_ezbiri.tex
```

## Remarque
Les captures utilisées proviennent du dépôt GitHub du TP, mais seules les images les plus utiles ont été retenues pour garder un rapport clair et lisible.
