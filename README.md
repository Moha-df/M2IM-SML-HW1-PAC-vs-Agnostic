# HW1 : PAC et PAC agnostique

**Mohamed De Franceschi** - M2 IM - Statistical and Machine Learning - Université de Haute-Alsace

Ce dépôt contient le notebook `De_Franceschi_Mohamed_HW1.ipynb`, qui compare expérimentalement l'apprentissage PAC (labels sans erreur) et PAC agnostique (10 % de labels inversés) sur des classifieurs à seuil dans [0, 1].

## Contenu du notebook

1. Génération des données
2. Algorithme ERM (implémenté à la main, sans bibliothèque de ML)
3. Erreur empirique et erreur vraie
4. Vérification expérimentale du PAC
5. Cas agnostique avec bruit sur les labels
6. Conclusion

## Lancer le notebook

Prérequis : Python 3 avec `numpy`, `matplotlib` et `jupyter`.

```bash
pip install numpy matplotlib jupyter
jupyter notebook De_Franceschi_Mohamed_HW1.ipynb
```

Puis *Kernel → Restart & Run All*. L'exécution prend une dizaine de secondes, et la graine aléatoire fixe (42) donne toujours les mêmes résultats.