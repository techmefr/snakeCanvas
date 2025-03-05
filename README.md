# Snake Canvas

Un jeu Snake classique implémenté avec HTML Canvas et JavaScript.

## 📋 Description

Ce projet est une implémentation simple mais fonctionnelle du jeu classique Snake. Le joueur contrôle un serpent qui grandit en mangeant de la nourriture et doit éviter de se cogner contre les murs ou contre lui-même.

## ✨ Caractéristiques

- **Contrôles intuitifs** - Utilisation des touches fléchées du clavier
- **Mécanique de croissance** - Le serpent s'allonge en mangeant
- **Système de score** - Affichage du nombre de nourritures mangées
- **Détection de collision** - Fin de partie si le serpent touche un mur ou son propre corps

## 🛠️ Technologies utilisées

- HTML5 Canvas
- JavaScript vanilla
- CSS minimal

## 💡 Fonctionnalités techniques

- **Rendu Canvas**: Affichage graphique optimisé
- **Détection de collision**: Algorithme vérifiant les contacts avec les murs et le corps du serpent
- **Génération aléatoire**: Placement de la nourriture à des positions aléatoires

```javascript
function collision(head, array) {
    for (let g = 0; g < array.length; g++) {
        if (head.x == array[g].x && head.y == array[g].y) {
            return true;
        }
    }
    return false;
}
```

## 🎮 Contrôles

- **Flèches directionnelles**: Déplacent le serpent dans les quatre directions

## 🎨 Personnalisation

- **Taille du serpent**: Modifiez la valeur de `box` (20 pixels)
- **Vitesse du jeu**: Ajustez l'intervalle dans `setInterval(draw, 100)`
- **Couleurs**: Modifiez les valeurs de `fillStyle` pour chaque élément

## 📥 Installation

1. Clonez ce dépôt
2. Ouvrez `index.html` dans votre navigateur

## 🚀 Applications pédagogiques

Ce projet illustre:
- Les fondamentaux du développement de jeux en JavaScript
- L'utilisation de Canvas pour le rendu graphique
- Les boucles de jeu et la détection de collision

## 📝 Licence

[MIT](https://choosealicense.com/licenses/mit/)

---

Créé par [Gaëtan Compigni](https://github.com/techmefr)
