# mp2i
# TIPE — Optimisation énergétique des trajets dans un graphe pondéré

> **Thème** : Sobriété, Efficacité, Optimisation

---

## Problématique

**Comment adapter les algorithmes classiques de plus court chemin pour minimiser un coût énergétique plutôt qu'une distance ?**

---

## Objectifs

- Étudier la théorie des graphes pondérés et implemnter quelque codes
- Comparer leur complexité et leurs performances
- Étudier une optimisation multi-critère (énergie / temps)

---

## Structure du dépôt

```
TIPE/
├── README.md               ← Ce fichier
├── requirements.txt        ← Dépendances Python
│
├─
```

---

## Concepts étudiés

| Concept | Description |
|---|---|
| Graphes pondérés | Modélisation d'un réseau avec des coûts énergétiques |
| Complexité algorithmique | Analyse en temps et en espace des algorithmes |
| Plus court chemin | Dijkstra, Bellman-Ford, A* |


---

## Avancement

- [ ] Modélisation mathématique
- [ ] Implémentation Dijkstra
- [ ] Implémentation Bellman-Ford
- [ ] Comparaison expérimentale
- [ ] Extension multicritère

---

## Utilisation rapide

```python
from src.graph import Graph
from src.dijkstra import dijkstra

g = Graph()
g.add_edge("A", "B", poids=3.5)  # poids = coût énergétique
g.add_edge("B", "C", poids=2.0)

chemin, cout = dijkstra(g, source="A", cible="C")
print(f"Chemin optimal : {chemin}, coût énergétique : {cout}")
```

