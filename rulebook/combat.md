---
layout: default
title: Combat
parent: Livre de règles
nav_order: 6
permalink: /rulebook/combat/
---

# Combat

Le combat repose sur un principe simple : une attaque réalisable touche sa cible, sauf si celle-ci parvient à se défendre.

Contrairement aux actions ordinaires, l'attaquant n'effectue donc pas de jet pour déterminer s'il touche. Les jets sont effectués par les défenseurs lorsqu'ils tentent d'éviter une attaque.

## Initiative 

Au début d'un combat les intervenants vont lancer l'initiative pour déterminer l'ordre de jeu.

`Initiative = 1d100 + Réflexes`

Le plus grand chiffre joue en premier, en cas d'égalité priorité aux joueurs.

## Résolution d'une attaque

1. Déclaration de l'attaque : l'attaquant choisit sa cible et son action. Le MJ vérifie que l'attaque est réalisable compte tenu de la portée, de la position et des circonstances.
2. Effets préalables : les éventuels effets On Action sont appliqués avant la défense.
3. Défense réactive : si elle en a la possibilité, la cible tente une Parade ou une Esquive.
4. Résolution : si la défense réussit, l'attaque est annulée. Sinon, elle touche et ses dégâts et effets à l'impact sont appliqués.

Une cible incapable de se défendre est touchée automatiquement.

## Parade et Esquive

Les personnages disposent de deux compétences défensives :

| Compétence | Utilisation |
| - | - |
| Parer | Intercepter ou dévier une attaque avec une arme, un bouclier ou un moyen adapté. |
| Esquiver | Éviter physiquement une attaque en se déplaçant. |

La Parade peut être utilisée contre des attaques au corps à corps comme à distance, à condition de disposer d'un moyen crédible de les intercepter.

L'Esquive peut être utilisée contre toute attaque physiquement évitable, mais subit un malus important au corps à corps.

*Exemple : Une flèche peut être esquivée ou interceptée par un bouclier adapté, tandis qu'une boule de feu doit généralement être esquivée, sauf protection particulière.*

### Modificateurs défensifs

Le score offensif de l'attaquant impose un malus au jet défensif. L'Esquive subit également un malus important lorsqu'elle est utilisée contre une attaque au corps à corps.

| Compétence offensive | Malus défensif |
| - | - |
| 0-29 | 0 |
| 30-59 | −10 |
| 60-79 | −20 |
| 80-100 | −30 |

L'Esquive subit un malus supplémentaire de −20 contre les attaques au corps à corps.

Lorsqu'un personnage tente plusieurs défenses au cours d'un même tour, chaque défense après la première subit un malus cumulatif de −10. Ce malus est réinitialisé au début du tour suivant.

Tous les malus applicables se cumulent.

Le défenseur effectue un unique jet de d100 :
  - **Résultat inférieur ou égal à la compétence défensive modifiée** : l'attaque est annulée.
  - **Résultat supérieur** : la défense échoue et l'attaque touche.


## TLDR Dégats

 - Arme fait dégâts.
 - Moi fort en compétence ? Arme tape plus fort (vraiment).
 - Arme magique ? Peut faire dégâts bonus.
 - Dégâts bonus sur effet d'arme viennent de l'arme, pas de moi.
 - Dés sur arme faire 25% des dégats.
  
## Dégâts et résistances

### Types de dégâts

Il existe deux types de dégâts :

- **Physiques**
- **Magiques**

Chaque attaque peut infliger une ou plusieurs lignes de dégâts, chacune possédant son propre type et sa propre valeur.

### Calcul des dégâts

Chaque arme ou attaque magique possède une formule de dégâts de base, composée de dés et d'une valeur fixe, par exemple `2d8+27`.

Les dégâts principaux sont amplifiés par les compétences du personnage selon la formule :

`Dégâts bruts = Dégâts de base × (1 + 2 × (Compétence normale + Compétence spéciale) / 100)`

- **Dégâts de base** : résultat de la formule de dégâts de l'arme ou de l'attaque.
- **Compétence normale** : compétence normale utilisée pour l'attaque.
- **Compétence spéciale** : compétence spéciale associée à l'attaque, ou 0 si le personnage ne la possède pas.

Pour une attaque physique, on utilise **Combat rapproché** ou **Combat à distance**, ainsi que l'éventuelle discipline martiale correspondante.

Pour une attaque magique, on utilise **Magie** et le domaine magique concerné.

Les armes sont généralement conçues pour qu'environ **25 % de leurs dégâts moyens proviennent des dés et 75 % d'une valeur fixe**.

### TLDR Résitances

- Deux types : physique et magique.
- Résistance % réduit dégâts d'abord.
- Résistance fixe enlève dégâts ensuite.
- Plusieurs lignes de dégâts ? Résistance appliquée à chaque ligne séparément.

### Résistances

Chaque personnage possède quatre valeurs de résistance :

| Résistance | Fonction |
| - | - |
| Physique (%) | Réduction proportionnelle des dégâts physiques |
| Physique fixe | Réduction fixe des dégâts physiques |
| Magique (%) | Réduction proportionnelle des dégâts magiques |
| Magique fixe | Réduction fixe des dégâts magiques |

Pour chaque ligne de dégâts, on applique d'abord la résistance en pourcentage, puis la résistance fixe correspondante :

`Dégâts reçus = max(0, Dégâts bruts × (1 - Résistance % / 100) - Résistance fixe)`

Les dégâts reçus ne peuvent pas être négatifs.

### Attaques à plusieurs lignes

Lorsqu'une attaque inflige plusieurs lignes de dégâts, **chaque ligne est réduite indépendamment** par les résistances de son type.

Les dégâts restants sont ensuite additionnés pour obtenir les dégâts totaux subis.

*Exemple :* Une épée enchantée inflige 100 dégâts physiques et 40 dégâts magiques.

La cible possède :
- 20 % de résistance physique et 15 de résistance physique fixe ;
- 25 % de résistance magique et 10 de résistance magique fixe.

La ligne physique inflige : `100 × 0,80 - 15 = 65`.

La ligne magique inflige : `40 × 0,75 - 10 = 20`.

**Total : 85 dégâts reçus.**

### Effets additionnels des armes

Certaines armes disposent d'effets supplémentaires déclenchés lorsqu'une attaque touche (*On Hit*).

Ces effets peuvent notamment ajouter des lignes de dégâts physiques ou magiques.

Contrairement aux dégâts principaux de l'attaque, **les lignes de dégâts additionnelles provenant de l'objet ne sont pas amplifiées par les compétences du personnage**.

Elles sont néanmoins soumises aux résistances habituelles, indépendamment des autres lignes de dégâts.

## Magie persistante en combat

Certains effets magiques nécessitent une concentration continue pour être maintenus, comme la manipulation d'objets par Télékinésie.

D'autres effets peuvent persister naturellement après leur création, comme une brume ou un incendie. Ceux-ci ne nécessitent pas de concentration.

### Maintien de la concentration

Lorsqu'un personnage maintenant un sort subit une attaque qui le touche, il doit effectuer un jet de concentration pour maintenir son effet.

Ce jet utilise directement la compétence spéciale du domaine magique concerné.

La compétence offensive de l'attaquant impose un malus selon les mêmes paliers que les défenses :

| Compétence offensive | Malus de concentration |
| - | - |
| 0–29 | 0 |
| 30–59 | −10 |
| 60–79 | −20 |
