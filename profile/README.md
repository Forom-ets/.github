[<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b39a9b2a-257e-4b8a-88e7-d3a5a8342359" />](https://media.discordapp.net/attachments/1462545996914364476/1466560805209112738/Creation_sans_titre.png?ex=697d30af&is=697bdf2f&hm=163115dfd623388929bdefbe81f3071faddebd976aa8dd2820cafc319eb3eacb&=&format=webp&quality=lossless&width=1703&height=958)
<div align="center">

# 🌀 F O R O M

**Reprenez le contrôle de votre consommation numérique.**
*Une grille de navigation 2D open-source pour structurer la connaissance et favoriser la pensée critique.*

[À propos](https://www.google.com/search?q=%23-%C3%A0-propos) · [L'Initiative ÉTS](https://www.google.com/search?q=%23-initiative-pilote--%C3%A9ts) · [Fonctionnalités](https://www.google.com/search?q=%23-fonctionnalit%C3%A9s-cl%C3%A9s) · [Stack Technique](https://www.google.com/search?q=%23-stack-technique--d%C3%A9marrage) · [Contribuer](https://www.google.com/search?q=%23-contribuer)

---

</div>

## 📖 À propos & Mission

**FOROM** est une initiative open-source née d'un constat simple : les plateformes actuelles nous imposent un flux infini ("doom scrolling") qui érode notre capacité de choix et notre esprit critique.

Nous proposons une alternative radicale : **The Finite Rom Map (FRM)**. Une interface finie, colorée et structurée. Une grille virtuelle où chaque contenu consommé est le fruit d'une décision consciente, naviguée horizontalement par éléments et verticalement par catégories.

* **Stop au Doom Scrolling :** Une fin claire avec des limites définies (ex: 20 éléments par catégorie), explorée via un viewport 5×5.
* **Pensée Critique :** Chaque carte de connaissance ("Mémoire") doit répondre à une question fondamentale (Le système WH).
* **Personnalisation & Gamification :** Un système de quêtes, d'économie (tokens) et de couleurs pour engager l'utilisateur de manière saine.

---

## 🚀 Initiative Pilote : ÉTS (École de technologie supérieure)

Pour lancer le projet, Forom est déployé comme solution sur mesure pour la communauté étudiante et les **clubs de l'ÉTS**.

* **Le Problème :** Le roulement étudiant entraîne une perte massive de connaissances institutionnelles.
* **La Solution FOROM :** Capturer les trucs, astuces, vidéos et savoir-faire des générations précédentes dans une grille visuelle 2D facile à consulter, assurant la pérennité et le soutien des futurs exécutifs (Partenaires, Culture, Clubs, Trésorerie, Atelier).

---

## ✨ Fonctionnalités Clés

### 1. Le Moteur de Navigation (La Grille 2D)

Forom réinvente la navigation avec un moteur de rendu fluide et physique.

* **Grille 5×5 :** Un viewport bidirectionnel. Scrollez horizontalement à l'infini (loop) dans une catégorie, et verticalement pour changer de sujet.
* **Sidebar "Roue" (Wheel) :** Un sélecteur de catégories incurvé, animé par la physique des ressorts (Framer Motion).
* **Responsive absolue :** Un dimensionnement basé sur `vw`/`vh` qui s'adapte à tous les écrans sans breakpoints classiques.

### 2. Les Mémoires & La Logique de Couleur

Dans FOROM, un post est une **"Mémoire"**. Pour créer ou consulter une mémoire, le code couleur guide l'angle et la réflexion :

| Question | Couleur | Hex | Aperçu |
| --- | --- | --- | --- |
| **QUI ?** | Ambre | `#F59E0B` |  |
| **QUOI ?** | Or | `#FACC15` |  |
| **OÙ ?** | Lime | `#84CC16` |  |
| **QUAND ?** | Émeraude | `#10B981` |  |
| **COMMENT ?** | Céruléen | `#0EA5E9` |  |
| **COMBIEN ?** | Indigo | `#4F46E5` |  |
| **POURQUOI ?** | Violet | `#8B5CF6` |  |

### 3. Économie & Gamification

Forom intègre des systèmes pour récompenser la participation constructive :

* **Système de Quêtes :** Des missions guidées avec un modal dédié pour suivre sa progression.
* **Portefeuille (Wallet) & Tokens :** Une monnaie in-app modifiable gagnée en contribuant au savoir collectif.
* **Bouton Heart FAB :** Un bouton d'action flottant pour soutenir la communauté.

---

## 🛠️ Stack Technique & Démarrage

FOROM est propulsé par une stack moderne et performante, prête pour la production.

| Technologie | Rôle |
| --- | --- |
| **React 19 & TypeScript** | Architecture des composants et sécurité des types |
| **Vite 7** | Outil de build ultra-rapide |
| **Tailwind CSS 4** | Styling utilitaire et thèmes (Dark/Light mode) |
| **Framer Motion 12** | Animations basées sur la physique (ressorts, inertie) |
| **PostgreSQL & Docker** | Base de données et déploiement conteneurisé |

### Installation

**Prérequis :** Node.js 18+ et npm 9+ (ou Docker).

```bash
# Cloner le dépôt
git clone https://github.com/votre-equipe/forom.git
cd forom

# Installer les dépendances
npm install

# Lancer le serveur de développement local
npm run dev

```

L'application sera accessible sur `http://localhost:5173`.

---

## 🤝 Contribuer

FOROM est un projet **Open Source**. Nous croyons que la meilleure façon de redonner le pouvoir aux utilisateurs est de construire l'outil avec eux. Que vous souhaitiez forker l'interface ou ajouter des fonctionnalités au noyau, votre aide est précieuse !

**Idées de contributions actuelles :**

* Support des gestes tactiles (swipe) pour mobile.
* Amélioration de l'accessibilité (ARIA, lecteurs d'écran).
* Intégration backend (API) pour la persistance des données complexes.
* Évolution du système de niveaux (XP) et d'économie.

Consultez `CONTRIBUTING.md` pour savoir comment proposer une Pull Request.

---

## 📜 Licence

<a href="[https://creativecommons.org/licenses/by-sa/4.0/](https://creativecommons.org/licenses/by-sa/4.0/)">
<img src="[https://licensebuttons.net/l/by-sa/4.0/88x31.png](https://licensebuttons.net/l/by-sa/4.0/88x31.png)" alt="CC BY-SA 4.0" />
</a>

Ce projet est distribué sous la licence **[Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/)**.
Vous êtes libre de partager et d'adapter le matériel, à condition de créditer Forom et de partager vos modifications sous la même licence.

---

<div align="center">

**Développé avec ❤️ par la communauté Forom**

*L'avenir de la navigation de contenu est fini.*

</div>

---

Voudrais-tu que je t'aide à rédiger le fichier `CONTRIBUTING.md` mentionné dans ce README pour guider tes futurs développeurs ?
