# 🗣️ Système de Reconnaissance Automatique de Voyelles 

**Matière :** Signaux analogiques et numériques (3ETI) - CPE Lyon  
**Année :** 2025-2026  
**Auteurs :** Timeo Martin, Arno Braz, Julie Le Ral  

## 📖 Description du Projet

L'objectif dans ce projet est de réaliser un algorithme de classification de voyelles capable de reconnaître automatiquement les sons /a/ /e/ /i/ /o/ et /u/.

Le système repose sur l'analyse spectrale (Transformée de Fourier) pour extraire l'empreinte harmonique de chaque son et le classifier par comparaison avec une base d'apprentissage.

## 📂 Structure du Projet
```
├── Programmes
│   └── Main.ipynb          # Programme principal
├── Sons                    # Dossier contenant les signaux
│   ├── apprentissage/  
│   ├── test/          
│   └── etude/          
└── README.md           
```

## 📊 Visualisation

Le notebook utilise `plotly.express` pour générer des graphiques interactifs, permettant d'observer précisément :
* Le signal temporel.
* Le spectre fréquentiel (linéaire et log10) pour valider la position des pics harmoniques.

*Note : Le signal attribué à notre groupe pour l'étude de cas est le **Signal 6**.*

## 🛠️ Environnement

Le projet est codé en Python 3.12 et utilise l'environnement virtuel `env_msi` fourni par l'école.

* **Bibliothèques principales :** `numpy`, `scipy`, `plotly`.
* **Bibliothèque spécifique :** `msicpe` (Bibliothèque de CPE Lyon).
