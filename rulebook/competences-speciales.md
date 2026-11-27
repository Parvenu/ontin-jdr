---
layout: default
title: Compétences spéciales
parent: Livre de règles
nav_order: 3
permalink: /rulebook/competences-speciales/
---

# Compétences spéciales

Les compétences spéciales représentent les domaines de spécialisation d'un personnage. Elles possèdent chacune leur propre score de maîtrise.

Leur apprentissage ou leur perfectionnement peut nécessiter un niveau minimum dans une ou plusieurs compétences normales.

*Exemple: un apprentissage de la Magie du feu demande une compétence de [Magie](../competences/#magie) d'au moins 30.*

Lorsqu'une action fait appel à une compétence spéciale, le jet s'effectue uniquement sur le score de cette dernière, sans effectuer de jet supplémentaire sur les compétences normales associées.

Certaines compétences normales peuvent également contribuer aux effets produits par une compétence spéciale, notamment dans le calcul des dégâts ou de la puissance.

## Apprentissage et progression des compétences spéciales

Par défaut, une compétence spéciale nouvellement apprise commence avec un score de **30**. Un tuteur peut toutefois définir directement un score d'enseignement supérieur : dans ce cas, une compétence absente est apprise à la valeur effective du tuteur.

Les compétences spéciales peuvent être apprises et perfectionnées de deux manières : grâce à un [**tuteur**](#tuteurs) ou par [**épiphanie**](#épiphanies).

### Tuteurs

Un tuteur est une source d'enseignement permettant d'apprendre ou d'améliorer une compétence normale ou spéciale. Il peut s'agir d'un professeur, d'un livre de compétences ou de toute autre source de savoir.

Chaque tuteur définit :
  - **La compétence normale ou spéciale enseignée.**
  - **Un score d'enseignement**, qui sert aussi de plafond de maîtrise.
  - **Des prérequis éventuels** : compétences normales, compétences spéciales, matériel, artefacts, consommables, paiement ou autres conditions.
  - **Une durée d'apprentissage**, généralement comprise entre un jour et une semaine.

Un tuteur peut posséder des valeurs fixes ou être une base mise à l'échelle par niveau. Pour une base calculée, le score d'enseignement et chaque minimum de compétence requis suivent séparément la formule :

```text
valeur effective = ceil(valeur de base + (niveau du tuteur − 1) × incrément par niveau)
```

Le niveau `1` restitue exactement la valeur de base et le résultat ne peut pas dépasser `100`. Le niveau `0` représente une base de tuteur non finalisée, inutilisable tant qu'un niveau jouable ne lui a pas été attribué. Une base peut limiter les niveaux auxquels un générateur est autorisé à la sélectionner. Les Items éventuellement requis ne sont jamais multipliés ni renforcés par le niveau du tuteur.

Lorsque les conditions sont réunies et que le temps nécessaire a été consacré à l'apprentissage, une compétence absente ou déjà connue progresse directement jusqu'au score effectif du tuteur. Le bonus permanent propre à la compétence reste séparé de ce score de base.

*Exemple : un traité de magie du Feu de niveau 3 possède un score de base de 35 et un incrément de 5 par niveau. Il enseigne donc Feu à 45. Son prérequis de Magie possède une base de 30 et un incrément de 2,5 : après arrondi supérieur, il exige 35 en Magie. Une potion particulière et trois jours d'étude peuvent également être demandés, sans que la potion ne scale avec le niveau.*

*Un personnage ne connaissant pas encore Feu l'apprend à 45. Un personnage possédant déjà 35 en Feu progresse jusqu'à 45. Un personnage possédant 60 en Feu n'en tire aucun bénéfice.*

### Épiphanies

Une épiphanie est une progression accordée directement par le MJ lorsqu'un événement ou les actions du personnage justifient une amélioration de sa maîtrise.

Elle peut notamment résulter d'une utilisation particulièrement ingénieuse d'une compétence, d'une expérience marquante, d'une découverte ou d'une rencontre extraordinaire.

Le MJ détermine la progression accordée selon les circonstances.

Contrairement aux tuteurs, **l'épiphanie ne nécessite ni dépense ni temps d'apprentissage supplémentaire** : le personnage a déjà acquis cette expérience au cours de l'aventure.

## Catalogue de compétences spéciales

On propose un catalogue **NON EXHAUSTIF** de compétences spéciales utilisées par les PNJ du monde :

### Artisanat et disciplines techniques

| Compétence spéciale | Prérequis d'apprentissage | Domaine d'application |
| - | - | - |
| Runologie | Connaissance des secrets ≥ 40, Artisanat, construire ≥ 30 | Étudier, concevoir et modifier les runes magiques |
| Formations magiques | Runologie ≥ 50, Connaissance des secrets ≥ 40 | Construire des réseaux d'inscriptions produisant des effets à grande échelle |
| Forgemagie | Runologie ≥ 30, Artisanat, construire ≥ 40 | Fabriquer des armes et armures enchantées par des runes |
| Ingénierie | Artisanat, construire ≥ 40 | Concevoir des mécanismes et machines complexes |


### Sciences, soins et investigation

| Compétence spéciale | Prérequis d'apprentissage | Domaine d'application |
| - | - | - |
| Dressage | Survie ≥ 40, Psychologie ≥ 30 | Éduquer, entraîner et diriger des animaux ou créatures extraordinaires |
| Alchimie | Connaissance de la nature ≥ 40, Magie ≥ 30 | Transformer et combiner des substances grâce à des procédés magiques |
| Apothicairerie | Connaissance de la nature ≥ 40 | Préparer des remèdes, poisons et antidotes |
| Médecine | 	Connaissance de la nature ≥ 40 | Diagnostiquer, traiter et opérer des patients |
| Investigation | Perception ≥ 40, Psychologie ≥ 30 | Reconstitution d'événements à partir d'indices, analyse méthodique d'une scène, recoupement de témoignages |

### Disciplines martiales

| Compétence spéciale | Prérequis d'apprentissage | Domaine d'application |
| - | - | - |
| Art de l'épée | Combat rapproché ≥ 40, Réflexes ≥ 30 | 	Maîtrise avancée du maniement de l'épée |
| Art des armes d'hast | Combat rapproché ≥ 40 | Techniques avancées de lance, hallebarde et armes apparentées |
| Art du tir | Combat à distance ≥ 40, Perception ≥ 30 | Techniques de tir exceptionnelles |
| Maîtrise corporelle | Athlétisme ≥ 40, Réflexes ≥ 30 | Développement physique, conditionnement, contrôle musculaire et exploits physiques |

### Disciplines magiques avancées

Certaines compétences spéciales permettent de prolonger une discipline ordinaire par la maîtrise de la magie.

Elles nécessitent généralement une maîtrise préalable de la discipline concernée ainsi qu'un certain niveau en [Magie](../competences/#magie).

Ces spécialisations permettent d'accomplir des actions dépassant les limites physiques naturelles, sans nécessairement relever d'un domaine de magie élémentaire ou fondamental.

*Exemple : Renforcement corporel magique*

| Compétence spéciale | Compétences associées | Domaine d'application |
| - | - | - |
| Renforcement corporel magique | Maîtrise corporelle ≥ 60, Magie ≥ 40 | Canaliser l'énergie magique dans son corps pour développer une force, une vitesse, une résistance et une mobilité surnaturelles. |

## Domaines de magie

Dans notre monde on catégorise la magie en plusieurs domaines, chaque domaine est une compétence spéciale du personnage et va régir sa capacité à executer des sorts ou manipulations **précises ou complexes** dans ce domaine.

Ces domaines ne sont pas des limites fixées à toutes les magies possibles dans notre monde.
Ce sont simplement des disciplines que les personnages peuvent apprendre ou développer *naturellement* au cours de leur aventure.
L'apprentissage des [domaines de magie](#domaines-de-magie) se fait via des professeurs, des livres de compétences, ou une épiphanie naturelle du personnage, leur maîtrise n'est pas innée.

L'apprentissage d'un domaine de magie nécessite un score d'au moins **40 en Magie**.

| Domaine | Périmètre |
| - | - |
| Feu | Produire, entretenir, déplacer ou éteindre des flammes ; manipuler la chaleur et provoquer une combustion. |
| Eau/Glace | Manipuler l'eau sous ses différentes formes, en modifier l'état, créer ou déplacer des masses d'eau et de glace. |
| Air | Manipuler les courants d'air, la pression et les mouvements de l'atmosphère. |
| Foudre | Produire, canaliser et manipuler les décharges électriques. |
| Terre | Manipuler la terre, la roche, le sable et les matières minérales naturelles. |
| Télékinésie | Exercer des forces à distance sur la matière inerte afin de la déplacer, la maintenir ou la manipuler sans contact. Ne permet pas d'exercer directement une force sur les êtres vivants. |
| Esprit | Développer et projeter sa conscience au-delà des limites du corps, percevoir l'environnement par le sens spirituel et établir des connexions avec certains objets magiques. La perception spirituelle traverse les obstacles physiques ordinaires, mais peut être bloquée par des formations, interdictions ou matériaux particuliers. |
| Espace | Manipuler les distances, les positions et les relations spatiales, permettant notamment des déplacements instantanés ou des distorsions de l'espace. |
| Temps | Percevoir ou modifier l'écoulement du temps, sa vitesse et éventuellement certaines relations temporelles entre les événements. |
| Mort | Pratiquer la nécromancie, animer et contrôler les dépouilles, infliger des malédictions et manipuler les âmes des défunts, notamment pour les emprisonner, les asservir ou exploiter leur énergie spirituelle. |

### Exemples de niveaux de maîtrise

> Les exemples suivants donnent des ordres de grandeur pour évaluer la maîtrise d'un domaine magique. Ils ne constituent ni une liste exhaustive de sorts ni des seuils de déblocage stricts. La faisabilité d'une manipulation dépend également de sa portée, de sa précision, de son intensité et des circonstances.

| Maîtrise | Feu | Télékinésie | Mort |
| - | - | - | - |
| 30-39 | Allumer une bougie ou produire une petite flamme| Déplacer un petit objet à quelques mètres, avec un contrôle assez rudimentaire | Animer de petits restes organiques, percevoir des traces de nécromancie ou des résidus d'âmes |
| 40-59 | Produire et diriger un jet de flammes | Manipuler plusieurs petits objets simultanément à une dizaine de mètres, ou déplacer un objet lourd | Réanimer un cadavre et lui donner des ordres simples, lancer des malédictions mineures, capturer de faibles résidus spirituels |
| 60-79 | Provoquer un incendie localisé et en contrôler la propagation | Contrôler précisément une dizaine d'objets à plusieurs dizaines de mètres, ou soulever une carriole | Contrôler plusieurs morts-vivants, infliger des malédictions persistantes, capturer et asservir des âmes dépouillées de leur conscience |
| 80-89 | Produire un brasier capable de ravager un bâtiment| Manipuler des dizaines d'objets indépendamment, à plusieurs centaines de mètres, ou soulever une masse considérable | Créer des serviteurs nécromantiques puissants et partiellement autonomes, infliger des malédictions difficiles à lever, emprisonner et exploiter des âmes puissantes |
| 90-100 | Déchaîner un incendie dévastateur à l'échelle d'un quartier | Contrôler simultanément des centaines d'objets sur une zone immense, ou déplacer des structures monumentales | Lever une armée de morts-vivants, imposer des malédictions dévastatrices sur une communauté entière ou asservir des légions d'âmes pour alimenter des rituels extraordinaires |
