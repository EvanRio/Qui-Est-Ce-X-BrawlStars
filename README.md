# 🌟 Brawl Stars : Qui est-ce ? 🕵️‍♂️

Bienvenue sur le dépôt du projet **Brawl Stars : Qui est-ce ?** ! 
Il s'agit d'une version web interactive et revisitée du célèbre jeu de société "Qui est-ce ?", mettant en vedette 103 personnages issus du jeu mobile Brawl Stars.

Ce projet a été codé par **[locyzz](https://locyzz.fr/)** (d'après un concept de **[Citron](https://youtube.com/@king.citron)**).

## 🎮 À propos du jeu

Le principe est simple : chaque joueur choisit un Brawler mystère et le note dans le champ de texte prévu à cet effet. Ensuite, posez-vous des questions à tour de rôle (ex: "Ton brawler a-t-il des lunettes ?", "Est-ce un tireur d'élite ?"). 

Au fur et à mesure des réponses, cliquez sur les portraits des Brawlers pour les éliminer (une croix rouge apparaîtra dessus). Le premier à deviner le personnage de l'adversaire remporte la partie !

## ✨ Fonctionnalités

* **Roster Complet :** Une grille dynamique contenant 103 Brawlers.
* **Filtre visuel interactif :** Un simple clic sur une case permet de griser/barrer un personnage éliminé.
* **Champ de mémorisation :** Un espace pour écrire et garder en mémoire le nom de son propre personnage.
* **100% Responsive :** L'affichage s'adapte automatiquement à votre écran, que vous soyez sur PC (grille large) ou sur Mobile (grille compacte).
* **Interface thématique :** Utilisation de la police `Lilita One` et d'un code couleur rappelant les menus du jeu.

## 🛠️ Technologies utilisées

Ce projet est un projet web statique léger et rapide, sans dépendances complexes :
* **HTML5** : Structure de la page.
* **CSS3** : Mise en page en Grid (`display: grid`), responsive design et animations visuelles.
* **JavaScript (Vanilla)** : Génération automatique de la grille des 103 Brawlers et gestion des clics (toggle de classe).

## 🚀 Installation et exécution

Ce projet ne nécessite aucune installation de serveur ou de base de données. 

1. **Cloner ou télécharger le dépôt :**
   ```bash
   git clone https://github.com/EvanRio/quiestcexbrawlstars.git
   ```

2. **Préparer les images :**
   Assurez-vous d'avoir un dossier `images/` à la racine du projet contenant :
   * Le logo du jeu : `logo.png`
   * Les portraits des Brawlers nommés de `1.png` à `103.png`.

3. **Lancer le jeu :**
   Ouvrez simplement le fichier `index.html` dans n'importe quel navigateur web (Chrome, Firefox, Safari, etc.).

## 🤝 Crédits

* **Développement Web :** [locyzz](https://locyzz.fr/)
* **Concept Original :** [Citron sur YouTube](https://youtube.com/@king.citron)

## 📝 Licence & Disclaimer

**⚠️ Disclaimer :** *Ce projet est une création de fan à but non lucratif. Il n'est pas affilié, sponsorisé, ni approuvé par Supercell. Brawl Stars et ses personnages sont des marques déposées de Supercell.*