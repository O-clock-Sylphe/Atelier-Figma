# Frames

## C'est quoi la différence entre une frame et une forme

Pour créer des éléments de base sur Figma, nous allons différencier deux éléments de base :

- **Frame** : la frame est un cadre de travail où vous allez déposer différents éléments, formes, ... composant votre maquette. C'est votre feuille de papier ! 📜
- **Forme** : Les formes sur Figma sont des éléments de base qui vont vous servir à créer les éléments composant votre maquette. Rectangle, rond, triangle... Tout part d'une forme simple que l'on adapte, module à notre envie. 👩‍🎨

---

## Création d'une première frame

Débutons notre travail de recréation de la maquette en créant une frame pour la page d'accueil. 🖼️ Notre maquette est une reproduction d'un écran d'ordinateur classique 🖥️.

Rends-toi sur la barre d'outils et sélectionne l'outil Frame (raccourci clavier `F`) :

<p align="center">
    <img src="../assets/05-figma-frames/barre-outils-creation-frame.png"/>
</p>

Après avoir sélectionné l'outil de création de frames dans Figma, tu remarqueras l'apparition, sur la partie droite de ton écran 💻➡️, d'une variété de templates prédéfinis. Ces templates sont disponibles en différentes tailles, adaptées aux supports les plus couramment utilisés aujourd'hui : mobiles, tablettes, et écrans d'ordinateur. Idéal pour gagner un temps fou ! 😎

<p align="center">
    <img src="../assets/05-figma-frames/inspecteur-frame-types.png"/>
</p>

Tu peux aussi réaliser ta propre frame via ta souris en maintenant le clic-gauche, comme ceci :

<p align="center">
    <img src="../assets/05-figma-frames/frame-main-libre.gif"/>
</p>

### Option d'une frame

Super ! 🎉 On vient de créer notre première frame. Avant d'aller plus loin, on va analyser les options présentes sur le panneau de droite de l'outil.

<p align="center">
    <img src="../assets/05-figma-frames/inspecteur-frame-options.png"/>
</p>

> 💡 Chque forme/frame que tu sélectionne sur Figma a son panneau de configuration. Il s'adapte en fonction du type d'objet que tu manipules. Le panneau d'une frame n'est pas le même que celui d'un objet, d'une police de caractères, ...

### Options générales

Attaquons-nous tout d'abord aux options de positionnement et de dimensions de notre frame :

<p align="center">
    <img src="../assets/05-figma-frames/inspecteur-frame-opt-dim-pos.png"/>
</p>

- Tout d'abord, si vous cliquez sur l'option `Frame 🔽`, vous allez pouvoir redimensionner votre cadre de travail selon les templates prédéfinis sur Figma ! Utile, si vous souhaitez changer rapidement sans avoir à tout recommencer.

- A droite de `Frame 🔽`, vous avez un rectangle **vertical** et un rectangle **horizontal** : il s'agit ici d'une option pour faire une rotation de votre frame. Essayez de cliquez dessus, vous verrez que votre frame se tourne automatiquement en fonction de l'option choisie (de base horizontalement ↔️). C'est très pratique si vous souhaitez partir d'un template d'un écran qui devra être présenté en fonction de l'usage de l'utilisateur comme pour l'écran d'un smartphone 📱.

<p align="center">
    <img src="../assets/05-figma-frames/frame-rotation.gif" width="400px"/>
</p>

- La dernière option de cette ligne se nomme **"Resize to fit"** ("redimensionner pour s'adapter"). Ce n'est pas une option très utilisée dans le cadre d'une frame qui représenterait une page web mais si vous créez des frames à main levée qui contiennnent différents éléments et dont vous souhaitez enlever les marges intérieures (le padding, ça vous dit quelque chose ? 😏), vous pouvez cliquer sur "Resize to fit" pour avoir redimensionnement automatique de votre frame selon ce qu'elle contient. Démonstration :

<p align="center">
    <img src="../assets/05-figma-frames/resize-to-fit.gif" width="400px"/>
</p>

#### Positionnement 📍

Comme lorsque vous faites du CSS (j'en vois certains en sueurs 😰), chaque élément a une position selon l'endroit (le parent) dans lequel il est situé. Pour une frame ou une forme créée (carré, rond, ...), vous pouvez indiquez la position initiale de celle-ci.

_Mais si une frame représente une de nos maquettes, par qui est-elle contenue ?_ 🤔

Hé bien, chaque frame est contenue dans notre espace de travail. L'espace de travail est un peu le `<>` de notre projet dans lequel nous allons mettre toutes nos frames. 👌

Ici, nous pouvons donc choisir la position de notre élément. Pour être plus précis, de base nous allons indiquer où va débuter notre frame et pour cela il faut savoir définir le point d'ancrage ⚓.

De base, elle se situe en haut à gauche et le sera obligatoirement pour nos frames (ce ne sera pas le cas de nos éléments créés dont on pourra choisir le point d'ancre).

Les options pour positionner sont définies par deux axes (retour au collège 😰) :

- L'axe horizontal (X) ↔️
- L'axe vertical (Y) ↕️

#### Dimensions 📐

Si un objet a une position, il a aussi une dimension 🐘. Et elles vous sont familières ces deux options car vous avez dû les utiliser en CSS :

- `W` pour `width` (largeur) : cette option définit la largeur de notre frame ou notre objet.
- `H` pour `height` (hauteur) : cette option définit la hauteur de notre frame ou notre objet.

> 📏 L'unité de chacune de ces options est en `px` (pixel).

Vous pouvez très bien changer ces options librement, vous pouvez même faire un calcul dans ces zones. Imaginons que je souhaite que ma frame soit d'une largeur de 4 fois 375px (`4 * 375`), il me suffit d'entrer cette opération dans mon champ et appuyer sur entrée :

<p align="center">
    <img src="../assets/05-figma-frames/math-input.gif" width="400px"/>
</p>

> 🧮Addition, soustraction, multiplication, division ! Figma vous évitera les prises de tête afin de faire toutes vos opérations à votre place. Quel ami ! 😌

Il y a plein d'autres options disponiles mais qui n'ont pas réellement d'intérêt premier lorsque l'on parle d'une frame. Toutefois, nous allons en parler via les formes ! 😃

---

### À ton tour

Pour notre première frame, nous souhaitons réaliser utiliser la résolution d'un écran standard. Sélectionne l'outil `Frame` puis cherche le template `Desktop`.

Puis renomme cette frame en faisant un clic-droit sur le nom `Desktop -1` dans le panneau latéral gauche > `Rename` ou en double cliquant sur le nom de la frame situé en haut à gauche de celle-ci. Appelles-la `Homepage`.

Enfin, repositionne-la dans notre espace de travail en vérifiant que les coordonnées X et Y soient sur `0`.

---

[◀️ Figma - Projet fil rouge](./04-figma-fil-rouge.md)

[Figma - Formes ▶️](./06-figma-formes.md)

[Retour à l'accueil 📍](../README.md)
