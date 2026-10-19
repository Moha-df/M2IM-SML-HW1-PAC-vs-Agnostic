# Statistical and Machine Learning : HW1 et HW2

**Mohamed De Franceschi** - M2 IM - Statistical and Machine Learning - Université de Haute-Alsace

Ce dépôt contient les deux homeworks : le HW1 (`De_Franceschi_Mohamed_HW1.ipynb`) et le HW2 (`De_Franceschi_Mohamed_HW2.ipynb`).

## HW1 : PAC et PAC agnostique

Ce dépôt contient le notebook `De_Franceschi_Mohamed_HW1.ipynb`, qui compare expérimentalement l'apprentissage PAC (labels sans erreur) et PAC agnostique (10 % de labels inversés) sur des classifieurs à seuil dans [0, 1].

### Contenu du notebook

1. Génération des données
2. Algorithme ERM (implémenté à la main, sans bibliothèque de ML)
3. Erreur empirique et erreur vraie
4. Vérification expérimentale du PAC
5. Cas agnostique avec bruit sur les labels
6. Conclusion

### Lancer le notebook

Prérequis : Python 3 avec `numpy`, `matplotlib` et `jupyter`.

```bash
pip install numpy matplotlib jupyter
jupyter notebook De_Franceschi_Mohamed_HW1.ipynb
```

Puis *Kernel → Restart & Run All*. L'exécution prend une dizaine de secondes, et la graine aléatoire fixe (42) donne toujours les mêmes résultats.

## HW2 : Convergence uniforme et limites de l'apprentissage

Le notebook `De_Franceschi_Mohamed_HW2.ipynb` simule directement les lois de probabilité du cours. On y regarde comment l'erreur empirique fluctue autour de l'erreur vraie, pour une hypothèse puis pour toute une classe finie. On apprend ensuite des cibles aléatoires pour illustrer le No-Free-Lunch, et on termine avec des cibles à seuil, où la classe des seuils permet de généraliser.

### Contenu du notebook

1. Partie I : convergence uniforme (erreur empirique, borne de Hoeffding, borne de l'union, effet de |H|, complexité d'échantillon)
2. Partie II : No-Free-Lunch (points non vus, apprentissage par cœur, prédiction sur les points non vus)
3. Partie III : connaissance a priori (ERM sur les seuils, comparaison avec les cibles aléatoires)
4. Conclusion

### Lancer le notebook

Les prérequis sont les mêmes que pour le HW1 :

```bash
jupyter notebook De_Franceschi_Mohamed_HW2.ipynb
```

Puis *Kernel → Restart & Run All*. L'exécution prend environ 30 secondes. La graine est la même que dans le HW1 (42).
