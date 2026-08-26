# ♟ Tic-Tac-Toe — Movable Pieces

> Ce n'est pas le Tic-Tac-Toe que tu connais.

---

## Aperçu

| Desktop | Mobile |
|--------|--------|
| ![Desktop](desktop%20vesion.png) | ![Mobile](mobile%20version.png) |

---

## C'est quoi ce jeu ?

**Tic-Tac-Toe — Movable Pieces** est une réinvention du célèbre jeu de morpion.  
La règle change tout : tes pièces **ne restent pas figées**. Après les avoir placées, tu peux les **déplacer** — mais seulement vers des positions précises, reliées entre elles par un graphe de connexions.

Le centre du plateau connecte tout. Le contrôler, c'est avoir le pouvoir.

---

## Comment ça se joue ?

Le jeu se déroule en **deux phases** :

### 1. Phase de placement
Chaque joueur dispose d'un stock de pièces en réserve.  
Tour par tour, tu places une pièce sur une case vide du plateau.  
La phase se termine quand toutes les pièces sont posées.

![Gameplay Desktop](desk.gif)

### 2. Phase de mouvement
Les pièces prennent vie.  
À chaque tour, tu déplaces une de tes pièces vers une case **directement connectée** à sa position actuelle.  
Pas de saut, pas de liberté totale — chaque mouvement suit les règles du graphe.

L'objectif reste le même : **aligner 3 pièces** en ligne, colonne ou diagonale.

![Gameplay Mobile](mob.gif)

---

## Ce qui rend ce jeu unique

- **Les pièces bougent** — la partie ne se fige jamais, tout peut basculer
- **Le plateau est un graphe** — chaque position a des voisins précis, pas une grille libre
- **Le centre est roi** — la position centrale connecte toutes les autres, c'est le point stratégique clé
- **Multijoueur en temps réel** — joue contre quelqu'un d'autre, en direct
- **Transitions animées** — les pièces se déplacent avec fluidité sur le plateau

---

## Le plateau

```
1 — 2 — 3
|\ | /|
| \|/ |
4 — 5 — 6
| /|\ |
|/ | \|
7 — 8 — 9
```

La position **5** (centre) est connectée à toutes les autres.  
Les positions en coin (1, 3, 7, 9) n'ont que 3 voisins.  
Chaque mouvement compte.

---

## Lignes gagnantes

Aligne 3 pièces sur l'une de ces combinaisons :

| Type       | Combinaisons              |
|------------|---------------------------|
| Lignes     | 1-2-3 · 4-5-6 · 7-8-9    |
| Colonnes   | 1-4-7 · 2-5-8 · 3-6-9    |
| Diagonales | 1-5-9 · 3-5-7             |

---

## Tu veux jouer, collaborer ou en savoir plus ?

Ce projet a été conçu et développé par **Aaron Vyaleveka**.

N'hésite pas à me contacter :

- 🌐 Portfolio : [switchs.dev](https://www.switchs.dev)
- ✍️ Blog : [switchs.dev/blog](https://www.switchs.dev/blog)
- 💌 Email : [arrowvyaleveka@gmail.com](mailto:arrowvyaleveka@gmail.com)
- 💼 LinkedIn : [Aaron Vyaleveka](https://www.linkedin.com/in/aaron-vyaleveka-04877b369/)
- 🐙 GitHub : [@AaronDAmin](https://github.com/AaronDAmin)

> Que ce soit pour jouer, discuter du projet, proposer une collaboration ou juste dire bonjour — je suis disponible.

---

*Fait avec passion. © Aaron Vyaleveka*
