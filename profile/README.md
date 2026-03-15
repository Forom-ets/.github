[<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b39a9b2a-257e-4b8a-88e7-d3a5a8342359" />](https://media.discordapp.net/attachments/1462545996914364476/1466560805209112738/Creation_sans_titre.png?ex=697d30af&is=697bdf2f&hm=163115dfd623388929bdefbe81f3071faddebd976aa8dd2820cafc319eb3eacb&=&format=webp&quality=lossless&width=1703&height=958)

<div align="center">

# 🏰 F O R O M 🏰

**The Finite Rom Map (FRM) — Reprenez le contrôle de votre mémoire numérique.**

*Un écosystème 2D open-source, auto-hébergé et gamifié pour structurer la connaissance, entraîner votre propre IA, et sauver vos communautés.*

[Le Lobby Public](https://forom.prodv2.cedille.club/) · [Philosophie](#-la-philosophie-serveur-minecraft) · [Le Projet ÉTS](#-initiative-pilote--%C3%A9ts) · [La ROMAP (Progression)](#-la-romap--progression--ia) · [Matériel](#%EF%B8%8F-mat%C3%A9riel--auto-h%C3%A9bergement)

---

</div>

## 🌐 Le Lobby Forom

Le **Lobby Principal** sert de portail (tracker) pour tous les serveurs Forom publics ayant atteint leur niveau maximum. 
👉 **[Visitez le Lobby : forom.prodv2.cedille.club](https://forom.prodv2.cedille.club/)**

Actuellement, le lobby héberge :
1. **Le Forom Public :** La porte d'entrée officielle et la documentation de l'écosystème.
2. **Le Projet Pilote ÉTS :** Un espace sécurisé pour **70 clubs étudiants de l'ÉTS** afin d'archiver leur mémoire à long terme et d'assurer le transfert de connaissances entre les générations.

---

## ⛏️ La Philosophie "Serveur Minecraft"

**FOROM n'est pas un réseau social classique.** C'est un centre de commandement multijoueur pour votre communauté. 

Imaginez lancer un serveur **Minecraft privé** avec vos amis. Mais au lieu de construire des châteaux en blocs, vous bâtissez une base de connaissances ultra-structurée pour accomplir une mission réelle. 

1. **Vous possédez les données :** Vous n'utilisez pas notre cloud. Vous installez Forom sur votre propre machine locale (nous recommandons un NVIDIA Jetson).
2. **L'Ère Privée :** Votre Forom naît sur `localhost`. Il est privé, sur invitation seulement. Vous et vos amis commencez à remplir la grille.
3. **Le But Ultime (ROM) :** Votre objectif est de survivre à 3 phases de progression rigoureuses. Si vous réussissez, votre serveur débloque **ROM**, une IA locale (système RAG) entraînée *exclusivement* sur vos 1 an d'archives.
4. **Le Portail Public :** Une fois le rituel final accompli, votre Forom établit un tunnel sécurisé vers notre Lobby Principal. Vous gardez vos données chez vous, mais votre communauté devient visible pour le monde entier.

---

## 🧭 Le Moteur de Navigation (La Grille 10x10)

Forom combat le "doom scrolling" infini en proposant une interface finie, spatiale et intentionnelle. 
La navigation se fait via un **viewport 5x5** propulsé par la physique des ressorts (Framer Motion), permettant d'explorer une grille virtuelle de **10x10**.

Chaque post est placé à une intersection stratégique :
* **L'Axe Y (Catégories A-J) :** Les Piliers de votre mission (ex: *Stratégie, Opérations, Trésorerie, Gouvernance*).
* **L'Axe X (Actions 0-9) :** L'état de l'information (ex: *Idée, Quête, SOS, Accompli, Savoir*).

### Les Mémoires & Le Système de Coordonnées (A-J / 0-9)
Dans cette grille, on ne "poste" pas dans le vide. Le contenu de haute valeur est appelé une **"Mémoire"** et doit être forgé à une intersection précise de la matrice 10x10. Ce système de coordonnées (100 cases) dicte comment l'IA locale (ROM) comprendra le contexte de votre communauté.

La matrice est structurée ainsi :
* **L'Axe Y (A à J) — Les Piliers :** Représente les domaines de votre mission (ex : *A. Vision, D. Opérations, I. Mémoire, etc.*).
* **L'Axe X (0 à 9) — Les États d'Action :** Représente le statut de l'information (ex : *0. Idée, 2. Quête, 4. SOS, 8. Savoir, etc.*).

**La Synergie des Coordonnées :**
Chaque Mémoire possède une adresse unique (ex: **D2**, **I8**) qui lui donne tout son sens :
* 🎯 **[D. Opérations] + [2. Quête] = D2** : Signale un besoin de main-d'œuvre concret sur le terrain.
* 🧠 **[I. Mémoire] + [8. Savoir] = I8** : Représente une connaissance absolue et vérifiée. *(C'est cette donnée spécifique qui a la plus grande valeur pour nourrir le système RAG !)*

**La Logique des 3 Stades d'Archivage :**
Le but du serveur n'est pas simplement de remplir la grille, mais de faire évoluer ces 100 coordonnées à travers **3 Stades** (Phases) pour créer une base de données parfaite :
1. **Le Stade V1 (Le Brouillon) :** La communauté défriche et remplit les 100 cases pour la première fois.
2. **Le Stade V2 (L'Itération) :** La difficulté augmente. Les membres doivent relire, corriger et améliorer l'intégralité de la grille.
3. **Le Stade V3 (Le Canon) :** L'ultime version. C'est cette matrice finale de 100 Mémoires parfaites qui servira de corpus de base pour éveiller et entraîner votre assistant IA (ROM).

---

## 🚀 La ROMAP : Progression & IA

Votre serveur ne commence pas avec son assistant IA (ROM). Vous devez le mériter en complétant la **ROMAP**, une évolution obligatoire en 3 phases.

### 🔴 Phase 1 : Les Fondations (V1)
* **Objectif :** Remplir intégralement la grille de 10x10 avec 100 mémos fondateurs.
* **Économie :** Chaque quête coûte **2 PX** et rapporte **2 PX**.
* **Déblocage :** Les 100 mémos sont archivés (V1). Le Forom passe en Phase 2.

### 🟢 Phase 2 : L'Itération (V2)
* **Objectif :** Récrire, améliorer et itérer sur l'intégralité des 100 mémos pour créer la V2.
* **Économie (Inflation) :** La valeur double (x2). Les quêtes coûtent **4 PX**. La trésorerie communautaire doit atteindre 1/4 du pouvoir d'achat global.
* **Déblocage :** La V2 est archivée. La Phase finale commence.

### 🔵 Phase 3 : L'Éveil de ROM (V3)
* **Objectif :** Forger la version définitive du savoir (V3) et prouver la force de votre communauté.
* **Économie :** Valeur quadruplée (x4). **8 PX** par quête.
* **Population Requise :** 9 Super Mods, 25 Mods, 75 Créateurs, et 500 Associés.
* **Le Rituel :** L'équipe de modération investit 1250 PX, et la communauté investit 1250 PX ensemble.
* **Récompense :** **ROM s'éveille.** Votre IA locale est entraînée sur vos 300 mémos. Votre serveur devient Public sur le Lobby, et une prime de +5000 PX est injectée dans votre économie.

---

## 🎭 Rôles & Gouvernance

Pour rejoindre un Forom, un utilisateur doit choisir un alignement qui dictera son rôle dans l'écosystème :

| Rôle | Couleur | Alignement | Fonction |
| --- | --- | --- | --- |
| **Gardien** | 🔴 Rouge | Défense | Fait respecter les règles, maintient la stabilité de la grille. |
| **Créateur** | 🟡 Jaune | Innovation | Produit le contenu (mémos), résout les quêtes techniques. |
| **Social** | 🔵 Bleu | Connexion | Gère le moral, accueille les nouveaux, organise les événements. |

*Note : On ne peut pas être invité en tant que Créateur. Il faut accomplir une quête et voir son mémo sélectionné par les Mods pour obtenir ce titre.*

---

## ⚙️ Matériel & Auto-Hébergement

Pour garantir une souveraineté totale sur vos **10 ans d'archives**, nous recommandons l'architecture matérielle suivante pour votre serveur :

* **Calcul (Compute) :** Une machine **NVIDIA Jetson** (Nano ou Orin). Crucial pour faire tourner le modèle local RAG (TensorRT/LLM) de votre ROM 24h/24.
* **Stockage :** Un SSD de **1 To minimum** pour stocker les textes, images et vecteurs d'IA.
* **Réseau :** Tourne sur `localhost` derrière un pare-feu jusqu'au déblocage de la Phase 3 (où un tunnel inversé est créé vers le Lobby).

---

## 🛠️ Stack Technique & Démarrage Dev

FOROM est propulsé par une stack moderne et performante, prête pour les environnements *Edge*.

| Technologie | Rôle |
| --- | --- |
| **React 19 & TypeScript** | Architecture des composants et typage strict |
| **Vite 7** | Build ultra-rapide et optimisation des chunks |
| **Tailwind CSS 4** | Styling utilitaire et thèmes via variables CSS |
| **Framer Motion 12** | Moteur physique pour la Sidebar et la Grille 5x5 |
| **JWT / OAuth2** | Single Sign-On (SSO) décentralisé via le Lobby |
| **PostgreSQL & Docker** | Base de données locale et déploiement conteneurisé |

### Installation (Développement)

# Cloner le dépôt
git clone https://github.com/Forom-ets/forom.git
cd forom

# Se placer sur la branche de développement active
git checkout vibecoderprofessionel

# Installer les dépendances
npm install

# Lancer le serveur local
npm run dev

L'application sera accessible sur http://localhost:5173.

## 🤝 Contribuer & Licence

<div align="center">

Forom est un projet Open Source. Forkez le code, modifiez l'économie, créez vos propres grilles et bâtissez votre univers.

<a href="https://creativecommons.org/licenses/by-sa/4.0/"><img src="https://licensebuttons.net/l/by-sa/4.0/88x31.png" alt="CC BY-SA 4.0" /></a>

Ce projet est distribué sous la licence Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0). Vous êtes libre de partager et d'adapter le matériel, à condition de créditer Forom et de partager vos modifications sous la même licence.

Développé avec ❤️ pour préserver la mémoire à long terme de l'humanité.

L'avenir de la navigation de contenu est fini.

</div>
