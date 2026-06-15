# gaming-dashboard
# 🎮 Gaming Dashboard 2024

Un dashboard interactif sur l'industrie du jeu vidéo en 2024, avec projections jusqu'en 2026.

> Projet réalisé par **Kenza HALIL** — étudiante en informatique en alternance.

---

## Aperçu

![Dashboard gaming sombre avec graphiques et statistiques](preview.png)

Ce dashboard présente en une seule page :
- Les **revenus mondiaux** du gaming de 2019 à 2024, avec projections 2025–2026
- La **répartition par plateforme** (Mobile, Console, PC, Cloud)
- Les **genres les plus joués** avec leurs parts de marché
- Le **top 6 des jeux Steam** par pic de joueurs simultanés
- Les **principaux tournois esport** et leurs prize pools
- Les **segments de marché** (Mobile, Console, PC, Esport)

---

## Technologies utilisées

| Technologie | Rôle |
|---|---|
| **HTML5** | Structure de la page |
| **CSS3** | Design, animations, mise en page responsive |
| **JavaScript (Vanilla)** | Logique, génération dynamique du contenu, animations |
| **[Chart.js 4.4](https://www.chartjs.org/)** | Graphiques (donut + courbe) |
| **Google Fonts** | Polices Space Grotesk & Space Mono |

Aucun framework, aucun serveur, aucune dépendance à installer — **un seul fichier HTML**.

---

## Fonctionnalités

- **Compteurs animés** — les chiffres défilent de 0 à la valeur réelle au chargement
- **Graphique double ligne** — ligne pleine pour les données réelles, pointillée pour les projections
- **Barres de genres animées** avec effet glow
- **Hover interactif** sur toutes les cartes, lignes de jeux et tableau esport
- **Badges colorés** par genre pour chaque jeu
- **Design responsive** — s'adapte au mobile
- **Fond lumineux** avec glow radial violet/rose
- **Barre de navigation** fixe avec indicateurs réel / projection

---

## Sources des données

Toutes les données 2024 sont issues de sources publiques :

| Donnée | Source |
|---|---|
| Revenus mondiaux ($187Md) | [Newzoo Global Games Market Report 2024](https://newzoo.com) |
| Nombre de joueurs (3.3Md) | [Statista](https://statista.com) |
| Parts de marché par genre | Newzoo · DFC Intelligence |
| Top jeux Steam | [Steam Charts](https://steamcharts.com) |
| Prize pools & viewers esport | [Esports Charts](https://escharts.com) |

Les valeurs 2025 et 2026 sont des **projections** basées sur les tendances historiques du marché (+8–9% de croissance annuelle).

---

## Lancement

Aucune installation requise.

```bash
# Cloner ou télécharger le fichier
# Puis double-cliquer sur gaming-dashboard.html
```

Ou ouvrir directement dans n'importe quel navigateur moderne (Chrome, Firefox, Edge, Safari).

---

## Structure du fichier

```
gaming-dashboard.html
│
├── <head>
│   ├── Chart.js (CDN)
│   └── CSS — variables, layout Grid, animations
│
├── <body>
│   ├── <nav>     Barre de navigation fixe
│   ├── <header>  Section hero avec KPIs animés
│   ├── <main>    Grille 12 colonnes avec 6 cartes
│   └── <footer>  Sources et auteur
│
└── <script>
    ├── Données (tableaux JS)
    ├── Animation des compteurs (IntersectionObserver)
    ├── Génération dynamique du HTML (forEach)
    └── Graphiques Chart.js (donut + ligne)
```

---

## Ce que ce projet démontre

- Structuration sémantique HTML5
- CSS moderne : Grid, variables, `backdrop-filter`, `radial-gradient`, transitions
- JavaScript Vanilla : DOM, `forEach`, `IntersectionObserver`, `requestAnimationFrame`
- Intégration d'une bibliothèque externe (Chart.js)
- Data visualisation : choix des graphiques adaptés aux données
- Design UI/UX : hiérarchie visuelle, lisibilité, responsive

---

## Auteur

**Kenza HALIL** — Étudiante en informatique en alternance
